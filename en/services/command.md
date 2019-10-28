# Command Protocol

The MAVLink command protocol allows guaranteed delivery of MAVLink commands.

Commands are values of [MAV_CMD](#MAV_CMD) that define the values of up to 7 parameters.
These parameters and the command id are encoded in [COMMAND_INT](#COMMAND_INT) or [COMMAND_LONG](#COMMAND_LONG) for sending.

The protocol provides reliable delivery by expecting a matching acknowledgement (`COMMAND_ACK`) from commands to indicate command arrival, and result.
If not acknowledgement is received the command must be automatically re-sent.

> **Note** `COMMAND_INT` is generally recommended when sending positional information as it allows greater precision, and is explicit about the co-ordinate frame.
  Commands that require float-only properties in parameters 5, 6 must be sent in `COMMAND_LONG` (e.g. commands where NaN has an explicit meaning).  

## Message/Enum Summary

Message | Description
-- | --
<span id="COMMAND_INT"></span>[COMMAND_INT](../messages/common.md#COMMAND_INT) | Message for encoding a command ([MAV_CMD](#MAV_CMD)). The message encodes commands into up to 7 parameters: parameters 1-4, 7 are floats, and parameters 5,6 are scaled integers. The scaled integers are used for positional information (scaling depends on the actual command value). The coordinate frame of positional parameters is explicitly specified in a frame field. Commands that require float-only properties in parameters 5, 6 cannot be sent in this message (e.g. commands where NaN has an explicit meaning).
<span id="COMMAND_LONG"></span>[COMMAND_LONG](../messages/common.md#COMMAND_LONG) | Message for encoding a command ([MAV_CMD](#MAV_CMD)). The mesage encodes commands into up to 7 float parameters. The coordinate frame used for positional co-ordinates is implementation dependent. Any command may be packaged in this message, but there may be some loss of precision for positional co-ordinates (latitude, longitude).
<span id="COMMAND_ACK"></span>[COMMAND_ACK](../messages/common.md#COMMAND_ACK) | Command acknowledgement. Includes result (success, failure, still in progress) and may include progress information and additional detail about failure reasons.


Enum | Description
-- | --
<span id="MAV_CMD"></span>[MAV_CMD](../messages/common.md#mav_commands) | Commands to be executed/sent in the command messages.
<span id="MAV_FRAME"></span>[MAV_FRAME](../messages/common.md#MAV_FRAME) | Coordinate frame. Used `COMMAND_INT` to specify co-ordinate frame of an positional parameters.
<span id="MAV_RESULT"></span>[MAV_RESULT](../messages/common.md#MAV_RESULT) | Result of command, included in [COMMAND_ACK.result](#COMMAND_ACK).


## Sequences

{% mermaid %}
sequenceDiagram;
    participant GCS
    participant Drone
    GCS->>Drone: COMMAND_LONG(confirmation=0)
    GCS->>GCS: Start timeout
    Drone->>GCS: COMMAND_ACK
{% endmermaid %}

If the command drops the sender should increase the confirmation field:

{% mermaid %}
sequenceDiagram;
    participant GCS
    participant Drone
    GCS->>Drone: COMMAND_LONG(confirmation=0)
    GCS->>GCS: Start timeout
    GCS->>Drone: COMMAND_LONG(confirmation=1)
    GCS->>GCS: Start timeout
    Drone->>GCS: COMMAND_ACK
{% endmermaid %}

The command may not complete immediately, in which case the drone can report its progress by sending `COMMMAND_ACK` messages with `COMMAND_ACK.result=`[MAV_RESULT_IN_PROGRESS](../messages/common.md#MAV_RESULT_IN_PROGRESS) and the progress as a percentage in `COMMMAND_ACK.progress` ([0-100] percent complete, 255 if progrss not supplied). 
When the operation completes, the drone must terminate with a `COMMMAND_ACK` containing the final [result](#MAV_RESULT) of the operation (e.g. failed, accepted, etc.).

{% mermaid %}
sequenceDiagram;
    participant GCS
    participant Drone
    GCS->>Drone: COMMAND_LONG()
    GCS->>GCS: Start timeout
    Drone->>GCS: COMMAND_ACK(result=MAV_RESULT_IN_PROGRESS,progress=?)
    GCS->>GCS: Start timeout
    Drone->>GCS: COMMAND_ACK(result=MAV_RESULT_IN_PROGRESS,progress=?)
    GCS->>GCS: Start timeout
    Note right of GCS: ...
    Drone->>GCS: COMMAND_ACK(result=MAV_RESULT_ACCEPTED)
{% endmermaid %}

