<html>
 <body>
  <h1>MAVLink Protocol Version</h1>
  <p>This file has protocol version: 3. The version numbers range from 1-255.</p>0<h1>MAVLink Type Enumerations</h1>
  <h2 class="mavlink_message_name" id="MAV_AUTOPILOT" name="ENUM_MAV_AUTOPILOT">MAV_AUTOPILOT</h2>
  <p class="description">Micro air vehicle / autopilot classes. This identifies the individual model.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_GENERIC">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_GENERIC</td>
     <td class="mavlink_comment">Generic autopilot, full support for everything</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_RESERVED">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_RESERVED</td>
     <td class="mavlink_comment">Reserved for future use.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_SLUGS">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_SLUGS</td>
     <td class="mavlink_comment">SLUGS autopilot, http://slugsuav.soe.ucsc.edu</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_ARDUPILOTMEGA">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_ARDUPILOTMEGA</td>
     <td class="mavlink_comment">ArduPilotMega / ArduCopter, http://diydrones.com</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_OPENPILOT">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_OPENPILOT</td>
     <td class="mavlink_comment">OpenPilot, http://openpilot.org</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_GENERIC_WAYPOINTS_ONLY">
     <td class="mavlink_type" valign="top">5</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_GENERIC_WAYPOINTS_ONLY</td>
     <td class="mavlink_comment">Generic autopilot only supporting simple waypoints</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_GENERIC_WAYPOINTS_AND_SIMPLE_NAVIGATION_ONLY">
     <td class="mavlink_type" valign="top">6</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_GENERIC_WAYPOINTS_AND_SIMPLE_NAVIGATION_ONLY</td>
     <td class="mavlink_comment">Generic autopilot supporting waypoints and other simple navigation commands</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_GENERIC_MISSION_FULL">
     <td class="mavlink_type" valign="top">7</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_GENERIC_MISSION_FULL</td>
     <td class="mavlink_comment">Generic autopilot supporting the full mission command set</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_INVALID">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_INVALID</td>
     <td class="mavlink_comment">No valid autopilot, e.g. a GCS or other MAVLink component</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_PPZ">
     <td class="mavlink_type" valign="top">9</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_PPZ</td>
     <td class="mavlink_comment">PPZ UAV - http://nongnu.org/paparazzi</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_UDB">
     <td class="mavlink_type" valign="top">10</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_UDB</td>
     <td class="mavlink_comment">UAV Dev Board</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_FP">
     <td class="mavlink_type" valign="top">11</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_FP</td>
     <td class="mavlink_comment">FlexiPilot</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_PX4">
     <td class="mavlink_type" valign="top">12</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_PX4</td>
     <td class="mavlink_comment">PX4 Autopilot - http://pixhawk.ethz.ch/px4/</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_SMACCMPILOT">
     <td class="mavlink_type" valign="top">13</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_SMACCMPILOT</td>
     <td class="mavlink_comment">SMACCMPilot - http://smaccmpilot.org</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_AUTOQUAD">
     <td class="mavlink_type" valign="top">14</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_AUTOQUAD</td>
     <td class="mavlink_comment">AutoQuad -- http://autoquad.org</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_ARMAZILA">
     <td class="mavlink_type" valign="top">15</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_ARMAZILA</td>
     <td class="mavlink_comment">Armazila -- http://armazila.com</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_AEROB">
     <td class="mavlink_type" valign="top">16</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_AEROB</td>
     <td class="mavlink_comment">Aerob -- http://aerob.ru</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_ASLUAV">
     <td class="mavlink_type" valign="top">17</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_ASLUAV</td>
     <td class="mavlink_comment">ASLUAV autopilot -- http://www.asl.ethz.ch</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_SMARTAP">
     <td class="mavlink_type" valign="top">18</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_SMARTAP</td>
     <td class="mavlink_comment">SmartAP Autopilot - http://sky-drones.com</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_TYPE" name="ENUM_MAV_TYPE">MAV_TYPE</h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_TYPE_GENERIC">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_GENERIC</td>
     <td class="mavlink_comment">Generic micro air vehicle.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_FIXED_WING">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_FIXED_WING</td>
     <td class="mavlink_comment">Fixed wing aircraft.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_QUADROTOR">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_QUADROTOR</td>
     <td class="mavlink_comment">Quadrotor</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_COAXIAL">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_COAXIAL</td>
     <td class="mavlink_comment">Coaxial helicopter</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_HELICOPTER">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_HELICOPTER</td>
     <td class="mavlink_comment">Normal helicopter with tail rotor.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_ANTENNA_TRACKER">
     <td class="mavlink_type" valign="top">5</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_ANTENNA_TRACKER</td>
     <td class="mavlink_comment">Ground installation</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_GCS">
     <td class="mavlink_type" valign="top">6</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_GCS</td>
     <td class="mavlink_comment">Operator control unit / ground control station</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_AIRSHIP">
     <td class="mavlink_type" valign="top">7</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_AIRSHIP</td>
     <td class="mavlink_comment">Airship, controlled</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_FREE_BALLOON">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_FREE_BALLOON</td>
     <td class="mavlink_comment">Free balloon, uncontrolled</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_ROCKET">
     <td class="mavlink_type" valign="top">9</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_ROCKET</td>
     <td class="mavlink_comment">Rocket</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_GROUND_ROVER">
     <td class="mavlink_type" valign="top">10</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_GROUND_ROVER</td>
     <td class="mavlink_comment">Ground rover</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_SURFACE_BOAT">
     <td class="mavlink_type" valign="top">11</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_SURFACE_BOAT</td>
     <td class="mavlink_comment">Surface vessel, boat, ship</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_SUBMARINE">
     <td class="mavlink_type" valign="top">12</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_SUBMARINE</td>
     <td class="mavlink_comment">Submarine</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_HEXAROTOR">
     <td class="mavlink_type" valign="top">13</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_HEXAROTOR</td>
     <td class="mavlink_comment">Hexarotor</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_OCTOROTOR">
     <td class="mavlink_type" valign="top">14</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_OCTOROTOR</td>
     <td class="mavlink_comment">Octorotor</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_TRICOPTER">
     <td class="mavlink_type" valign="top">15</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_TRICOPTER</td>
     <td class="mavlink_comment">Tricopter</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_FLAPPING_WING">
     <td class="mavlink_type" valign="top">16</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_FLAPPING_WING</td>
     <td class="mavlink_comment">Flapping wing</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_KITE">
     <td class="mavlink_type" valign="top">17</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_KITE</td>
     <td class="mavlink_comment">Kite</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_ONBOARD_CONTROLLER">
     <td class="mavlink_type" valign="top">18</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_ONBOARD_CONTROLLER</td>
     <td class="mavlink_comment">Onboard companion controller</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_VTOL_DUOROTOR">
     <td class="mavlink_type" valign="top">19</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_VTOL_DUOROTOR</td>
     <td class="mavlink_comment">Two-rotor VTOL using control surfaces in vertical operation in addition. Tailsitter.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_VTOL_QUADROTOR">
     <td class="mavlink_type" valign="top">20</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_VTOL_QUADROTOR</td>
     <td class="mavlink_comment">Quad-rotor VTOL using a V-shaped quad config in vertical operation. Tailsitter.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_VTOL_TILTROTOR">
     <td class="mavlink_type" valign="top">21</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_VTOL_TILTROTOR</td>
     <td class="mavlink_comment">Tiltrotor VTOL</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_VTOL_RESERVED2">
     <td class="mavlink_type" valign="top">22</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_VTOL_RESERVED2</td>
     <td class="mavlink_comment">VTOL reserved 2</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_VTOL_RESERVED3">
     <td class="mavlink_type" valign="top">23</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_VTOL_RESERVED3</td>
     <td class="mavlink_comment">VTOL reserved 3</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_VTOL_RESERVED4">
     <td class="mavlink_type" valign="top">24</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_VTOL_RESERVED4</td>
     <td class="mavlink_comment">VTOL reserved 4</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_VTOL_RESERVED5">
     <td class="mavlink_type" valign="top">25</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_VTOL_RESERVED5</td>
     <td class="mavlink_comment">VTOL reserved 5</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_GIMBAL">
     <td class="mavlink_type" valign="top">26</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_GIMBAL</td>
     <td class="mavlink_comment">Onboard gimbal</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_ADSB">
     <td class="mavlink_type" valign="top">27</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_ADSB</td>
     <td class="mavlink_comment">Onboard ADSB peripheral</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_PARAFOIL">
     <td class="mavlink_type" valign="top">28</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_PARAFOIL</td>
     <td class="mavlink_comment">Steerable, nonrigid airfoil</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="FIRMWARE_VERSION_TYPE" name="ENUM_FIRMWARE_VERSION_TYPE">FIRMWARE_VERSION_TYPE</h2>
  <p class="description">These values define the type of firmware release.  These values indicate the first version or release of this type.  For example the first alpha release would be 64, the second would be 65.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="FIRMWARE_VERSION_TYPE_DEV">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">FIRMWARE_VERSION_TYPE_DEV</td>
     <td class="mavlink_comment">development release</td>
    </tr>
    <tr class="mavlink_field" id="FIRMWARE_VERSION_TYPE_ALPHA">
     <td class="mavlink_type" valign="top">64</td>
     <td class="mavlink_name" valign="top">FIRMWARE_VERSION_TYPE_ALPHA</td>
     <td class="mavlink_comment">alpha release</td>
    </tr>
    <tr class="mavlink_field" id="FIRMWARE_VERSION_TYPE_BETA">
     <td class="mavlink_type" valign="top">128</td>
     <td class="mavlink_name" valign="top">FIRMWARE_VERSION_TYPE_BETA</td>
     <td class="mavlink_comment">beta release</td>
    </tr>
    <tr class="mavlink_field" id="FIRMWARE_VERSION_TYPE_RC">
     <td class="mavlink_type" valign="top">192</td>
     <td class="mavlink_name" valign="top">FIRMWARE_VERSION_TYPE_RC</td>
     <td class="mavlink_comment">release candidate</td>
    </tr>
    <tr class="mavlink_field" id="FIRMWARE_VERSION_TYPE_OFFICIAL">
     <td class="mavlink_type" valign="top">255</td>
     <td class="mavlink_name" valign="top">FIRMWARE_VERSION_TYPE_OFFICIAL</td>
     <td class="mavlink_comment">official stable release</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_MODE_FLAG" name="ENUM_MAV_MODE_FLAG">MAV_MODE_FLAG</h2>
  <p class="description">These flags encode the MAV mode.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_SAFETY_ARMED">
     <td class="mavlink_type" valign="top">128</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_SAFETY_ARMED</td>
     <td class="mavlink_comment">0b10000000 MAV safety set to armed. Motors are enabled / running / can start. Ready to fly. Additional note: this flag is to be ignore when sent in the command MAV_CMD_DO_SET_MODE and MAV_CMD_COMPONENT_ARM_DISARM shall be used instead. The flag can still be used to report the armed state.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_MANUAL_INPUT_ENABLED">
     <td class="mavlink_type" valign="top">64</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_MANUAL_INPUT_ENABLED</td>
     <td class="mavlink_comment">0b01000000 remote control input is enabled.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_HIL_ENABLED">
     <td class="mavlink_type" valign="top">32</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_HIL_ENABLED</td>
     <td class="mavlink_comment">0b00100000 hardware in the loop simulation. All motors / actuators are blocked, but internal software is full operational.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_STABILIZE_ENABLED">
     <td class="mavlink_type" valign="top">16</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_STABILIZE_ENABLED</td>
     <td class="mavlink_comment">0b00010000 system stabilizes electronically its attitude (and optionally position). It needs however further control inputs to move around.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_GUIDED_ENABLED">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_GUIDED_ENABLED</td>
     <td class="mavlink_comment">0b00001000 guided mode enabled, system flies waypoints / mission items.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_AUTO_ENABLED">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_AUTO_ENABLED</td>
     <td class="mavlink_comment">0b00000100 autonomous mode enabled, system finds its own goal positions. Guided flag can be set or not, depends on the actual implementation.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_TEST_ENABLED">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_TEST_ENABLED</td>
     <td class="mavlink_comment">0b00000010 system has a test mode enabled. This flag is intended for temporary system tests and should not be used for stable implementations.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_CUSTOM_MODE_ENABLED">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_CUSTOM_MODE_ENABLED</td>
     <td class="mavlink_comment">0b00000001 Reserved for future use.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_MODE_FLAG_DECODE_POSITION" name="ENUM_MAV_MODE_FLAG_DECODE_POSITION">MAV_MODE_FLAG_DECODE_POSITION</h2>
  <p class="description">These values encode the bit positions of the decode position. These values can be used to read the value of a flag bit by combining the base_mode variable with AND with the flag position value. The result will be either 0 or 1, depending on if the flag is set or not.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_DECODE_POSITION_SAFETY">
     <td class="mavlink_type" valign="top">128</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_DECODE_POSITION_SAFETY</td>
     <td class="mavlink_comment">First bit:  10000000</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_DECODE_POSITION_MANUAL">
     <td class="mavlink_type" valign="top">64</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_DECODE_POSITION_MANUAL</td>
     <td class="mavlink_comment">Second bit: 01000000</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_DECODE_POSITION_HIL">
     <td class="mavlink_type" valign="top">32</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_DECODE_POSITION_HIL</td>
     <td class="mavlink_comment">Third bit:  00100000</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_DECODE_POSITION_STABILIZE">
     <td class="mavlink_type" valign="top">16</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_DECODE_POSITION_STABILIZE</td>
     <td class="mavlink_comment">Fourth bit: 00010000</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_DECODE_POSITION_GUIDED">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_DECODE_POSITION_GUIDED</td>
     <td class="mavlink_comment">Fifth bit:  00001000</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_DECODE_POSITION_AUTO">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_DECODE_POSITION_AUTO</td>
     <td class="mavlink_comment">Sixt bit:   00000100</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_DECODE_POSITION_TEST">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_DECODE_POSITION_TEST</td>
     <td class="mavlink_comment">Seventh bit: 00000010</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_DECODE_POSITION_CUSTOM_MODE">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_DECODE_POSITION_CUSTOM_MODE</td>
     <td class="mavlink_comment">Eighth bit: 00000001</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_GOTO" name="ENUM_MAV_GOTO">MAV_GOTO</h2>
  <p class="description">Override command, pauses current mission execution and moves immediately to a position</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_GOTO_DO_HOLD">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_GOTO_DO_HOLD</td>
     <td class="mavlink_comment">Hold at the current position.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_GOTO_DO_CONTINUE">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_GOTO_DO_CONTINUE</td>
     <td class="mavlink_comment">Continue with the next item in mission execution.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_GOTO_HOLD_AT_CURRENT_POSITION">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_GOTO_HOLD_AT_CURRENT_POSITION</td>
     <td class="mavlink_comment">Hold at the current position of the system</td>
    </tr>
    <tr class="mavlink_field" id="MAV_GOTO_HOLD_AT_SPECIFIED_POSITION">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_GOTO_HOLD_AT_SPECIFIED_POSITION</td>
     <td class="mavlink_comment">Hold at the position specified in the parameters of the DO_HOLD action</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_MODE" name="ENUM_MAV_MODE">MAV_MODE</h2>
  <p class="description">These defines are predefined OR-combined mode flags. There is no need to use values from this enum, but it
               simplifies the use of the mode flags. Note that manual input is enabled in all modes as a safety override.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_MODE_PREFLIGHT">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_MODE_PREFLIGHT</td>
     <td class="mavlink_comment">System is not ready to fly, booting, calibrating, etc. No flag is set.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_STABILIZE_DISARMED">
     <td class="mavlink_type" valign="top">80</td>
     <td class="mavlink_name" valign="top">MAV_MODE_STABILIZE_DISARMED</td>
     <td class="mavlink_comment">System is allowed to be active, under assisted RC control.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_STABILIZE_ARMED">
     <td class="mavlink_type" valign="top">208</td>
     <td class="mavlink_name" valign="top">MAV_MODE_STABILIZE_ARMED</td>
     <td class="mavlink_comment">System is allowed to be active, under assisted RC control.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_MANUAL_DISARMED">
     <td class="mavlink_type" valign="top">64</td>
     <td class="mavlink_name" valign="top">MAV_MODE_MANUAL_DISARMED</td>
     <td class="mavlink_comment">System is allowed to be active, under manual (RC) control, no stabilization</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_MANUAL_ARMED">
     <td class="mavlink_type" valign="top">192</td>
     <td class="mavlink_name" valign="top">MAV_MODE_MANUAL_ARMED</td>
     <td class="mavlink_comment">System is allowed to be active, under manual (RC) control, no stabilization</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_GUIDED_DISARMED">
     <td class="mavlink_type" valign="top">88</td>
     <td class="mavlink_name" valign="top">MAV_MODE_GUIDED_DISARMED</td>
     <td class="mavlink_comment">System is allowed to be active, under autonomous control, manual setpoint</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_GUIDED_ARMED">
     <td class="mavlink_type" valign="top">216</td>
     <td class="mavlink_name" valign="top">MAV_MODE_GUIDED_ARMED</td>
     <td class="mavlink_comment">System is allowed to be active, under autonomous control, manual setpoint</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_AUTO_DISARMED">
     <td class="mavlink_type" valign="top">92</td>
     <td class="mavlink_name" valign="top">MAV_MODE_AUTO_DISARMED</td>
     <td class="mavlink_comment">System is allowed to be active, under autonomous control and navigation (the trajectory is decided onboard and not pre-programmed by waypoints)</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_AUTO_ARMED">
     <td class="mavlink_type" valign="top">220</td>
     <td class="mavlink_name" valign="top">MAV_MODE_AUTO_ARMED</td>
     <td class="mavlink_comment">System is allowed to be active, under autonomous control and navigation (the trajectory is decided onboard and not pre-programmed by waypoints)</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_TEST_DISARMED">
     <td class="mavlink_type" valign="top">66</td>
     <td class="mavlink_name" valign="top">MAV_MODE_TEST_DISARMED</td>
     <td class="mavlink_comment">UNDEFINED mode. This solely depends on the autopilot - use with caution, intended for developers only.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_TEST_ARMED">
     <td class="mavlink_type" valign="top">194</td>
     <td class="mavlink_name" valign="top">MAV_MODE_TEST_ARMED</td>
     <td class="mavlink_comment">UNDEFINED mode. This solely depends on the autopilot - use with caution, intended for developers only.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_STATE" name="ENUM_MAV_STATE">MAV_STATE</h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_STATE_UNINIT">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_STATE_UNINIT</td>
     <td class="mavlink_comment">Uninitialized system, state is unknown.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_STATE_BOOT">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_STATE_BOOT</td>
     <td class="mavlink_comment">System is booting up.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_STATE_CALIBRATING">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_STATE_CALIBRATING</td>
     <td class="mavlink_comment">System is calibrating and not flight-ready.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_STATE_STANDBY">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_STATE_STANDBY</td>
     <td class="mavlink_comment">System is grounded and on standby. It can be launched any time.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_STATE_ACTIVE">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_STATE_ACTIVE</td>
     <td class="mavlink_comment">System is active and might be already airborne. Motors are engaged.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_STATE_CRITICAL">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_STATE_CRITICAL</td>
     <td class="mavlink_comment">System is in a non-normal flight mode. It can however still navigate.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_STATE_EMERGENCY">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_STATE_EMERGENCY</td>
     <td class="mavlink_comment">System is in a non-normal flight mode. It lost control over parts or over the whole airframe. It is in mayday and going down.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_STATE_POWEROFF">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_STATE_POWEROFF</td>
     <td class="mavlink_comment">System just initialized its power-down sequence, will shut down now.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_STATE_FLIGHT_TERMINATION">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_STATE_FLIGHT_TERMINATION</td>
     <td class="mavlink_comment">System is terminating itself.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_COMPONENT" name="ENUM_MAV_COMPONENT">MAV_COMPONENT</h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_COMP_ID_ALL">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_ALL</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_AUTOPILOT1">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_AUTOPILOT1</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_CAMERA">
     <td class="mavlink_type" valign="top">100</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_CAMERA</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_CAMERA2">
     <td class="mavlink_type" valign="top">101</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_CAMERA2</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_CAMERA3">
     <td class="mavlink_type" valign="top">102</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_CAMERA3</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_CAMERA4">
     <td class="mavlink_type" valign="top">103</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_CAMERA4</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_CAMERA5">
     <td class="mavlink_type" valign="top">104</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_CAMERA5</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_CAMERA6">
     <td class="mavlink_type" valign="top">105</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_CAMERA6</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_SERVO1">
     <td class="mavlink_type" valign="top">140</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_SERVO1</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_SERVO2">
     <td class="mavlink_type" valign="top">141</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_SERVO2</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_SERVO3">
     <td class="mavlink_type" valign="top">142</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_SERVO3</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_SERVO4">
     <td class="mavlink_type" valign="top">143</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_SERVO4</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_SERVO5">
     <td class="mavlink_type" valign="top">144</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_SERVO5</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_SERVO6">
     <td class="mavlink_type" valign="top">145</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_SERVO6</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_SERVO7">
     <td class="mavlink_type" valign="top">146</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_SERVO7</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_SERVO8">
     <td class="mavlink_type" valign="top">147</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_SERVO8</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_SERVO9">
     <td class="mavlink_type" valign="top">148</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_SERVO9</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_SERVO10">
     <td class="mavlink_type" valign="top">149</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_SERVO10</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_SERVO11">
     <td class="mavlink_type" valign="top">150</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_SERVO11</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_SERVO12">
     <td class="mavlink_type" valign="top">151</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_SERVO12</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_SERVO13">
     <td class="mavlink_type" valign="top">152</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_SERVO13</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_SERVO14">
     <td class="mavlink_type" valign="top">153</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_SERVO14</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_GIMBAL">
     <td class="mavlink_type" valign="top">154</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_GIMBAL</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_LOG">
     <td class="mavlink_type" valign="top">155</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_LOG</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_ADSB">
     <td class="mavlink_type" valign="top">156</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_ADSB</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_OSD">
     <td class="mavlink_type" valign="top">157</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_OSD</td>
     <td class="mavlink_comment">On Screen Display (OSD) devices for video links</td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_PERIPHERAL">
     <td class="mavlink_type" valign="top">158</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_PERIPHERAL</td>
     <td class="mavlink_comment">Generic autopilot peripheral component ID. Meant for devices that do not implement the parameter sub-protocol</td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_QX1_GIMBAL">
     <td class="mavlink_type" valign="top">159</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_QX1_GIMBAL</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_MAPPER">
     <td class="mavlink_type" valign="top">180</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_MAPPER</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_MISSIONPLANNER">
     <td class="mavlink_type" valign="top">190</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_MISSIONPLANNER</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_PATHPLANNER">
     <td class="mavlink_type" valign="top">195</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_PATHPLANNER</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_IMU">
     <td class="mavlink_type" valign="top">200</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_IMU</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_IMU_2">
     <td class="mavlink_type" valign="top">201</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_IMU_2</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_IMU_3">
     <td class="mavlink_type" valign="top">202</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_IMU_3</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_GPS">
     <td class="mavlink_type" valign="top">220</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_GPS</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_GPS2">
     <td class="mavlink_type" valign="top">221</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_GPS2</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_UDP_BRIDGE">
     <td class="mavlink_type" valign="top">240</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_UDP_BRIDGE</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_UART_BRIDGE">
     <td class="mavlink_type" valign="top">241</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_UART_BRIDGE</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_COMP_ID_SYSTEM_CONTROL">
     <td class="mavlink_type" valign="top">250</td>
     <td class="mavlink_name" valign="top">MAV_COMP_ID_SYSTEM_CONTROL</td>
     <td class="mavlink_comment">
     </td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_SYS_STATUS_SENSOR" name="ENUM_MAV_SYS_STATUS_SENSOR">MAV_SYS_STATUS_SENSOR</h2>
  <p class="description">These encode the sensors whose status is sent as part of the SYS_STATUS message.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_3D_GYRO">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_3D_GYRO</td>
     <td class="mavlink_comment">0x01 3D gyro</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_3D_ACCEL">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_3D_ACCEL</td>
     <td class="mavlink_comment">0x02 3D accelerometer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_3D_MAG">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_3D_MAG</td>
     <td class="mavlink_comment">0x04 3D magnetometer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_ABSOLUTE_PRESSURE">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_ABSOLUTE_PRESSURE</td>
     <td class="mavlink_comment">0x08 absolute pressure</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_DIFFERENTIAL_PRESSURE">
     <td class="mavlink_type" valign="top">16</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_DIFFERENTIAL_PRESSURE</td>
     <td class="mavlink_comment">0x10 differential pressure</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_GPS">
     <td class="mavlink_type" valign="top">32</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_GPS</td>
     <td class="mavlink_comment">0x20 GPS</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_OPTICAL_FLOW">
     <td class="mavlink_type" valign="top">64</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_OPTICAL_FLOW</td>
     <td class="mavlink_comment">0x40 optical flow</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_VISION_POSITION">
     <td class="mavlink_type" valign="top">128</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_VISION_POSITION</td>
     <td class="mavlink_comment">0x80 computer vision position</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_LASER_POSITION">
     <td class="mavlink_type" valign="top">256</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_LASER_POSITION</td>
     <td class="mavlink_comment">0x100 laser based position</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_EXTERNAL_GROUND_TRUTH">
     <td class="mavlink_type" valign="top">512</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_EXTERNAL_GROUND_TRUTH</td>
     <td class="mavlink_comment">0x200 external ground truth (Vicon or Leica)</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_ANGULAR_RATE_CONTROL">
     <td class="mavlink_type" valign="top">1024</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_ANGULAR_RATE_CONTROL</td>
     <td class="mavlink_comment">0x400 3D angular rate control</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_ATTITUDE_STABILIZATION">
     <td class="mavlink_type" valign="top">2048</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_ATTITUDE_STABILIZATION</td>
     <td class="mavlink_comment">0x800 attitude stabilization</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_YAW_POSITION">
     <td class="mavlink_type" valign="top">4096</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_YAW_POSITION</td>
     <td class="mavlink_comment">0x1000 yaw position</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_Z_ALTITUDE_CONTROL">
     <td class="mavlink_type" valign="top">8192</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_Z_ALTITUDE_CONTROL</td>
     <td class="mavlink_comment">0x2000 z/altitude control</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_XY_POSITION_CONTROL">
     <td class="mavlink_type" valign="top">16384</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_XY_POSITION_CONTROL</td>
     <td class="mavlink_comment">0x4000 x/y position control</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_MOTOR_OUTPUTS">
     <td class="mavlink_type" valign="top">32768</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_MOTOR_OUTPUTS</td>
     <td class="mavlink_comment">0x8000 motor outputs / control</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_RC_RECEIVER">
     <td class="mavlink_type" valign="top">65536</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_RC_RECEIVER</td>
     <td class="mavlink_comment">0x10000 rc receiver</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_3D_GYRO2">
     <td class="mavlink_type" valign="top">131072</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_3D_GYRO2</td>
     <td class="mavlink_comment">0x20000 2nd 3D gyro</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_3D_ACCEL2">
     <td class="mavlink_type" valign="top">262144</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_3D_ACCEL2</td>
     <td class="mavlink_comment">0x40000 2nd 3D accelerometer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_3D_MAG2">
     <td class="mavlink_type" valign="top">524288</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_3D_MAG2</td>
     <td class="mavlink_comment">0x80000 2nd 3D magnetometer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_GEOFENCE">
     <td class="mavlink_type" valign="top">1048576</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_GEOFENCE</td>
     <td class="mavlink_comment">0x100000 geofence</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_AHRS">
     <td class="mavlink_type" valign="top">2097152</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_AHRS</td>
     <td class="mavlink_comment">0x200000 AHRS subsystem health</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_TERRAIN">
     <td class="mavlink_type" valign="top">4194304</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_TERRAIN</td>
     <td class="mavlink_comment">0x400000 Terrain subsystem health</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_REVERSE_MOTOR">
     <td class="mavlink_type" valign="top">8388608</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_REVERSE_MOTOR</td>
     <td class="mavlink_comment">0x800000 Motors are reversed</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_LOGGING">
     <td class="mavlink_type" valign="top">16777216</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_LOGGING</td>
     <td class="mavlink_comment">0x1000000 Logging</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SYS_STATUS_SENSOR_BATTERY">
     <td class="mavlink_type" valign="top">33554432</td>
     <td class="mavlink_name" valign="top">MAV_SYS_STATUS_SENSOR_BATTERY</td>
     <td class="mavlink_comment">0x2000000 Battery</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_FRAME" name="ENUM_MAV_FRAME">MAV_FRAME</h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_FRAME_GLOBAL">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_FRAME_GLOBAL</td>
     <td class="mavlink_comment">Global coordinate frame, WGS84 coordinate system. First value / x: latitude, second value / y: longitude, third value / z: positive altitude over mean sea level (MSL)</td>
    </tr>
    <tr class="mavlink_field" id="MAV_FRAME_LOCAL_NED">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_FRAME_LOCAL_NED</td>
     <td class="mavlink_comment">Local coordinate frame, Z-up (x: north, y: east, z: down).</td>
    </tr>
    <tr class="mavlink_field" id="MAV_FRAME_MISSION">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_FRAME_MISSION</td>
     <td class="mavlink_comment">NOT a coordinate frame, indicates a mission command.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_FRAME_GLOBAL_RELATIVE_ALT">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_FRAME_GLOBAL_RELATIVE_ALT</td>
     <td class="mavlink_comment">Global coordinate frame, WGS84 coordinate system, relative altitude over ground with respect to the home position. First value / x: latitude, second value / y: longitude, third value / z: positive altitude with 0 being at the altitude of the home location.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_FRAME_LOCAL_ENU">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_FRAME_LOCAL_ENU</td>
     <td class="mavlink_comment">Local coordinate frame, Z-down (x: east, y: north, z: up)</td>
    </tr>
    <tr class="mavlink_field" id="MAV_FRAME_GLOBAL_INT">
     <td class="mavlink_type" valign="top">5</td>
     <td class="mavlink_name" valign="top">MAV_FRAME_GLOBAL_INT</td>
     <td class="mavlink_comment">Global coordinate frame, WGS84 coordinate system. First value / x: latitude in degrees*1.0e-7, second value / y: longitude in degrees*1.0e-7, third value / z: positive altitude over mean sea level (MSL)</td>
    </tr>
    <tr class="mavlink_field" id="MAV_FRAME_GLOBAL_RELATIVE_ALT_INT">
     <td class="mavlink_type" valign="top">6</td>
     <td class="mavlink_name" valign="top">MAV_FRAME_GLOBAL_RELATIVE_ALT_INT</td>
     <td class="mavlink_comment">Global coordinate frame, WGS84 coordinate system, relative altitude over ground with respect to the home position. First value / x: latitude in degrees*10e-7, second value / y: longitude in degrees*10e-7, third value / z: positive altitude with 0 being at the altitude of the home location.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_FRAME_LOCAL_OFFSET_NED">
     <td class="mavlink_type" valign="top">7</td>
     <td class="mavlink_name" valign="top">MAV_FRAME_LOCAL_OFFSET_NED</td>
     <td class="mavlink_comment">Offset to the current local frame. Anything expressed in this frame should be added to the current local frame position.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_FRAME_BODY_NED">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">MAV_FRAME_BODY_NED</td>
     <td class="mavlink_comment">Setpoint in body NED frame. This makes sense if all position control is externalized - e.g. useful to command 2 m/s^2 acceleration to the right.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_FRAME_BODY_OFFSET_NED">
     <td class="mavlink_type" valign="top">9</td>
     <td class="mavlink_name" valign="top">MAV_FRAME_BODY_OFFSET_NED</td>
     <td class="mavlink_comment">Offset in body NED frame. This makes sense if adding setpoints to the current flight path, to avoid an obstacle - e.g. useful to command 2 m/s^2 acceleration to the east.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_FRAME_GLOBAL_TERRAIN_ALT">
     <td class="mavlink_type" valign="top">10</td>
     <td class="mavlink_name" valign="top">MAV_FRAME_GLOBAL_TERRAIN_ALT</td>
     <td class="mavlink_comment">Global coordinate frame with above terrain level altitude. WGS84 coordinate system, relative altitude over terrain with respect to the waypoint coordinate. First value / x: latitude in degrees, second value / y: longitude in degrees, third value / z: positive altitude in meters with 0 being at ground level in terrain model.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_FRAME_GLOBAL_TERRAIN_ALT_INT">
     <td class="mavlink_type" valign="top">11</td>
     <td class="mavlink_name" valign="top">MAV_FRAME_GLOBAL_TERRAIN_ALT_INT</td>
     <td class="mavlink_comment">Global coordinate frame with above terrain level altitude. WGS84 coordinate system, relative altitude over terrain with respect to the waypoint coordinate. First value / x: latitude in degrees*10e-7, second value / y: longitude in degrees*10e-7, third value / z: positive altitude in meters with 0 being at ground level in terrain model.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAVLINK_DATA_STREAM_TYPE" name="ENUM_MAVLINK_DATA_STREAM_TYPE">MAVLINK_DATA_STREAM_TYPE</h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAVLINK_DATA_STREAM_IMG_JPEG">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAVLINK_DATA_STREAM_IMG_JPEG</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAVLINK_DATA_STREAM_IMG_BMP">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAVLINK_DATA_STREAM_IMG_BMP</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAVLINK_DATA_STREAM_IMG_RAW8U">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAVLINK_DATA_STREAM_IMG_RAW8U</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAVLINK_DATA_STREAM_IMG_RAW32U">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAVLINK_DATA_STREAM_IMG_RAW32U</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAVLINK_DATA_STREAM_IMG_PGM">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAVLINK_DATA_STREAM_IMG_PGM</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAVLINK_DATA_STREAM_IMG_PNG">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAVLINK_DATA_STREAM_IMG_PNG</td>
     <td class="mavlink_comment">
     </td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="FENCE_ACTION" name="ENUM_FENCE_ACTION">FENCE_ACTION</h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="FENCE_ACTION_NONE">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">FENCE_ACTION_NONE</td>
     <td class="mavlink_comment">Disable fenced mode</td>
    </tr>
    <tr class="mavlink_field" id="FENCE_ACTION_GUIDED">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">FENCE_ACTION_GUIDED</td>
     <td class="mavlink_comment">Switched to guided mode to return point (fence point 0)</td>
    </tr>
    <tr class="mavlink_field" id="FENCE_ACTION_REPORT">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">FENCE_ACTION_REPORT</td>
     <td class="mavlink_comment">Report fence breach, but don't take action</td>
    </tr>
    <tr class="mavlink_field" id="FENCE_ACTION_GUIDED_THR_PASS">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">FENCE_ACTION_GUIDED_THR_PASS</td>
     <td class="mavlink_comment">Switched to guided mode to return point (fence point 0) with manual throttle control</td>
    </tr>
    <tr class="mavlink_field" id="FENCE_ACTION_RTL">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">FENCE_ACTION_RTL</td>
     <td class="mavlink_comment">Switch to RTL (return to launch) mode and head for the return point.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="FENCE_BREACH" name="ENUM_FENCE_BREACH">FENCE_BREACH</h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="FENCE_BREACH_NONE">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">FENCE_BREACH_NONE</td>
     <td class="mavlink_comment">No last fence breach</td>
    </tr>
    <tr class="mavlink_field" id="FENCE_BREACH_MINALT">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">FENCE_BREACH_MINALT</td>
     <td class="mavlink_comment">Breached minimum altitude</td>
    </tr>
    <tr class="mavlink_field" id="FENCE_BREACH_MAXALT">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">FENCE_BREACH_MAXALT</td>
     <td class="mavlink_comment">Breached maximum altitude</td>
    </tr>
    <tr class="mavlink_field" id="FENCE_BREACH_BOUNDARY">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">FENCE_BREACH_BOUNDARY</td>
     <td class="mavlink_comment">Breached fence boundary</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_MOUNT_MODE" name="ENUM_MAV_MOUNT_MODE">MAV_MOUNT_MODE</h2>
  <p class="description">Enumeration of possible mount operation modes</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_MOUNT_MODE_RETRACT">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_MOUNT_MODE_RETRACT</td>
     <td class="mavlink_comment">Load and keep safe position (Roll,Pitch,Yaw) from permant memory and stop stabilization</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MOUNT_MODE_NEUTRAL">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_MOUNT_MODE_NEUTRAL</td>
     <td class="mavlink_comment">Load and keep neutral position (Roll,Pitch,Yaw) from permanent memory.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MOUNT_MODE_MAVLINK_TARGETING">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_MOUNT_MODE_MAVLINK_TARGETING</td>
     <td class="mavlink_comment">Load neutral position and start MAVLink Roll,Pitch,Yaw control with stabilization</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MOUNT_MODE_RC_TARGETING">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_MOUNT_MODE_RC_TARGETING</td>
     <td class="mavlink_comment">Load neutral position and start RC Roll,Pitch,Yaw control with stabilization</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MOUNT_MODE_GPS_POINT">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_MOUNT_MODE_GPS_POINT</td>
     <td class="mavlink_comment">Load neutral position and start to point to Lat,Lon,Alt</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="UAVCAN_NODE_HEALTH" name="ENUM_UAVCAN_NODE_HEALTH">UAVCAN_NODE_HEALTH</h2>
  <p class="description">Generalized UAVCAN node health</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="UAVCAN_NODE_HEALTH_OK">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">UAVCAN_NODE_HEALTH_OK</td>
     <td class="mavlink_comment">The node is functioning properly.</td>
    </tr>
    <tr class="mavlink_field" id="UAVCAN_NODE_HEALTH_WARNING">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">UAVCAN_NODE_HEALTH_WARNING</td>
     <td class="mavlink_comment">A critical parameter went out of range or the node has encountered a minor failure.</td>
    </tr>
    <tr class="mavlink_field" id="UAVCAN_NODE_HEALTH_ERROR">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">UAVCAN_NODE_HEALTH_ERROR</td>
     <td class="mavlink_comment">The node has encountered a major failure.</td>
    </tr>
    <tr class="mavlink_field" id="UAVCAN_NODE_HEALTH_CRITICAL">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">UAVCAN_NODE_HEALTH_CRITICAL</td>
     <td class="mavlink_comment">The node has suffered a fatal malfunction.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="UAVCAN_NODE_MODE" name="ENUM_UAVCAN_NODE_MODE">UAVCAN_NODE_MODE</h2>
  <p class="description">Generalized UAVCAN node mode</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="UAVCAN_NODE_MODE_OPERATIONAL">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">UAVCAN_NODE_MODE_OPERATIONAL</td>
     <td class="mavlink_comment">The node is performing its primary functions.</td>
    </tr>
    <tr class="mavlink_field" id="UAVCAN_NODE_MODE_INITIALIZATION">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">UAVCAN_NODE_MODE_INITIALIZATION</td>
     <td class="mavlink_comment">The node is initializing; this mode is entered immediately after startup.</td>
    </tr>
    <tr class="mavlink_field" id="UAVCAN_NODE_MODE_MAINTENANCE">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">UAVCAN_NODE_MODE_MAINTENANCE</td>
     <td class="mavlink_comment">The node is under maintenance.</td>
    </tr>
    <tr class="mavlink_field" id="UAVCAN_NODE_MODE_SOFTWARE_UPDATE">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">UAVCAN_NODE_MODE_SOFTWARE_UPDATE</td>
     <td class="mavlink_comment">The node is in the process of updating its software.</td>
    </tr>
    <tr class="mavlink_field" id="UAVCAN_NODE_MODE_OFFLINE">
     <td class="mavlink_type" valign="top">7</td>
     <td class="mavlink_name" valign="top">UAVCAN_NODE_MODE_OFFLINE</td>
     <td class="mavlink_comment">The node is no longer available online.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_CMD" name="ENUM_MAV_CMD">MAV_CMD</h2>
  <p class="description">Commands to be executed by the MAV. They can be executed on user request, or as part of a mission script. If the action is used in a mission, the parameter mapping to the waypoint/mission message is as follows: Param 1, Param 2, Param 3, Param 4, X: Param 5, Y:Param 6, Z:Param 7. This command list is similar what ARINC 424 is for commercial aircraft: A data format how to interpret waypoint/mission data.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_CMD_NAV_WAYPOINT">
     <td class="mavlink_type" valign="top">16</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_WAYPOINT</td>
     <td class="mavlink_comment">Navigate to waypoint.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_LOITER_UNLIM">
     <td class="mavlink_type" valign="top">17</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_LOITER_UNLIM</td>
     <td class="mavlink_comment">Loiter around this waypoint an unlimited amount of time</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_LOITER_TURNS">
     <td class="mavlink_type" valign="top">18</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_LOITER_TURNS</td>
     <td class="mavlink_comment">Loiter around this waypoint for X turns</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_LOITER_TIME">
     <td class="mavlink_type" valign="top">19</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_LOITER_TIME</td>
     <td class="mavlink_comment">Loiter around this waypoint for X seconds</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_RETURN_TO_LAUNCH">
     <td class="mavlink_type" valign="top">20</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_RETURN_TO_LAUNCH</td>
     <td class="mavlink_comment">Return to launch location</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_LAND">
     <td class="mavlink_type" valign="top">21</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_LAND</td>
     <td class="mavlink_comment">Land at location</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_TAKEOFF">
     <td class="mavlink_type" valign="top">22</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_TAKEOFF</td>
     <td class="mavlink_comment">Takeoff from ground / hand</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_LAND_LOCAL">
     <td class="mavlink_type" valign="top">23</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_LAND_LOCAL</td>
     <td class="mavlink_comment">Land at local position (local frame only)</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_TAKEOFF_LOCAL">
     <td class="mavlink_type" valign="top">24</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_TAKEOFF_LOCAL</td>
     <td class="mavlink_comment">Takeoff from local position (local frame only)</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_FOLLOW">
     <td class="mavlink_type" valign="top">25</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_FOLLOW</td>
     <td class="mavlink_comment">Vehicle following, i.e. this waypoint represents the position of a moving vehicle</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_CONTINUE_AND_CHANGE_ALT">
     <td class="mavlink_type" valign="top">30</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_CONTINUE_AND_CHANGE_ALT</td>
     <td class="mavlink_comment">Continue on the current course and climb/descend to specified altitude.  When the altitude is reached continue to the next command (i.e., don't proceed to the next command until the desired altitude is reached.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_LOITER_TO_ALT">
     <td class="mavlink_type" valign="top">31</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_LOITER_TO_ALT</td>
     <td class="mavlink_comment">Begin loiter at the specified Latitude and Longitude.  If Lat=Lon=0, then loiter at the current position.  Don't consider the navigation command complete (don't leave loiter) until the altitude has been reached.  Additionally, if the Heading Required parameter is non-zero the  aircraft will not leave the loiter until heading toward the next waypoint.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_FOLLOW">
     <td class="mavlink_type" valign="top">32</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_FOLLOW</td>
     <td class="mavlink_comment">Being following a target</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_FOLLOW_REPOSITION">
     <td class="mavlink_type" valign="top">33</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_FOLLOW_REPOSITION</td>
     <td class="mavlink_comment">Reposition the MAV after a follow target command has been sent</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_ROI">
     <td class="mavlink_type" valign="top">80</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_ROI</td>
     <td class="mavlink_comment">Sets the region of interest (ROI) for a sensor set or the vehicle itself. This can then be used by the vehicles control system to control the vehicle attitude and the attitude of various sensors such as cameras.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_PATHPLANNING">
     <td class="mavlink_type" valign="top">81</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_PATHPLANNING</td>
     <td class="mavlink_comment">Control autonomous path planning on the MAV.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_SPLINE_WAYPOINT">
     <td class="mavlink_type" valign="top">82</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_SPLINE_WAYPOINT</td>
     <td class="mavlink_comment">Navigate to waypoint using a spline path.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_VTOL_TAKEOFF">
     <td class="mavlink_type" valign="top">84</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_VTOL_TAKEOFF</td>
     <td class="mavlink_comment">Takeoff from ground using VTOL mode</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_VTOL_LAND">
     <td class="mavlink_type" valign="top">85</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_VTOL_LAND</td>
     <td class="mavlink_comment">Land using VTOL mode</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_GUIDED_ENABLE">
     <td class="mavlink_type" valign="top">92</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_GUIDED_ENABLE</td>
     <td class="mavlink_comment">hand control over to an external controller</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_DELAY">
     <td class="mavlink_type" valign="top">93</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_DELAY</td>
     <td class="mavlink_comment">Delay the next navigation command a number of seconds or until a specified time</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_PAYLOAD_PLACE">
     <td class="mavlink_type" valign="top">94</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_PAYLOAD_PLACE</td>
     <td class="mavlink_comment">Descend and place payload.  Vehicle descends until it detects a hanging payload has reached the ground, the gripper is opened to release the payload</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_LAST">
     <td class="mavlink_type" valign="top">95</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_LAST</td>
     <td class="mavlink_comment">NOP - This command is only used to mark the upper limit of the NAV/ACTION commands in the enumeration</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_CONDITION_DELAY">
     <td class="mavlink_type" valign="top">112</td>
     <td class="mavlink_name" valign="top">MAV_CMD_CONDITION_DELAY</td>
     <td class="mavlink_comment">Delay mission state machine.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_CONDITION_CHANGE_ALT">
     <td class="mavlink_type" valign="top">113</td>
     <td class="mavlink_name" valign="top">MAV_CMD_CONDITION_CHANGE_ALT</td>
     <td class="mavlink_comment">Ascend/descend at rate.  Delay mission state machine until desired altitude reached.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_CONDITION_DISTANCE">
     <td class="mavlink_type" valign="top">114</td>
     <td class="mavlink_name" valign="top">MAV_CMD_CONDITION_DISTANCE</td>
     <td class="mavlink_comment">Delay mission state machine until within desired distance of next NAV point.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_CONDITION_YAW">
     <td class="mavlink_type" valign="top">115</td>
     <td class="mavlink_name" valign="top">MAV_CMD_CONDITION_YAW</td>
     <td class="mavlink_comment">Reach a certain target angle.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_CONDITION_LAST">
     <td class="mavlink_type" valign="top">159</td>
     <td class="mavlink_name" valign="top">MAV_CMD_CONDITION_LAST</td>
     <td class="mavlink_comment">NOP - This command is only used to mark the upper limit of the CONDITION commands in the enumeration</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_SET_MODE">
     <td class="mavlink_type" valign="top">176</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_SET_MODE</td>
     <td class="mavlink_comment">Set system mode.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_JUMP">
     <td class="mavlink_type" valign="top">177</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_JUMP</td>
     <td class="mavlink_comment">Jump to the desired command in the mission list.  Repeat this action only the specified number of times</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_CHANGE_SPEED">
     <td class="mavlink_type" valign="top">178</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_CHANGE_SPEED</td>
     <td class="mavlink_comment">Change speed and/or throttle set points.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_SET_HOME">
     <td class="mavlink_type" valign="top">179</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_SET_HOME</td>
     <td class="mavlink_comment">Changes the home location either to the current location or a specified location.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_SET_PARAMETER">
     <td class="mavlink_type" valign="top">180</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_SET_PARAMETER</td>
     <td class="mavlink_comment">Set a system parameter.  Caution!  Use of this command requires knowledge of the numeric enumeration value of the parameter.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_SET_RELAY">
     <td class="mavlink_type" valign="top">181</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_SET_RELAY</td>
     <td class="mavlink_comment">Set a relay to a condition.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_REPEAT_RELAY">
     <td class="mavlink_type" valign="top">182</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_REPEAT_RELAY</td>
     <td class="mavlink_comment">Cycle a relay on and off for a desired number of cyles with a desired period.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_SET_SERVO">
     <td class="mavlink_type" valign="top">183</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_SET_SERVO</td>
     <td class="mavlink_comment">Set a servo to a desired PWM value.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_REPEAT_SERVO">
     <td class="mavlink_type" valign="top">184</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_REPEAT_SERVO</td>
     <td class="mavlink_comment">Cycle a between its nominal setting and a desired PWM for a desired number of cycles with a desired period.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_FLIGHTTERMINATION">
     <td class="mavlink_type" valign="top">185</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_FLIGHTTERMINATION</td>
     <td class="mavlink_comment">Terminate flight immediately</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_CHANGE_ALTITUDE">
     <td class="mavlink_type" valign="top">186</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_CHANGE_ALTITUDE</td>
     <td class="mavlink_comment">Change altitude set point.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_LAND_START">
     <td class="mavlink_type" valign="top">189</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_LAND_START</td>
     <td class="mavlink_comment">Mission command to perform a landing. This is used as a marker in a mission to tell the autopilot where a sequence of mission items that represents a landing starts. It may also be sent via a COMMAND_LONG to trigger a landing, in which case the nearest (geographically) landing sequence in the mission will be used. The Latitude/Longitude is optional, and may be set to 0 if not needed. If specified then it will be used to help find the closest landing sequence.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_RALLY_LAND">
     <td class="mavlink_type" valign="top">190</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_RALLY_LAND</td>
     <td class="mavlink_comment">Mission command to perform a landing from a rally point.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_GO_AROUND">
     <td class="mavlink_type" valign="top">191</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_GO_AROUND</td>
     <td class="mavlink_comment">Mission command to safely abort an autonmous landing.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_REPOSITION">
     <td class="mavlink_type" valign="top">192</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_REPOSITION</td>
     <td class="mavlink_comment">Reposition the vehicle to a specific WGS84 global position.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_PAUSE_CONTINUE">
     <td class="mavlink_type" valign="top">193</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_PAUSE_CONTINUE</td>
     <td class="mavlink_comment">If in a GPS controlled position mode, hold the current position or continue.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_SET_REVERSE">
     <td class="mavlink_type" valign="top">194</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_SET_REVERSE</td>
     <td class="mavlink_comment">Set moving direction to forward or reverse.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_CONTROL_VIDEO">
     <td class="mavlink_type" valign="top">200</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_CONTROL_VIDEO</td>
     <td class="mavlink_comment">Control onboard camera system.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_SET_ROI">
     <td class="mavlink_type" valign="top">201</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_SET_ROI</td>
     <td class="mavlink_comment">Sets the region of interest (ROI) for a sensor set or the vehicle itself. This can then be used by the vehicles control system to control the vehicle attitude and the attitude of various sensors such as cameras.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_DIGICAM_CONFIGURE">
     <td class="mavlink_type" valign="top">202</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_DIGICAM_CONFIGURE</td>
     <td class="mavlink_comment">Mission command to configure an on-board camera controller system.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_DIGICAM_CONTROL">
     <td class="mavlink_type" valign="top">203</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_DIGICAM_CONTROL</td>
     <td class="mavlink_comment">Mission command to control an on-board camera controller system.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_MOUNT_CONFIGURE">
     <td class="mavlink_type" valign="top">204</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_MOUNT_CONFIGURE</td>
     <td class="mavlink_comment">Mission command to configure a camera or antenna mount</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_MOUNT_CONTROL">
     <td class="mavlink_type" valign="top">205</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_MOUNT_CONTROL</td>
     <td class="mavlink_comment">Mission command to control a camera or antenna mount</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_SET_CAM_TRIGG_DIST">
     <td class="mavlink_type" valign="top">206</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_SET_CAM_TRIGG_DIST</td>
     <td class="mavlink_comment">Mission command to set camera trigger distance for this flight. The camera is trigerred each time this distance is exceeded. This command can also be used to set the shutter integration time for the camera.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_FENCE_ENABLE">
     <td class="mavlink_type" valign="top">207</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_FENCE_ENABLE</td>
     <td class="mavlink_comment">Mission command to enable the geofence</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_PARACHUTE">
     <td class="mavlink_type" valign="top">208</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_PARACHUTE</td>
     <td class="mavlink_comment">Mission command to trigger a parachute</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_MOTOR_TEST">
     <td class="mavlink_type" valign="top">209</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_MOTOR_TEST</td>
     <td class="mavlink_comment">Mission command to perform motor test</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_INVERTED_FLIGHT">
     <td class="mavlink_type" valign="top">210</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_INVERTED_FLIGHT</td>
     <td class="mavlink_comment">Change to/from inverted flight</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_SET_YAW_SPEED">
     <td class="mavlink_type" valign="top">213</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_SET_YAW_SPEED</td>
     <td class="mavlink_comment">Sets a desired vehicle turn angle and speed change</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_SET_CAM_TRIGG_INTERVAL">
     <td class="mavlink_type" valign="top">214</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_SET_CAM_TRIGG_INTERVAL</td>
     <td class="mavlink_comment">Mission command to set camera trigger interval for this flight. If triggering is enabled, the camera is triggered each time this interval expires. This command can also be used to set the shutter integration time for the camera.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_MOUNT_CONTROL_QUAT">
     <td class="mavlink_type" valign="top">220</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_MOUNT_CONTROL_QUAT</td>
     <td class="mavlink_comment">Mission command to control a camera or antenna mount, using a quaternion as reference.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_GUIDED_MASTER">
     <td class="mavlink_type" valign="top">221</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_GUIDED_MASTER</td>
     <td class="mavlink_comment">set id of master controller</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_GUIDED_LIMITS">
     <td class="mavlink_type" valign="top">222</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_GUIDED_LIMITS</td>
     <td class="mavlink_comment">set limits for external control</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_ENGINE_CONTROL">
     <td class="mavlink_type" valign="top">223</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_ENGINE_CONTROL</td>
     <td class="mavlink_comment">Control vehicle engine. This is interpreted by the vehicles engine controller to change the target engine state. It is intended for vehicles with internal combustion engines</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_LAST">
     <td class="mavlink_type" valign="top">240</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_LAST</td>
     <td class="mavlink_comment">NOP - This command is only used to mark the upper limit of the DO commands in the enumeration</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_PREFLIGHT_CALIBRATION">
     <td class="mavlink_type" valign="top">241</td>
     <td class="mavlink_name" valign="top">MAV_CMD_PREFLIGHT_CALIBRATION</td>
     <td class="mavlink_comment">Trigger calibration. This command will be only accepted if in pre-flight mode. Except for Temperature Calibration, only one sensor should be set in a single message and all others should be zero.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_PREFLIGHT_SET_SENSOR_OFFSETS">
     <td class="mavlink_type" valign="top">242</td>
     <td class="mavlink_name" valign="top">MAV_CMD_PREFLIGHT_SET_SENSOR_OFFSETS</td>
     <td class="mavlink_comment">Set sensor offsets. This command will be only accepted if in pre-flight mode.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_PREFLIGHT_UAVCAN">
     <td class="mavlink_type" valign="top">243</td>
     <td class="mavlink_name" valign="top">MAV_CMD_PREFLIGHT_UAVCAN</td>
     <td class="mavlink_comment">Trigger UAVCAN config. This command will be only accepted if in pre-flight mode.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_PREFLIGHT_STORAGE">
     <td class="mavlink_type" valign="top">245</td>
     <td class="mavlink_name" valign="top">MAV_CMD_PREFLIGHT_STORAGE</td>
     <td class="mavlink_comment">Request storage of different parameter values and logs. This command will be only accepted if in pre-flight mode.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_PREFLIGHT_REBOOT_SHUTDOWN">
     <td class="mavlink_type" valign="top">246</td>
     <td class="mavlink_name" valign="top">MAV_CMD_PREFLIGHT_REBOOT_SHUTDOWN</td>
     <td class="mavlink_comment">Request the reboot or shutdown of system components.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_OVERRIDE_GOTO">
     <td class="mavlink_type" valign="top">252</td>
     <td class="mavlink_name" valign="top">MAV_CMD_OVERRIDE_GOTO</td>
     <td class="mavlink_comment">Hold / continue the current action</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_MISSION_START">
     <td class="mavlink_type" valign="top">300</td>
     <td class="mavlink_name" valign="top">MAV_CMD_MISSION_START</td>
     <td class="mavlink_comment">start running a mission</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_COMPONENT_ARM_DISARM">
     <td class="mavlink_type" valign="top">400</td>
     <td class="mavlink_name" valign="top">MAV_CMD_COMPONENT_ARM_DISARM</td>
     <td class="mavlink_comment">Arms / Disarms a component</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_GET_HOME_POSITION">
     <td class="mavlink_type" valign="top">410</td>
     <td class="mavlink_name" valign="top">MAV_CMD_GET_HOME_POSITION</td>
     <td class="mavlink_comment">Request the home position from the vehicle.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_START_RX_PAIR">
     <td class="mavlink_type" valign="top">500</td>
     <td class="mavlink_name" valign="top">MAV_CMD_START_RX_PAIR</td>
     <td class="mavlink_comment">Starts receiver pairing</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_GET_MESSAGE_INTERVAL">
     <td class="mavlink_type" valign="top">510</td>
     <td class="mavlink_name" valign="top">MAV_CMD_GET_MESSAGE_INTERVAL</td>
     <td class="mavlink_comment">Request the interval between messages for a particular MAVLink message ID</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_SET_MESSAGE_INTERVAL">
     <td class="mavlink_type" valign="top">511</td>
     <td class="mavlink_name" valign="top">MAV_CMD_SET_MESSAGE_INTERVAL</td>
     <td class="mavlink_comment">Request the interval between messages for a particular MAVLink message ID. This interface replaces REQUEST_DATA_STREAM</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_REQUEST_PROTOCOL_VERSION">
     <td class="mavlink_type" valign="top">519</td>
     <td class="mavlink_name" valign="top">MAV_CMD_REQUEST_PROTOCOL_VERSION</td>
     <td class="mavlink_comment">Request MAVLink protocol version compatibility</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_REQUEST_AUTOPILOT_CAPABILITIES">
     <td class="mavlink_type" valign="top">520</td>
     <td class="mavlink_name" valign="top">MAV_CMD_REQUEST_AUTOPILOT_CAPABILITIES</td>
     <td class="mavlink_comment">Request autopilot capabilities</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_REQUEST_CAMERA_INFORMATION">
     <td class="mavlink_type" valign="top">521</td>
     <td class="mavlink_name" valign="top">MAV_CMD_REQUEST_CAMERA_INFORMATION</td>
     <td class="mavlink_comment">WIP: Request camera information (CAMERA_INFORMATION).</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_REQUEST_CAMERA_SETTINGS">
     <td class="mavlink_type" valign="top">522</td>
     <td class="mavlink_name" valign="top">MAV_CMD_REQUEST_CAMERA_SETTINGS</td>
     <td class="mavlink_comment">WIP: Request camera settings (CAMERA_SETTINGS).</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_REQUEST_STORAGE_INFORMATION">
     <td class="mavlink_type" valign="top">525</td>
     <td class="mavlink_name" valign="top">MAV_CMD_REQUEST_STORAGE_INFORMATION</td>
     <td class="mavlink_comment">WIP: Request storage information (STORAGE_INFORMATION). Use the command's target_component to target a specific component's storage.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_STORAGE_FORMAT">
     <td class="mavlink_type" valign="top">526</td>
     <td class="mavlink_name" valign="top">MAV_CMD_STORAGE_FORMAT</td>
     <td class="mavlink_comment">WIP: Format a storage medium. Once format is complete, a STORAGE_INFORMATION message is sent. Use the command's target_component to target a specific component's storage.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_REQUEST_CAMERA_CAPTURE_STATUS">
     <td class="mavlink_type" valign="top">527</td>
     <td class="mavlink_name" valign="top">MAV_CMD_REQUEST_CAMERA_CAPTURE_STATUS</td>
     <td class="mavlink_comment">WIP: Request camera capture status (CAMERA_CAPTURE_STATUS)</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_REQUEST_FLIGHT_INFORMATION">
     <td class="mavlink_type" valign="top">528</td>
     <td class="mavlink_name" valign="top">MAV_CMD_REQUEST_FLIGHT_INFORMATION</td>
     <td class="mavlink_comment">WIP: Request flight information (FLIGHT_INFORMATION)</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_RESET_CAMERA_SETTINGS">
     <td class="mavlink_type" valign="top">529</td>
     <td class="mavlink_name" valign="top">MAV_CMD_RESET_CAMERA_SETTINGS</td>
     <td class="mavlink_comment">WIP: Reset all camera settings to Factory Default</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_SET_CAMERA_MODE">
     <td class="mavlink_type" valign="top">530</td>
     <td class="mavlink_name" valign="top">MAV_CMD_SET_CAMERA_MODE</td>
     <td class="mavlink_comment">Set camera running mode. Use NAN for reserved values.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_IMAGE_START_CAPTURE">
     <td class="mavlink_type" valign="top">2000</td>
     <td class="mavlink_name" valign="top">MAV_CMD_IMAGE_START_CAPTURE</td>
     <td class="mavlink_comment">Start image capture sequence. Sends CAMERA_IMAGE_CAPTURED after each capture. Use NAN for reserved values.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_IMAGE_STOP_CAPTURE">
     <td class="mavlink_type" valign="top">2001</td>
     <td class="mavlink_name" valign="top">MAV_CMD_IMAGE_STOP_CAPTURE</td>
     <td class="mavlink_comment">Stop image capture sequence Use NAN for reserved values.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_REQUEST_CAMERA_IMAGE_CAPTURE">
     <td class="mavlink_type" valign="top">2002</td>
     <td class="mavlink_name" valign="top">MAV_CMD_REQUEST_CAMERA_IMAGE_CAPTURE</td>
     <td class="mavlink_comment">WIP: Re-request a CAMERA_IMAGE_CAPTURE packet. Use NAN for reserved values.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_TRIGGER_CONTROL">
     <td class="mavlink_type" valign="top">2003</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_TRIGGER_CONTROL</td>
     <td class="mavlink_comment">Enable or disable on-board camera triggering system.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_VIDEO_START_CAPTURE">
     <td class="mavlink_type" valign="top">2500</td>
     <td class="mavlink_name" valign="top">MAV_CMD_VIDEO_START_CAPTURE</td>
     <td class="mavlink_comment">Starts video capture (recording). Use NAN for reserved values.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_VIDEO_STOP_CAPTURE">
     <td class="mavlink_type" valign="top">2501</td>
     <td class="mavlink_name" valign="top">MAV_CMD_VIDEO_STOP_CAPTURE</td>
     <td class="mavlink_comment">Stop the current video capture (recording). Use NAN for reserved values.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_VIDEO_START_STREAMING">
     <td class="mavlink_type" valign="top">2502</td>
     <td class="mavlink_name" valign="top">MAV_CMD_VIDEO_START_STREAMING</td>
     <td class="mavlink_comment">WIP: Start video streaming</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_VIDEO_STOP_STREAMING">
     <td class="mavlink_type" valign="top">2503</td>
     <td class="mavlink_name" valign="top">MAV_CMD_VIDEO_STOP_STREAMING</td>
     <td class="mavlink_comment">WIP: Stop the current video streaming</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_REQUEST_VIDEO_STREAM_INFORMATION">
     <td class="mavlink_type" valign="top">2504</td>
     <td class="mavlink_name" valign="top">MAV_CMD_REQUEST_VIDEO_STREAM_INFORMATION</td>
     <td class="mavlink_comment">WIP: Request video stream information (VIDEO_STREAM_INFORMATION)</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_LOGGING_START">
     <td class="mavlink_type" valign="top">2510</td>
     <td class="mavlink_name" valign="top">MAV_CMD_LOGGING_START</td>
     <td class="mavlink_comment">Request to start streaming logging data over MAVLink (see also LOGGING_DATA message)</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_LOGGING_STOP">
     <td class="mavlink_type" valign="top">2511</td>
     <td class="mavlink_name" valign="top">MAV_CMD_LOGGING_STOP</td>
     <td class="mavlink_comment">Request to stop streaming log data over MAVLink</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_AIRFRAME_CONFIGURATION">
     <td class="mavlink_type" valign="top">2520</td>
     <td class="mavlink_name" valign="top">MAV_CMD_AIRFRAME_CONFIGURATION</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_PANORAMA_CREATE">
     <td class="mavlink_type" valign="top">2800</td>
     <td class="mavlink_name" valign="top">MAV_CMD_PANORAMA_CREATE</td>
     <td class="mavlink_comment">Create a panorama at the current position</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_DO_VTOL_TRANSITION">
     <td class="mavlink_type" valign="top">3000</td>
     <td class="mavlink_name" valign="top">MAV_CMD_DO_VTOL_TRANSITION</td>
     <td class="mavlink_comment">Request VTOL transition</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_SET_GUIDED_SUBMODE_STANDARD">
     <td class="mavlink_type" valign="top">4000</td>
     <td class="mavlink_name" valign="top">MAV_CMD_SET_GUIDED_SUBMODE_STANDARD</td>
     <td class="mavlink_comment">This command sets the submode to standard guided when vehicle is in guided mode. The vehicle holds position and altitude and the user can input the desired velocites along all three axes.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_SET_GUIDED_SUBMODE_CIRCLE">
     <td class="mavlink_type" valign="top">4001</td>
     <td class="mavlink_name" valign="top">MAV_CMD_SET_GUIDED_SUBMODE_CIRCLE</td>
     <td class="mavlink_comment">This command sets submode circle when vehicle is in guided mode. Vehicle flies along a circle facing the center of the circle. The user can input the velocity along the circle and change the radius. If no input is given the vehicle will hold position.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_CONDITION_GATE">
     <td class="mavlink_type" valign="top">4501</td>
     <td class="mavlink_name" valign="top">MAV_CMD_CONDITION_GATE</td>
     <td class="mavlink_comment">WIP: Delay mission state machine until gate has been reached.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_ARM_AUTHORIZATION_REQUEST">
     <td class="mavlink_type" valign="top">3001</td>
     <td class="mavlink_name" valign="top">MAV_CMD_ARM_AUTHORIZATION_REQUEST</td>
     <td class="mavlink_comment">Request authorization to arm the vehicle to a external entity, the arm authorizer is resposible to request all data that is needs from the vehicle before authorize or deny the request. If approved the progress of command_ack message should be set with period of time that this authorization is valid in seconds or in case it was denied it should be set with one of the reasons in ARM_AUTH_DENIED_REASON.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_FENCE_RETURN_POINT">
     <td class="mavlink_type" valign="top">5000</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_FENCE_RETURN_POINT</td>
     <td class="mavlink_comment">Fence return point. There can only be one fence return point.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_FENCE_POLYGON_VERTEX_INCLUSION">
     <td class="mavlink_type" valign="top">5001</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_FENCE_POLYGON_VERTEX_INCLUSION</td>
     <td class="mavlink_comment">Fence vertex for an inclusion polygon (the polygon must not be self-intersecting). The vehicle must stay within this area. Minimum of 3 vertices required.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_FENCE_POLYGON_VERTEX_EXCLUSION">
     <td class="mavlink_type" valign="top">5002</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_FENCE_POLYGON_VERTEX_EXCLUSION</td>
     <td class="mavlink_comment">Fence vertex for an exclusion polygon (the polygon must not be self-intersecting). The vehicle must stay outside this area. Minimum of 3 vertices required.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_FENCE_CIRCLE_INCLUSION">
     <td class="mavlink_type" valign="top">5003</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_FENCE_CIRCLE_INCLUSION</td>
     <td class="mavlink_comment">Circular fence area. The vehicle must stay inside this area.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_FENCE_CIRCLE_EXCLUSION">
     <td class="mavlink_type" valign="top">5004</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_FENCE_CIRCLE_EXCLUSION</td>
     <td class="mavlink_comment">Circular fence area. The vehicle must stay outside this area.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_NAV_RALLY_POINT">
     <td class="mavlink_type" valign="top">5100</td>
     <td class="mavlink_name" valign="top">MAV_CMD_NAV_RALLY_POINT</td>
     <td class="mavlink_comment">Rally point. You can have multiple rally points defined.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_UAVCAN_GET_NODE_INFO">
     <td class="mavlink_type" valign="top">5200</td>
     <td class="mavlink_name" valign="top">MAV_CMD_UAVCAN_GET_NODE_INFO</td>
     <td class="mavlink_comment">Commands the vehicle to respond with a sequence of messages UAVCAN_NODE_INFO, one message per every UAVCAN node that is online. Note that some of the response messages can be lost, which the receiver can detect easily by checking whether every received UAVCAN_NODE_STATUS has a matching message UAVCAN_NODE_INFO received earlier; if not, this command should be sent again in order to request re-transmission of the node information messages.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_PAYLOAD_PREPARE_DEPLOY">
     <td class="mavlink_type" valign="top">30001</td>
     <td class="mavlink_name" valign="top">MAV_CMD_PAYLOAD_PREPARE_DEPLOY</td>
     <td class="mavlink_comment">Deploy payload on a Lat / Lon / Alt position. This includes the navigation to reach the required release position and velocity.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_PAYLOAD_CONTROL_DEPLOY">
     <td class="mavlink_type" valign="top">30002</td>
     <td class="mavlink_name" valign="top">MAV_CMD_PAYLOAD_CONTROL_DEPLOY</td>
     <td class="mavlink_comment">Control the payload deployment.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_WAYPOINT_USER_1">
     <td class="mavlink_type" valign="top">31000</td>
     <td class="mavlink_name" valign="top">MAV_CMD_WAYPOINT_USER_1</td>
     <td class="mavlink_comment">User defined waypoint item. Ground Station will show the Vehicle as flying through this item.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_WAYPOINT_USER_2">
     <td class="mavlink_type" valign="top">31001</td>
     <td class="mavlink_name" valign="top">MAV_CMD_WAYPOINT_USER_2</td>
     <td class="mavlink_comment">User defined waypoint item. Ground Station will show the Vehicle as flying through this item.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_WAYPOINT_USER_3">
     <td class="mavlink_type" valign="top">31002</td>
     <td class="mavlink_name" valign="top">MAV_CMD_WAYPOINT_USER_3</td>
     <td class="mavlink_comment">User defined waypoint item. Ground Station will show the Vehicle as flying through this item.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_WAYPOINT_USER_4">
     <td class="mavlink_type" valign="top">31003</td>
     <td class="mavlink_name" valign="top">MAV_CMD_WAYPOINT_USER_4</td>
     <td class="mavlink_comment">User defined waypoint item. Ground Station will show the Vehicle as flying through this item.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_WAYPOINT_USER_5">
     <td class="mavlink_type" valign="top">31004</td>
     <td class="mavlink_name" valign="top">MAV_CMD_WAYPOINT_USER_5</td>
     <td class="mavlink_comment">User defined waypoint item. Ground Station will show the Vehicle as flying through this item.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_SPATIAL_USER_1">
     <td class="mavlink_type" valign="top">31005</td>
     <td class="mavlink_name" valign="top">MAV_CMD_SPATIAL_USER_1</td>
     <td class="mavlink_comment">User defined spatial item. Ground Station will not show the Vehicle as flying through this item. Example: ROI item.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_SPATIAL_USER_2">
     <td class="mavlink_type" valign="top">31006</td>
     <td class="mavlink_name" valign="top">MAV_CMD_SPATIAL_USER_2</td>
     <td class="mavlink_comment">User defined spatial item. Ground Station will not show the Vehicle as flying through this item. Example: ROI item.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_SPATIAL_USER_3">
     <td class="mavlink_type" valign="top">31007</td>
     <td class="mavlink_name" valign="top">MAV_CMD_SPATIAL_USER_3</td>
     <td class="mavlink_comment">User defined spatial item. Ground Station will not show the Vehicle as flying through this item. Example: ROI item.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_SPATIAL_USER_4">
     <td class="mavlink_type" valign="top">31008</td>
     <td class="mavlink_name" valign="top">MAV_CMD_SPATIAL_USER_4</td>
     <td class="mavlink_comment">User defined spatial item. Ground Station will not show the Vehicle as flying through this item. Example: ROI item.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_SPATIAL_USER_5">
     <td class="mavlink_type" valign="top">31009</td>
     <td class="mavlink_name" valign="top">MAV_CMD_SPATIAL_USER_5</td>
     <td class="mavlink_comment">User defined spatial item. Ground Station will not show the Vehicle as flying through this item. Example: ROI item.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_USER_1">
     <td class="mavlink_type" valign="top">31010</td>
     <td class="mavlink_name" valign="top">MAV_CMD_USER_1</td>
     <td class="mavlink_comment">User defined command. Ground Station will not show the Vehicle as flying through this item. Example: MAV_CMD_DO_SET_PARAMETER item.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_USER_2">
     <td class="mavlink_type" valign="top">31011</td>
     <td class="mavlink_name" valign="top">MAV_CMD_USER_2</td>
     <td class="mavlink_comment">User defined command. Ground Station will not show the Vehicle as flying through this item. Example: MAV_CMD_DO_SET_PARAMETER item.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_USER_3">
     <td class="mavlink_type" valign="top">31012</td>
     <td class="mavlink_name" valign="top">MAV_CMD_USER_3</td>
     <td class="mavlink_comment">User defined command. Ground Station will not show the Vehicle as flying through this item. Example: MAV_CMD_DO_SET_PARAMETER item.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_USER_4">
     <td class="mavlink_type" valign="top">31013</td>
     <td class="mavlink_name" valign="top">MAV_CMD_USER_4</td>
     <td class="mavlink_comment">User defined command. Ground Station will not show the Vehicle as flying through this item. Example: MAV_CMD_DO_SET_PARAMETER item.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_USER_5">
     <td class="mavlink_type" valign="top">31014</td>
     <td class="mavlink_name" valign="top">MAV_CMD_USER_5</td>
     <td class="mavlink_comment">User defined command. Ground Station will not show the Vehicle as flying through this item. Example: MAV_CMD_DO_SET_PARAMETER item.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_DATA_STREAM" name="ENUM_MAV_DATA_STREAM">MAV_DATA_STREAM</h2>
  <p class="description">THIS INTERFACE IS DEPRECATED AS OF JULY 2015. Please use MESSAGE_INTERVAL instead. A data stream is not a fixed set of messages, but rather a
     recommendation to the autopilot software. Individual autopilots may or may not obey
     the recommended messages.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_DATA_STREAM_ALL">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_DATA_STREAM_ALL</td>
     <td class="mavlink_comment">Enable all data streams</td>
    </tr>
    <tr class="mavlink_field" id="MAV_DATA_STREAM_RAW_SENSORS">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_DATA_STREAM_RAW_SENSORS</td>
     <td class="mavlink_comment">Enable IMU_RAW, GPS_RAW, GPS_STATUS packets.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_DATA_STREAM_EXTENDED_STATUS">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_DATA_STREAM_EXTENDED_STATUS</td>
     <td class="mavlink_comment">Enable GPS_STATUS, CONTROL_STATUS, AUX_STATUS</td>
    </tr>
    <tr class="mavlink_field" id="MAV_DATA_STREAM_RC_CHANNELS">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_DATA_STREAM_RC_CHANNELS</td>
     <td class="mavlink_comment">Enable RC_CHANNELS_SCALED, RC_CHANNELS_RAW, SERVO_OUTPUT_RAW</td>
    </tr>
    <tr class="mavlink_field" id="MAV_DATA_STREAM_RAW_CONTROLLER">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_DATA_STREAM_RAW_CONTROLLER</td>
     <td class="mavlink_comment">Enable ATTITUDE_CONTROLLER_OUTPUT, POSITION_CONTROLLER_OUTPUT, NAV_CONTROLLER_OUTPUT.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_DATA_STREAM_POSITION">
     <td class="mavlink_type" valign="top">6</td>
     <td class="mavlink_name" valign="top">MAV_DATA_STREAM_POSITION</td>
     <td class="mavlink_comment">Enable LOCAL_POSITION, GLOBAL_POSITION/GLOBAL_POSITION_INT messages.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_DATA_STREAM_EXTRA1">
     <td class="mavlink_type" valign="top">10</td>
     <td class="mavlink_name" valign="top">MAV_DATA_STREAM_EXTRA1</td>
     <td class="mavlink_comment">Dependent on the autopilot</td>
    </tr>
    <tr class="mavlink_field" id="MAV_DATA_STREAM_EXTRA2">
     <td class="mavlink_type" valign="top">11</td>
     <td class="mavlink_name" valign="top">MAV_DATA_STREAM_EXTRA2</td>
     <td class="mavlink_comment">Dependent on the autopilot</td>
    </tr>
    <tr class="mavlink_field" id="MAV_DATA_STREAM_EXTRA3">
     <td class="mavlink_type" valign="top">12</td>
     <td class="mavlink_name" valign="top">MAV_DATA_STREAM_EXTRA3</td>
     <td class="mavlink_comment">Dependent on the autopilot</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_ROI" name="ENUM_MAV_ROI">MAV_ROI</h2>
  <p class="description">The ROI (region of interest) for the vehicle. This can be
                be used by the vehicle for camera/vehicle attitude alignment (see
                MAV_CMD_NAV_ROI).</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_ROI_NONE">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_ROI_NONE</td>
     <td class="mavlink_comment">No region of interest.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_ROI_WPNEXT">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_ROI_WPNEXT</td>
     <td class="mavlink_comment">Point toward next waypoint.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_ROI_WPINDEX">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_ROI_WPINDEX</td>
     <td class="mavlink_comment">Point toward given waypoint.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_ROI_LOCATION">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_ROI_LOCATION</td>
     <td class="mavlink_comment">Point toward fixed location.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_ROI_TARGET">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_ROI_TARGET</td>
     <td class="mavlink_comment">Point toward of given id.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_CMD_ACK" name="ENUM_MAV_CMD_ACK">MAV_CMD_ACK</h2>
  <p class="description">ACK / NACK / ERROR values as a result of MAV_CMDs and for mission item transmission.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_CMD_ACK_OK">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_CMD_ACK_OK</td>
     <td class="mavlink_comment">Command / mission item is ok.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_ACK_ERR_FAIL">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_CMD_ACK_ERR_FAIL</td>
     <td class="mavlink_comment">Generic error message if none of the other reasons fails or if no detailed error reporting is implemented.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_ACK_ERR_ACCESS_DENIED">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_CMD_ACK_ERR_ACCESS_DENIED</td>
     <td class="mavlink_comment">The system is refusing to accept this command from this source / communication partner.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_ACK_ERR_NOT_SUPPORTED">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_CMD_ACK_ERR_NOT_SUPPORTED</td>
     <td class="mavlink_comment">Command or mission item is not supported, other commands would be accepted.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_ACK_ERR_COORDINATE_FRAME_NOT_SUPPORTED">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_CMD_ACK_ERR_COORDINATE_FRAME_NOT_SUPPORTED</td>
     <td class="mavlink_comment">The coordinate frame of this command / mission item is not supported.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_ACK_ERR_COORDINATES_OUT_OF_RANGE">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_CMD_ACK_ERR_COORDINATES_OUT_OF_RANGE</td>
     <td class="mavlink_comment">The coordinate frame of this command is ok, but he coordinate values exceed the safety limits of this system. This is a generic error, please use the more specific error messages below if possible.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_ACK_ERR_X_LAT_OUT_OF_RANGE">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_CMD_ACK_ERR_X_LAT_OUT_OF_RANGE</td>
     <td class="mavlink_comment">The X or latitude value is out of range.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_ACK_ERR_Y_LON_OUT_OF_RANGE">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_CMD_ACK_ERR_Y_LON_OUT_OF_RANGE</td>
     <td class="mavlink_comment">The Y or longitude value is out of range.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_CMD_ACK_ERR_Z_ALT_OUT_OF_RANGE">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_CMD_ACK_ERR_Z_ALT_OUT_OF_RANGE</td>
     <td class="mavlink_comment">The Z or altitude value is out of range.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_PARAM_TYPE" name="ENUM_MAV_PARAM_TYPE">MAV_PARAM_TYPE</h2>
  <p class="description">Specifies the datatype of a MAVLink parameter.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_PARAM_TYPE_UINT8">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_TYPE_UINT8</td>
     <td class="mavlink_comment">8-bit unsigned integer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_TYPE_INT8">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_TYPE_INT8</td>
     <td class="mavlink_comment">8-bit signed integer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_TYPE_UINT16">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_TYPE_UINT16</td>
     <td class="mavlink_comment">16-bit unsigned integer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_TYPE_INT16">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_TYPE_INT16</td>
     <td class="mavlink_comment">16-bit signed integer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_TYPE_UINT32">
     <td class="mavlink_type" valign="top">5</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_TYPE_UINT32</td>
     <td class="mavlink_comment">32-bit unsigned integer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_TYPE_INT32">
     <td class="mavlink_type" valign="top">6</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_TYPE_INT32</td>
     <td class="mavlink_comment">32-bit signed integer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_TYPE_UINT64">
     <td class="mavlink_type" valign="top">7</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_TYPE_UINT64</td>
     <td class="mavlink_comment">64-bit unsigned integer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_TYPE_INT64">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_TYPE_INT64</td>
     <td class="mavlink_comment">64-bit signed integer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_TYPE_REAL32">
     <td class="mavlink_type" valign="top">9</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_TYPE_REAL32</td>
     <td class="mavlink_comment">32-bit floating-point</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_TYPE_REAL64">
     <td class="mavlink_type" valign="top">10</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_TYPE_REAL64</td>
     <td class="mavlink_comment">64-bit floating-point</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_PARAM_EXT_TYPE" name="ENUM_MAV_PARAM_EXT_TYPE">MAV_PARAM_EXT_TYPE</h2>
  <p class="description">Specifies the datatype of a MAVLink extended parameter.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_PARAM_EXT_TYPE_UINT8">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_EXT_TYPE_UINT8</td>
     <td class="mavlink_comment">8-bit unsigned integer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_EXT_TYPE_INT8">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_EXT_TYPE_INT8</td>
     <td class="mavlink_comment">8-bit signed integer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_EXT_TYPE_UINT16">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_EXT_TYPE_UINT16</td>
     <td class="mavlink_comment">16-bit unsigned integer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_EXT_TYPE_INT16">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_EXT_TYPE_INT16</td>
     <td class="mavlink_comment">16-bit signed integer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_EXT_TYPE_UINT32">
     <td class="mavlink_type" valign="top">5</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_EXT_TYPE_UINT32</td>
     <td class="mavlink_comment">32-bit unsigned integer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_EXT_TYPE_INT32">
     <td class="mavlink_type" valign="top">6</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_EXT_TYPE_INT32</td>
     <td class="mavlink_comment">32-bit signed integer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_EXT_TYPE_UINT64">
     <td class="mavlink_type" valign="top">7</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_EXT_TYPE_UINT64</td>
     <td class="mavlink_comment">64-bit unsigned integer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_EXT_TYPE_INT64">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_EXT_TYPE_INT64</td>
     <td class="mavlink_comment">64-bit signed integer</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_EXT_TYPE_REAL32">
     <td class="mavlink_type" valign="top">9</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_EXT_TYPE_REAL32</td>
     <td class="mavlink_comment">32-bit floating-point</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_EXT_TYPE_REAL64">
     <td class="mavlink_type" valign="top">10</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_EXT_TYPE_REAL64</td>
     <td class="mavlink_comment">64-bit floating-point</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PARAM_EXT_TYPE_CUSTOM">
     <td class="mavlink_type" valign="top">11</td>
     <td class="mavlink_name" valign="top">MAV_PARAM_EXT_TYPE_CUSTOM</td>
     <td class="mavlink_comment">Custom Type</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_RESULT" name="ENUM_MAV_RESULT">MAV_RESULT</h2>
  <p class="description">result from a mavlink command</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_RESULT_ACCEPTED">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_RESULT_ACCEPTED</td>
     <td class="mavlink_comment">Command ACCEPTED and EXECUTED</td>
    </tr>
    <tr class="mavlink_field" id="MAV_RESULT_TEMPORARILY_REJECTED">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_RESULT_TEMPORARILY_REJECTED</td>
     <td class="mavlink_comment">Command TEMPORARY REJECTED/DENIED</td>
    </tr>
    <tr class="mavlink_field" id="MAV_RESULT_DENIED">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_RESULT_DENIED</td>
     <td class="mavlink_comment">Command PERMANENTLY DENIED</td>
    </tr>
    <tr class="mavlink_field" id="MAV_RESULT_UNSUPPORTED">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_RESULT_UNSUPPORTED</td>
     <td class="mavlink_comment">Command UNKNOWN/UNSUPPORTED</td>
    </tr>
    <tr class="mavlink_field" id="MAV_RESULT_FAILED">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_RESULT_FAILED</td>
     <td class="mavlink_comment">Command executed, but failed</td>
    </tr>
    <tr class="mavlink_field" id="MAV_RESULT_IN_PROGRESS">
     <td class="mavlink_type" valign="top">5</td>
     <td class="mavlink_name" valign="top">MAV_RESULT_IN_PROGRESS</td>
     <td class="mavlink_comment">WIP: Command being executed</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_MISSION_RESULT" name="ENUM_MAV_MISSION_RESULT">MAV_MISSION_RESULT</h2>
  <p class="description">result in a mavlink mission ack</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_MISSION_ACCEPTED">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_ACCEPTED</td>
     <td class="mavlink_comment">mission accepted OK</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MISSION_ERROR">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_ERROR</td>
     <td class="mavlink_comment">generic error / not accepting mission commands at all right now</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MISSION_UNSUPPORTED_FRAME">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_UNSUPPORTED_FRAME</td>
     <td class="mavlink_comment">coordinate frame is not supported</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MISSION_UNSUPPORTED">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_UNSUPPORTED</td>
     <td class="mavlink_comment">command is not supported</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MISSION_NO_SPACE">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_NO_SPACE</td>
     <td class="mavlink_comment">mission item exceeds storage space</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MISSION_INVALID">
     <td class="mavlink_type" valign="top">5</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_INVALID</td>
     <td class="mavlink_comment">one of the parameters has an invalid value</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MISSION_INVALID_PARAM1">
     <td class="mavlink_type" valign="top">6</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_INVALID_PARAM1</td>
     <td class="mavlink_comment">param1 has an invalid value</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MISSION_INVALID_PARAM2">
     <td class="mavlink_type" valign="top">7</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_INVALID_PARAM2</td>
     <td class="mavlink_comment">param2 has an invalid value</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MISSION_INVALID_PARAM3">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_INVALID_PARAM3</td>
     <td class="mavlink_comment">param3 has an invalid value</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MISSION_INVALID_PARAM4">
     <td class="mavlink_type" valign="top">9</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_INVALID_PARAM4</td>
     <td class="mavlink_comment">param4 has an invalid value</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MISSION_INVALID_PARAM5_X">
     <td class="mavlink_type" valign="top">10</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_INVALID_PARAM5_X</td>
     <td class="mavlink_comment">x/param5 has an invalid value</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MISSION_INVALID_PARAM6_Y">
     <td class="mavlink_type" valign="top">11</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_INVALID_PARAM6_Y</td>
     <td class="mavlink_comment">y/param6 has an invalid value</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MISSION_INVALID_PARAM7">
     <td class="mavlink_type" valign="top">12</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_INVALID_PARAM7</td>
     <td class="mavlink_comment">param7 has an invalid value</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MISSION_INVALID_SEQUENCE">
     <td class="mavlink_type" valign="top">13</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_INVALID_SEQUENCE</td>
     <td class="mavlink_comment">received waypoint out of sequence</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MISSION_DENIED">
     <td class="mavlink_type" valign="top">14</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_DENIED</td>
     <td class="mavlink_comment">not accepting any mission commands from this communication partner</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_SEVERITY" name="ENUM_MAV_SEVERITY">MAV_SEVERITY</h2>
  <p class="description">Indicates the severity level, generally used for status messages to indicate their relative urgency. Based on RFC-5424 using expanded definitions at: http://www.kiwisyslog.com/kb/info:-syslog-message-levels/.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_SEVERITY_EMERGENCY">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_SEVERITY_EMERGENCY</td>
     <td class="mavlink_comment">System is unusable. This is a "panic" condition.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SEVERITY_ALERT">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_SEVERITY_ALERT</td>
     <td class="mavlink_comment">Action should be taken immediately. Indicates error in non-critical systems.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SEVERITY_CRITICAL">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_SEVERITY_CRITICAL</td>
     <td class="mavlink_comment">Action must be taken immediately. Indicates failure in a primary system.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SEVERITY_ERROR">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_SEVERITY_ERROR</td>
     <td class="mavlink_comment">Indicates an error in secondary/redundant systems.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SEVERITY_WARNING">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_SEVERITY_WARNING</td>
     <td class="mavlink_comment">Indicates about a possible future error if this is not resolved within a given timeframe. Example would be a low battery warning.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SEVERITY_NOTICE">
     <td class="mavlink_type" valign="top">5</td>
     <td class="mavlink_name" valign="top">MAV_SEVERITY_NOTICE</td>
     <td class="mavlink_comment">An unusual event has occured, though not an error condition. This should be investigated for the root cause.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SEVERITY_INFO">
     <td class="mavlink_type" valign="top">6</td>
     <td class="mavlink_name" valign="top">MAV_SEVERITY_INFO</td>
     <td class="mavlink_comment">Normal operational messages. Useful for logging. No action is required for these messages.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SEVERITY_DEBUG">
     <td class="mavlink_type" valign="top">7</td>
     <td class="mavlink_name" valign="top">MAV_SEVERITY_DEBUG</td>
     <td class="mavlink_comment">Useful non-operational messages that can assist in debugging. These should not occur during normal operation.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_POWER_STATUS" name="ENUM_MAV_POWER_STATUS">MAV_POWER_STATUS</h2>
  <p class="description">Power supply status flags (bitmask)</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_POWER_STATUS_BRICK_VALID">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_POWER_STATUS_BRICK_VALID</td>
     <td class="mavlink_comment">main brick power supply valid</td>
    </tr>
    <tr class="mavlink_field" id="MAV_POWER_STATUS_SERVO_VALID">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_POWER_STATUS_SERVO_VALID</td>
     <td class="mavlink_comment">main servo power supply valid for FMU</td>
    </tr>
    <tr class="mavlink_field" id="MAV_POWER_STATUS_USB_CONNECTED">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_POWER_STATUS_USB_CONNECTED</td>
     <td class="mavlink_comment">USB power is connected</td>
    </tr>
    <tr class="mavlink_field" id="MAV_POWER_STATUS_PERIPH_OVERCURRENT">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">MAV_POWER_STATUS_PERIPH_OVERCURRENT</td>
     <td class="mavlink_comment">peripheral supply is in over-current state</td>
    </tr>
    <tr class="mavlink_field" id="MAV_POWER_STATUS_PERIPH_HIPOWER_OVERCURRENT">
     <td class="mavlink_type" valign="top">16</td>
     <td class="mavlink_name" valign="top">MAV_POWER_STATUS_PERIPH_HIPOWER_OVERCURRENT</td>
     <td class="mavlink_comment">hi-power peripheral supply is in over-current state</td>
    </tr>
    <tr class="mavlink_field" id="MAV_POWER_STATUS_CHANGED">
     <td class="mavlink_type" valign="top">32</td>
     <td class="mavlink_name" valign="top">MAV_POWER_STATUS_CHANGED</td>
     <td class="mavlink_comment">Power status has changed since boot</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SERIAL_CONTROL_DEV" name="ENUM_SERIAL_CONTROL_DEV">SERIAL_CONTROL_DEV</h2>
  <p class="description">SERIAL_CONTROL device types</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="SERIAL_CONTROL_DEV_TELEM1">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">SERIAL_CONTROL_DEV_TELEM1</td>
     <td class="mavlink_comment">First telemetry port</td>
    </tr>
    <tr class="mavlink_field" id="SERIAL_CONTROL_DEV_TELEM2">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">SERIAL_CONTROL_DEV_TELEM2</td>
     <td class="mavlink_comment">Second telemetry port</td>
    </tr>
    <tr class="mavlink_field" id="SERIAL_CONTROL_DEV_GPS1">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">SERIAL_CONTROL_DEV_GPS1</td>
     <td class="mavlink_comment">First GPS port</td>
    </tr>
    <tr class="mavlink_field" id="SERIAL_CONTROL_DEV_GPS2">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">SERIAL_CONTROL_DEV_GPS2</td>
     <td class="mavlink_comment">Second GPS port</td>
    </tr>
    <tr class="mavlink_field" id="SERIAL_CONTROL_DEV_SHELL">
     <td class="mavlink_type" valign="top">10</td>
     <td class="mavlink_name" valign="top">SERIAL_CONTROL_DEV_SHELL</td>
     <td class="mavlink_comment">system shell</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SERIAL_CONTROL_FLAG" name="ENUM_SERIAL_CONTROL_FLAG">SERIAL_CONTROL_FLAG</h2>
  <p class="description">SERIAL_CONTROL flags (bitmask)</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="SERIAL_CONTROL_FLAG_REPLY">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">SERIAL_CONTROL_FLAG_REPLY</td>
     <td class="mavlink_comment">Set if this is a reply</td>
    </tr>
    <tr class="mavlink_field" id="SERIAL_CONTROL_FLAG_RESPOND">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">SERIAL_CONTROL_FLAG_RESPOND</td>
     <td class="mavlink_comment">Set if the sender wants the receiver to send a response as another SERIAL_CONTROL message</td>
    </tr>
    <tr class="mavlink_field" id="SERIAL_CONTROL_FLAG_EXCLUSIVE">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">SERIAL_CONTROL_FLAG_EXCLUSIVE</td>
     <td class="mavlink_comment">Set if access to the serial port should be removed from whatever driver is currently using it, giving exclusive access to the SERIAL_CONTROL protocol. The port can be handed back by sending a request without this flag set</td>
    </tr>
    <tr class="mavlink_field" id="SERIAL_CONTROL_FLAG_BLOCKING">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">SERIAL_CONTROL_FLAG_BLOCKING</td>
     <td class="mavlink_comment">Block on writes to the serial port</td>
    </tr>
    <tr class="mavlink_field" id="SERIAL_CONTROL_FLAG_MULTI">
     <td class="mavlink_type" valign="top">16</td>
     <td class="mavlink_name" valign="top">SERIAL_CONTROL_FLAG_MULTI</td>
     <td class="mavlink_comment">Send multiple replies until port is drained</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_DISTANCE_SENSOR" name="ENUM_MAV_DISTANCE_SENSOR">MAV_DISTANCE_SENSOR</h2>
  <p class="description">Enumeration of distance sensor types</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_DISTANCE_SENSOR_LASER">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_DISTANCE_SENSOR_LASER</td>
     <td class="mavlink_comment">Laser rangefinder, e.g. LightWare SF02/F or PulsedLight units</td>
    </tr>
    <tr class="mavlink_field" id="MAV_DISTANCE_SENSOR_ULTRASOUND">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_DISTANCE_SENSOR_ULTRASOUND</td>
     <td class="mavlink_comment">Ultrasound rangefinder, e.g. MaxBotix units</td>
    </tr>
    <tr class="mavlink_field" id="MAV_DISTANCE_SENSOR_INFRARED">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_DISTANCE_SENSOR_INFRARED</td>
     <td class="mavlink_comment">Infrared rangefinder, e.g. Sharp units</td>
    </tr>
    <tr class="mavlink_field" id="MAV_DISTANCE_SENSOR_RADAR">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_DISTANCE_SENSOR_RADAR</td>
     <td class="mavlink_comment">Radar type, e.g. uLanding units</td>
    </tr>
    <tr class="mavlink_field" id="MAV_DISTANCE_SENSOR_UNKNOWN">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_DISTANCE_SENSOR_UNKNOWN</td>
     <td class="mavlink_comment">Broken or unknown type, e.g. analog units</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_SENSOR_ORIENTATION" name="ENUM_MAV_SENSOR_ORIENTATION">MAV_SENSOR_ORIENTATION</h2>
  <p class="description">Enumeration of sensor orientation, according to its rotations</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_NONE">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_NONE</td>
     <td class="mavlink_comment">Roll: 0, Pitch: 0, Yaw: 0</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_YAW_45">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_YAW_45</td>
     <td class="mavlink_comment">Roll: 0, Pitch: 0, Yaw: 45</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_YAW_90">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_YAW_90</td>
     <td class="mavlink_comment">Roll: 0, Pitch: 0, Yaw: 90</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_YAW_135">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_YAW_135</td>
     <td class="mavlink_comment">Roll: 0, Pitch: 0, Yaw: 135</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_YAW_180">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_YAW_180</td>
     <td class="mavlink_comment">Roll: 0, Pitch: 0, Yaw: 180</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_YAW_225">
     <td class="mavlink_type" valign="top">5</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_YAW_225</td>
     <td class="mavlink_comment">Roll: 0, Pitch: 0, Yaw: 225</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_YAW_270">
     <td class="mavlink_type" valign="top">6</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_YAW_270</td>
     <td class="mavlink_comment">Roll: 0, Pitch: 0, Yaw: 270</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_YAW_315">
     <td class="mavlink_type" valign="top">7</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_YAW_315</td>
     <td class="mavlink_comment">Roll: 0, Pitch: 0, Yaw: 315</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_180">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_180</td>
     <td class="mavlink_comment">Roll: 180, Pitch: 0, Yaw: 0</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_180_YAW_45">
     <td class="mavlink_type" valign="top">9</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_180_YAW_45</td>
     <td class="mavlink_comment">Roll: 180, Pitch: 0, Yaw: 45</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_180_YAW_90">
     <td class="mavlink_type" valign="top">10</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_180_YAW_90</td>
     <td class="mavlink_comment">Roll: 180, Pitch: 0, Yaw: 90</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_180_YAW_135">
     <td class="mavlink_type" valign="top">11</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_180_YAW_135</td>
     <td class="mavlink_comment">Roll: 180, Pitch: 0, Yaw: 135</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_PITCH_180">
     <td class="mavlink_type" valign="top">12</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_PITCH_180</td>
     <td class="mavlink_comment">Roll: 0, Pitch: 180, Yaw: 0</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_180_YAW_225">
     <td class="mavlink_type" valign="top">13</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_180_YAW_225</td>
     <td class="mavlink_comment">Roll: 180, Pitch: 0, Yaw: 225</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_180_YAW_270">
     <td class="mavlink_type" valign="top">14</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_180_YAW_270</td>
     <td class="mavlink_comment">Roll: 180, Pitch: 0, Yaw: 270</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_180_YAW_315">
     <td class="mavlink_type" valign="top">15</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_180_YAW_315</td>
     <td class="mavlink_comment">Roll: 180, Pitch: 0, Yaw: 315</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_90">
     <td class="mavlink_type" valign="top">16</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_90</td>
     <td class="mavlink_comment">Roll: 90, Pitch: 0, Yaw: 0</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_90_YAW_45">
     <td class="mavlink_type" valign="top">17</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_90_YAW_45</td>
     <td class="mavlink_comment">Roll: 90, Pitch: 0, Yaw: 45</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_90_YAW_90">
     <td class="mavlink_type" valign="top">18</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_90_YAW_90</td>
     <td class="mavlink_comment">Roll: 90, Pitch: 0, Yaw: 90</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_90_YAW_135">
     <td class="mavlink_type" valign="top">19</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_90_YAW_135</td>
     <td class="mavlink_comment">Roll: 90, Pitch: 0, Yaw: 135</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_270">
     <td class="mavlink_type" valign="top">20</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_270</td>
     <td class="mavlink_comment">Roll: 270, Pitch: 0, Yaw: 0</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_270_YAW_45">
     <td class="mavlink_type" valign="top">21</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_270_YAW_45</td>
     <td class="mavlink_comment">Roll: 270, Pitch: 0, Yaw: 45</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_270_YAW_90">
     <td class="mavlink_type" valign="top">22</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_270_YAW_90</td>
     <td class="mavlink_comment">Roll: 270, Pitch: 0, Yaw: 90</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_270_YAW_135">
     <td class="mavlink_type" valign="top">23</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_270_YAW_135</td>
     <td class="mavlink_comment">Roll: 270, Pitch: 0, Yaw: 135</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_PITCH_90">
     <td class="mavlink_type" valign="top">24</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_PITCH_90</td>
     <td class="mavlink_comment">Roll: 0, Pitch: 90, Yaw: 0</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_PITCH_270">
     <td class="mavlink_type" valign="top">25</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_PITCH_270</td>
     <td class="mavlink_comment">Roll: 0, Pitch: 270, Yaw: 0</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_PITCH_180_YAW_90">
     <td class="mavlink_type" valign="top">26</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_PITCH_180_YAW_90</td>
     <td class="mavlink_comment">Roll: 0, Pitch: 180, Yaw: 90</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_PITCH_180_YAW_270">
     <td class="mavlink_type" valign="top">27</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_PITCH_180_YAW_270</td>
     <td class="mavlink_comment">Roll: 0, Pitch: 180, Yaw: 270</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_90_PITCH_90">
     <td class="mavlink_type" valign="top">28</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_90_PITCH_90</td>
     <td class="mavlink_comment">Roll: 90, Pitch: 90, Yaw: 0</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_180_PITCH_90">
     <td class="mavlink_type" valign="top">29</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_180_PITCH_90</td>
     <td class="mavlink_comment">Roll: 180, Pitch: 90, Yaw: 0</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_270_PITCH_90">
     <td class="mavlink_type" valign="top">30</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_270_PITCH_90</td>
     <td class="mavlink_comment">Roll: 270, Pitch: 90, Yaw: 0</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_90_PITCH_180">
     <td class="mavlink_type" valign="top">31</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_90_PITCH_180</td>
     <td class="mavlink_comment">Roll: 90, Pitch: 180, Yaw: 0</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_270_PITCH_180">
     <td class="mavlink_type" valign="top">32</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_270_PITCH_180</td>
     <td class="mavlink_comment">Roll: 270, Pitch: 180, Yaw: 0</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_90_PITCH_270">
     <td class="mavlink_type" valign="top">33</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_90_PITCH_270</td>
     <td class="mavlink_comment">Roll: 90, Pitch: 270, Yaw: 0</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_180_PITCH_270">
     <td class="mavlink_type" valign="top">34</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_180_PITCH_270</td>
     <td class="mavlink_comment">Roll: 180, Pitch: 270, Yaw: 0</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_270_PITCH_270">
     <td class="mavlink_type" valign="top">35</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_270_PITCH_270</td>
     <td class="mavlink_comment">Roll: 270, Pitch: 270, Yaw: 0</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_90_PITCH_180_YAW_90">
     <td class="mavlink_type" valign="top">36</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_90_PITCH_180_YAW_90</td>
     <td class="mavlink_comment">Roll: 90, Pitch: 180, Yaw: 90</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_90_YAW_270">
     <td class="mavlink_type" valign="top">37</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_90_YAW_270</td>
     <td class="mavlink_comment">Roll: 90, Pitch: 0, Yaw: 270</td>
    </tr>
    <tr class="mavlink_field" id="MAV_SENSOR_ROTATION_ROLL_315_PITCH_315_YAW_315">
     <td class="mavlink_type" valign="top">38</td>
     <td class="mavlink_name" valign="top">MAV_SENSOR_ROTATION_ROLL_315_PITCH_315_YAW_315</td>
     <td class="mavlink_comment">Roll: 315, Pitch: 315, Yaw: 315</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_PROTOCOL_CAPABILITY" name="ENUM_MAV_PROTOCOL_CAPABILITY">MAV_PROTOCOL_CAPABILITY</h2>
  <p class="description">Bitmask of (optional) autopilot capabilities (64 bit). If a bit is set, the autopilot supports this capability.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_PROTOCOL_CAPABILITY_MISSION_FLOAT">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_PROTOCOL_CAPABILITY_MISSION_FLOAT</td>
     <td class="mavlink_comment">Autopilot supports MISSION float message type.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PROTOCOL_CAPABILITY_PARAM_FLOAT">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_PROTOCOL_CAPABILITY_PARAM_FLOAT</td>
     <td class="mavlink_comment">Autopilot supports the new param float message type.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PROTOCOL_CAPABILITY_MISSION_INT">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_PROTOCOL_CAPABILITY_MISSION_INT</td>
     <td class="mavlink_comment">Autopilot supports MISSION_INT scaled integer message type.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PROTOCOL_CAPABILITY_COMMAND_INT">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">MAV_PROTOCOL_CAPABILITY_COMMAND_INT</td>
     <td class="mavlink_comment">Autopilot supports COMMAND_INT scaled integer message type.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PROTOCOL_CAPABILITY_PARAM_UNION">
     <td class="mavlink_type" valign="top">16</td>
     <td class="mavlink_name" valign="top">MAV_PROTOCOL_CAPABILITY_PARAM_UNION</td>
     <td class="mavlink_comment">Autopilot supports the new param union message type.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PROTOCOL_CAPABILITY_FTP">
     <td class="mavlink_type" valign="top">32</td>
     <td class="mavlink_name" valign="top">MAV_PROTOCOL_CAPABILITY_FTP</td>
     <td class="mavlink_comment">Autopilot supports the new FILE_TRANSFER_PROTOCOL message type.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PROTOCOL_CAPABILITY_SET_ATTITUDE_TARGET">
     <td class="mavlink_type" valign="top">64</td>
     <td class="mavlink_name" valign="top">MAV_PROTOCOL_CAPABILITY_SET_ATTITUDE_TARGET</td>
     <td class="mavlink_comment">Autopilot supports commanding attitude offboard.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PROTOCOL_CAPABILITY_SET_POSITION_TARGET_LOCAL_NED">
     <td class="mavlink_type" valign="top">128</td>
     <td class="mavlink_name" valign="top">MAV_PROTOCOL_CAPABILITY_SET_POSITION_TARGET_LOCAL_NED</td>
     <td class="mavlink_comment">Autopilot supports commanding position and velocity targets in local NED frame.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PROTOCOL_CAPABILITY_SET_POSITION_TARGET_GLOBAL_INT">
     <td class="mavlink_type" valign="top">256</td>
     <td class="mavlink_name" valign="top">MAV_PROTOCOL_CAPABILITY_SET_POSITION_TARGET_GLOBAL_INT</td>
     <td class="mavlink_comment">Autopilot supports commanding position and velocity targets in global scaled integers.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PROTOCOL_CAPABILITY_TERRAIN">
     <td class="mavlink_type" valign="top">512</td>
     <td class="mavlink_name" valign="top">MAV_PROTOCOL_CAPABILITY_TERRAIN</td>
     <td class="mavlink_comment">Autopilot supports terrain protocol / data handling.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PROTOCOL_CAPABILITY_SET_ACTUATOR_TARGET">
     <td class="mavlink_type" valign="top">1024</td>
     <td class="mavlink_name" valign="top">MAV_PROTOCOL_CAPABILITY_SET_ACTUATOR_TARGET</td>
     <td class="mavlink_comment">Autopilot supports direct actuator control.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PROTOCOL_CAPABILITY_FLIGHT_TERMINATION">
     <td class="mavlink_type" valign="top">2048</td>
     <td class="mavlink_name" valign="top">MAV_PROTOCOL_CAPABILITY_FLIGHT_TERMINATION</td>
     <td class="mavlink_comment">Autopilot supports the flight termination command.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PROTOCOL_CAPABILITY_COMPASS_CALIBRATION">
     <td class="mavlink_type" valign="top">4096</td>
     <td class="mavlink_name" valign="top">MAV_PROTOCOL_CAPABILITY_COMPASS_CALIBRATION</td>
     <td class="mavlink_comment">Autopilot supports onboard compass calibration.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PROTOCOL_CAPABILITY_MAVLINK2">
     <td class="mavlink_type" valign="top">8192</td>
     <td class="mavlink_name" valign="top">MAV_PROTOCOL_CAPABILITY_MAVLINK2</td>
     <td class="mavlink_comment">Autopilot supports mavlink version 2.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PROTOCOL_CAPABILITY_MISSION_FENCE">
     <td class="mavlink_type" valign="top">16384</td>
     <td class="mavlink_name" valign="top">MAV_PROTOCOL_CAPABILITY_MISSION_FENCE</td>
     <td class="mavlink_comment">Autopilot supports mission fence protocol.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PROTOCOL_CAPABILITY_MISSION_RALLY">
     <td class="mavlink_type" valign="top">32768</td>
     <td class="mavlink_name" valign="top">MAV_PROTOCOL_CAPABILITY_MISSION_RALLY</td>
     <td class="mavlink_comment">Autopilot supports mission rally point protocol.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_PROTOCOL_CAPABILITY_FLIGHT_INFORMATION">
     <td class="mavlink_type" valign="top">65536</td>
     <td class="mavlink_name" valign="top">MAV_PROTOCOL_CAPABILITY_FLIGHT_INFORMATION</td>
     <td class="mavlink_comment">Autopilot supports the flight information protocol.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_MISSION_TYPE" name="ENUM_MAV_MISSION_TYPE">MAV_MISSION_TYPE</h2>
  <p class="description">Type of mission items being requested/sent in mission protocol.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_MISSION_TYPE_MISSION">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_TYPE_MISSION</td>
     <td class="mavlink_comment">Items are mission commands for main mission.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MISSION_TYPE_FENCE">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_TYPE_FENCE</td>
     <td class="mavlink_comment">Specifies GeoFence area(s). Items are MAV_CMD_FENCE_ GeoFence items.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MISSION_TYPE_RALLY">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_TYPE_RALLY</td>
     <td class="mavlink_comment">Specifies the rally points for the vehicle. Rally points are alternative RTL points. Items are MAV_CMD_RALLY_POINT rally point items.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MISSION_TYPE_ALL">
     <td class="mavlink_type" valign="top">255</td>
     <td class="mavlink_name" valign="top">MAV_MISSION_TYPE_ALL</td>
     <td class="mavlink_comment">Only used in MISSION_CLEAR_ALL to clear all mission types.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_ESTIMATOR_TYPE" name="ENUM_MAV_ESTIMATOR_TYPE">MAV_ESTIMATOR_TYPE</h2>
  <p class="description">Enumeration of estimator types</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_ESTIMATOR_TYPE_NAIVE">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_ESTIMATOR_TYPE_NAIVE</td>
     <td class="mavlink_comment">This is a naive estimator without any real covariance feedback.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_ESTIMATOR_TYPE_VISION">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_ESTIMATOR_TYPE_VISION</td>
     <td class="mavlink_comment">Computer vision based estimate. Might be up to scale.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_ESTIMATOR_TYPE_VIO">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_ESTIMATOR_TYPE_VIO</td>
     <td class="mavlink_comment">Visual-inertial estimate.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_ESTIMATOR_TYPE_GPS">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_ESTIMATOR_TYPE_GPS</td>
     <td class="mavlink_comment">Plain GPS estimate.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_ESTIMATOR_TYPE_GPS_INS">
     <td class="mavlink_type" valign="top">5</td>
     <td class="mavlink_name" valign="top">MAV_ESTIMATOR_TYPE_GPS_INS</td>
     <td class="mavlink_comment">Estimator integrating GPS and inertial sensing.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_BATTERY_TYPE" name="ENUM_MAV_BATTERY_TYPE">MAV_BATTERY_TYPE</h2>
  <p class="description">Enumeration of battery types</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_BATTERY_TYPE_UNKNOWN">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_BATTERY_TYPE_UNKNOWN</td>
     <td class="mavlink_comment">Not specified.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_BATTERY_TYPE_LIPO">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_BATTERY_TYPE_LIPO</td>
     <td class="mavlink_comment">Lithium polymer battery</td>
    </tr>
    <tr class="mavlink_field" id="MAV_BATTERY_TYPE_LIFE">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_BATTERY_TYPE_LIFE</td>
     <td class="mavlink_comment">Lithium-iron-phosphate battery</td>
    </tr>
    <tr class="mavlink_field" id="MAV_BATTERY_TYPE_LION">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_BATTERY_TYPE_LION</td>
     <td class="mavlink_comment">Lithium-ION battery</td>
    </tr>
    <tr class="mavlink_field" id="MAV_BATTERY_TYPE_NIMH">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_BATTERY_TYPE_NIMH</td>
     <td class="mavlink_comment">Nickel metal hydride battery</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_BATTERY_FUNCTION" name="ENUM_MAV_BATTERY_FUNCTION">MAV_BATTERY_FUNCTION</h2>
  <p class="description">Enumeration of battery functions</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_BATTERY_FUNCTION_UNKNOWN">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_BATTERY_FUNCTION_UNKNOWN</td>
     <td class="mavlink_comment">Battery function is unknown</td>
    </tr>
    <tr class="mavlink_field" id="MAV_BATTERY_FUNCTION_ALL">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_BATTERY_FUNCTION_ALL</td>
     <td class="mavlink_comment">Battery supports all flight systems</td>
    </tr>
    <tr class="mavlink_field" id="MAV_BATTERY_FUNCTION_PROPULSION">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_BATTERY_FUNCTION_PROPULSION</td>
     <td class="mavlink_comment">Battery for the propulsion system</td>
    </tr>
    <tr class="mavlink_field" id="MAV_BATTERY_FUNCTION_AVIONICS">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_BATTERY_FUNCTION_AVIONICS</td>
     <td class="mavlink_comment">Avionics battery</td>
    </tr>
    <tr class="mavlink_field" id="MAV_BATTERY_TYPE_PAYLOAD">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_BATTERY_TYPE_PAYLOAD</td>
     <td class="mavlink_comment">Payload battery</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_VTOL_STATE" name="ENUM_MAV_VTOL_STATE">MAV_VTOL_STATE</h2>
  <p class="description">Enumeration of VTOL states</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_VTOL_STATE_UNDEFINED">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_VTOL_STATE_UNDEFINED</td>
     <td class="mavlink_comment">MAV is not configured as VTOL</td>
    </tr>
    <tr class="mavlink_field" id="MAV_VTOL_STATE_TRANSITION_TO_FW">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_VTOL_STATE_TRANSITION_TO_FW</td>
     <td class="mavlink_comment">VTOL is in transition from multicopter to fixed-wing</td>
    </tr>
    <tr class="mavlink_field" id="MAV_VTOL_STATE_TRANSITION_TO_MC">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_VTOL_STATE_TRANSITION_TO_MC</td>
     <td class="mavlink_comment">VTOL is in transition from fixed-wing to multicopter</td>
    </tr>
    <tr class="mavlink_field" id="MAV_VTOL_STATE_MC">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_VTOL_STATE_MC</td>
     <td class="mavlink_comment">VTOL is in multicopter state</td>
    </tr>
    <tr class="mavlink_field" id="MAV_VTOL_STATE_FW">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_VTOL_STATE_FW</td>
     <td class="mavlink_comment">VTOL is in fixed-wing state</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_LANDED_STATE" name="ENUM_MAV_LANDED_STATE">MAV_LANDED_STATE</h2>
  <p class="description">Enumeration of landed detector states</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_LANDED_STATE_UNDEFINED">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_LANDED_STATE_UNDEFINED</td>
     <td class="mavlink_comment">MAV landed state is unknown</td>
    </tr>
    <tr class="mavlink_field" id="MAV_LANDED_STATE_ON_GROUND">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_LANDED_STATE_ON_GROUND</td>
     <td class="mavlink_comment">MAV is landed (on ground)</td>
    </tr>
    <tr class="mavlink_field" id="MAV_LANDED_STATE_IN_AIR">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_LANDED_STATE_IN_AIR</td>
     <td class="mavlink_comment">MAV is in air</td>
    </tr>
    <tr class="mavlink_field" id="MAV_LANDED_STATE_TAKEOFF">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_LANDED_STATE_TAKEOFF</td>
     <td class="mavlink_comment">MAV currently taking off</td>
    </tr>
    <tr class="mavlink_field" id="MAV_LANDED_STATE_LANDING">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_LANDED_STATE_LANDING</td>
     <td class="mavlink_comment">MAV currently landing</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="ADSB_ALTITUDE_TYPE" name="ENUM_ADSB_ALTITUDE_TYPE">ADSB_ALTITUDE_TYPE</h2>
  <p class="description">Enumeration of the ADSB altimeter types</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="ADSB_ALTITUDE_TYPE_PRESSURE_QNH">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">ADSB_ALTITUDE_TYPE_PRESSURE_QNH</td>
     <td class="mavlink_comment">Altitude reported from a Baro source using QNH reference</td>
    </tr>
    <tr class="mavlink_field" id="ADSB_ALTITUDE_TYPE_GEOMETRIC">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">ADSB_ALTITUDE_TYPE_GEOMETRIC</td>
     <td class="mavlink_comment">Altitude reported from a GNSS source</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="ADSB_EMITTER_TYPE" name="ENUM_ADSB_EMITTER_TYPE">ADSB_EMITTER_TYPE</h2>
  <p class="description">ADSB classification for the type of vehicle emitting the transponder signal</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_NO_INFO">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_NO_INFO</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_LIGHT">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_LIGHT</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_SMALL">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_SMALL</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_LARGE">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_LARGE</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_HIGH_VORTEX_LARGE">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_HIGH_VORTEX_LARGE</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_HEAVY">
     <td class="mavlink_type" valign="top">5</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_HEAVY</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_HIGHLY_MANUV">
     <td class="mavlink_type" valign="top">6</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_HIGHLY_MANUV</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_ROTOCRAFT">
     <td class="mavlink_type" valign="top">7</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_ROTOCRAFT</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_UNASSIGNED">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_UNASSIGNED</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_GLIDER">
     <td class="mavlink_type" valign="top">9</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_GLIDER</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_LIGHTER_AIR">
     <td class="mavlink_type" valign="top">10</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_LIGHTER_AIR</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_PARACHUTE">
     <td class="mavlink_type" valign="top">11</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_PARACHUTE</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_ULTRA_LIGHT">
     <td class="mavlink_type" valign="top">12</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_ULTRA_LIGHT</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_UNASSIGNED2">
     <td class="mavlink_type" valign="top">13</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_UNASSIGNED2</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_UAV">
     <td class="mavlink_type" valign="top">14</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_UAV</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_SPACE">
     <td class="mavlink_type" valign="top">15</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_SPACE</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_UNASSGINED3">
     <td class="mavlink_type" valign="top">16</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_UNASSGINED3</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_EMERGENCY_SURFACE">
     <td class="mavlink_type" valign="top">17</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_EMERGENCY_SURFACE</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_SERVICE_SURFACE">
     <td class="mavlink_type" valign="top">18</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_SERVICE_SURFACE</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_EMITTER_TYPE_POINT_OBSTACLE">
     <td class="mavlink_type" valign="top">19</td>
     <td class="mavlink_name" valign="top">ADSB_EMITTER_TYPE_POINT_OBSTACLE</td>
     <td class="mavlink_comment">
     </td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="ADSB_FLAGS" name="ENUM_ADSB_FLAGS">ADSB_FLAGS</h2>
  <p class="description">These flags indicate status such as data validity of each data source. Set = data valid</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="ADSB_FLAGS_VALID_COORDS">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">ADSB_FLAGS_VALID_COORDS</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_FLAGS_VALID_ALTITUDE">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">ADSB_FLAGS_VALID_ALTITUDE</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_FLAGS_VALID_HEADING">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">ADSB_FLAGS_VALID_HEADING</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_FLAGS_VALID_VELOCITY">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">ADSB_FLAGS_VALID_VELOCITY</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_FLAGS_VALID_CALLSIGN">
     <td class="mavlink_type" valign="top">16</td>
     <td class="mavlink_name" valign="top">ADSB_FLAGS_VALID_CALLSIGN</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_FLAGS_VALID_SQUAWK">
     <td class="mavlink_type" valign="top">32</td>
     <td class="mavlink_name" valign="top">ADSB_FLAGS_VALID_SQUAWK</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="ADSB_FLAGS_SIMULATED">
     <td class="mavlink_type" valign="top">64</td>
     <td class="mavlink_name" valign="top">ADSB_FLAGS_SIMULATED</td>
     <td class="mavlink_comment">
     </td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_DO_REPOSITION_FLAGS" name="ENUM_MAV_DO_REPOSITION_FLAGS">MAV_DO_REPOSITION_FLAGS</h2>
  <p class="description">Bitmask of options for the MAV_CMD_DO_REPOSITION</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_DO_REPOSITION_FLAGS_CHANGE_MODE">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_DO_REPOSITION_FLAGS_CHANGE_MODE</td>
     <td class="mavlink_comment">The aircraft should immediately transition into guided. This should not be set for follow me applications</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="ESTIMATOR_STATUS_FLAGS" name="ENUM_ESTIMATOR_STATUS_FLAGS">ESTIMATOR_STATUS_FLAGS</h2>
  <p class="description">Flags in EKF_STATUS message</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="ESTIMATOR_ATTITUDE">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">ESTIMATOR_ATTITUDE</td>
     <td class="mavlink_comment">True if the attitude estimate is good</td>
    </tr>
    <tr class="mavlink_field" id="ESTIMATOR_VELOCITY_HORIZ">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">ESTIMATOR_VELOCITY_HORIZ</td>
     <td class="mavlink_comment">True if the horizontal velocity estimate is good</td>
    </tr>
    <tr class="mavlink_field" id="ESTIMATOR_VELOCITY_VERT">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">ESTIMATOR_VELOCITY_VERT</td>
     <td class="mavlink_comment">True if the  vertical velocity estimate is good</td>
    </tr>
    <tr class="mavlink_field" id="ESTIMATOR_POS_HORIZ_REL">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">ESTIMATOR_POS_HORIZ_REL</td>
     <td class="mavlink_comment">True if the horizontal position (relative) estimate is good</td>
    </tr>
    <tr class="mavlink_field" id="ESTIMATOR_POS_HORIZ_ABS">
     <td class="mavlink_type" valign="top">16</td>
     <td class="mavlink_name" valign="top">ESTIMATOR_POS_HORIZ_ABS</td>
     <td class="mavlink_comment">True if the horizontal position (absolute) estimate is good</td>
    </tr>
    <tr class="mavlink_field" id="ESTIMATOR_POS_VERT_ABS">
     <td class="mavlink_type" valign="top">32</td>
     <td class="mavlink_name" valign="top">ESTIMATOR_POS_VERT_ABS</td>
     <td class="mavlink_comment">True if the vertical position (absolute) estimate is good</td>
    </tr>
    <tr class="mavlink_field" id="ESTIMATOR_POS_VERT_AGL">
     <td class="mavlink_type" valign="top">64</td>
     <td class="mavlink_name" valign="top">ESTIMATOR_POS_VERT_AGL</td>
     <td class="mavlink_comment">True if the vertical position (above ground) estimate is good</td>
    </tr>
    <tr class="mavlink_field" id="ESTIMATOR_CONST_POS_MODE">
     <td class="mavlink_type" valign="top">128</td>
     <td class="mavlink_name" valign="top">ESTIMATOR_CONST_POS_MODE</td>
     <td class="mavlink_comment">True if the EKF is in a constant position mode and is not using external measurements (eg GPS or optical flow)</td>
    </tr>
    <tr class="mavlink_field" id="ESTIMATOR_PRED_POS_HORIZ_REL">
     <td class="mavlink_type" valign="top">256</td>
     <td class="mavlink_name" valign="top">ESTIMATOR_PRED_POS_HORIZ_REL</td>
     <td class="mavlink_comment">True if the EKF has sufficient data to enter a mode that will provide a (relative) position estimate</td>
    </tr>
    <tr class="mavlink_field" id="ESTIMATOR_PRED_POS_HORIZ_ABS">
     <td class="mavlink_type" valign="top">512</td>
     <td class="mavlink_name" valign="top">ESTIMATOR_PRED_POS_HORIZ_ABS</td>
     <td class="mavlink_comment">True if the EKF has sufficient data to enter a mode that will provide a (absolute) position estimate</td>
    </tr>
    <tr class="mavlink_field" id="ESTIMATOR_GPS_GLITCH">
     <td class="mavlink_type" valign="top">1024</td>
     <td class="mavlink_name" valign="top">ESTIMATOR_GPS_GLITCH</td>
     <td class="mavlink_comment">True if the EKF has detected a GPS glitch</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MOTOR_TEST_THROTTLE_TYPE" name="ENUM_MOTOR_TEST_THROTTLE_TYPE">MOTOR_TEST_THROTTLE_TYPE</h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MOTOR_TEST_THROTTLE_PERCENT">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MOTOR_TEST_THROTTLE_PERCENT</td>
     <td class="mavlink_comment">throttle as a percentage from 0 ~ 100</td>
    </tr>
    <tr class="mavlink_field" id="MOTOR_TEST_THROTTLE_PWM">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MOTOR_TEST_THROTTLE_PWM</td>
     <td class="mavlink_comment">throttle as an absolute PWM value (normally in range of 1000~2000)</td>
    </tr>
    <tr class="mavlink_field" id="MOTOR_TEST_THROTTLE_PILOT">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MOTOR_TEST_THROTTLE_PILOT</td>
     <td class="mavlink_comment">throttle pass-through from pilot's transmitter</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="GPS_INPUT_IGNORE_FLAGS" name="ENUM_GPS_INPUT_IGNORE_FLAGS">GPS_INPUT_IGNORE_FLAGS</h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="GPS_INPUT_IGNORE_FLAG_ALT">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">GPS_INPUT_IGNORE_FLAG_ALT</td>
     <td class="mavlink_comment">ignore altitude field</td>
    </tr>
    <tr class="mavlink_field" id="GPS_INPUT_IGNORE_FLAG_HDOP">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">GPS_INPUT_IGNORE_FLAG_HDOP</td>
     <td class="mavlink_comment">ignore hdop field</td>
    </tr>
    <tr class="mavlink_field" id="GPS_INPUT_IGNORE_FLAG_VDOP">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">GPS_INPUT_IGNORE_FLAG_VDOP</td>
     <td class="mavlink_comment">ignore vdop field</td>
    </tr>
    <tr class="mavlink_field" id="GPS_INPUT_IGNORE_FLAG_VEL_HORIZ">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">GPS_INPUT_IGNORE_FLAG_VEL_HORIZ</td>
     <td class="mavlink_comment">ignore horizontal velocity field (vn and ve)</td>
    </tr>
    <tr class="mavlink_field" id="GPS_INPUT_IGNORE_FLAG_VEL_VERT">
     <td class="mavlink_type" valign="top">16</td>
     <td class="mavlink_name" valign="top">GPS_INPUT_IGNORE_FLAG_VEL_VERT</td>
     <td class="mavlink_comment">ignore vertical velocity field (vd)</td>
    </tr>
    <tr class="mavlink_field" id="GPS_INPUT_IGNORE_FLAG_SPEED_ACCURACY">
     <td class="mavlink_type" valign="top">32</td>
     <td class="mavlink_name" valign="top">GPS_INPUT_IGNORE_FLAG_SPEED_ACCURACY</td>
     <td class="mavlink_comment">ignore speed accuracy field</td>
    </tr>
    <tr class="mavlink_field" id="GPS_INPUT_IGNORE_FLAG_HORIZONTAL_ACCURACY">
     <td class="mavlink_type" valign="top">64</td>
     <td class="mavlink_name" valign="top">GPS_INPUT_IGNORE_FLAG_HORIZONTAL_ACCURACY</td>
     <td class="mavlink_comment">ignore horizontal accuracy field</td>
    </tr>
    <tr class="mavlink_field" id="GPS_INPUT_IGNORE_FLAG_VERTICAL_ACCURACY">
     <td class="mavlink_type" valign="top">128</td>
     <td class="mavlink_name" valign="top">GPS_INPUT_IGNORE_FLAG_VERTICAL_ACCURACY</td>
     <td class="mavlink_comment">ignore vertical accuracy field</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_COLLISION_ACTION" name="ENUM_MAV_COLLISION_ACTION">MAV_COLLISION_ACTION</h2>
  <p class="description">Possible actions an aircraft can take to avoid a collision.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_COLLISION_ACTION_NONE">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_COLLISION_ACTION_NONE</td>
     <td class="mavlink_comment">Ignore any potential collisions</td>
    </tr>
    <tr class="mavlink_field" id="MAV_COLLISION_ACTION_REPORT">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_COLLISION_ACTION_REPORT</td>
     <td class="mavlink_comment">Report potential collision</td>
    </tr>
    <tr class="mavlink_field" id="MAV_COLLISION_ACTION_ASCEND_OR_DESCEND">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_COLLISION_ACTION_ASCEND_OR_DESCEND</td>
     <td class="mavlink_comment">Ascend or Descend to avoid threat</td>
    </tr>
    <tr class="mavlink_field" id="MAV_COLLISION_ACTION_MOVE_HORIZONTALLY">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_COLLISION_ACTION_MOVE_HORIZONTALLY</td>
     <td class="mavlink_comment">Move horizontally to avoid threat</td>
    </tr>
    <tr class="mavlink_field" id="MAV_COLLISION_ACTION_MOVE_PERPENDICULAR">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_COLLISION_ACTION_MOVE_PERPENDICULAR</td>
     <td class="mavlink_comment">Aircraft to move perpendicular to the collision's velocity vector</td>
    </tr>
    <tr class="mavlink_field" id="MAV_COLLISION_ACTION_RTL">
     <td class="mavlink_type" valign="top">5</td>
     <td class="mavlink_name" valign="top">MAV_COLLISION_ACTION_RTL</td>
     <td class="mavlink_comment">Aircraft to fly directly back to its launch point</td>
    </tr>
    <tr class="mavlink_field" id="MAV_COLLISION_ACTION_HOVER">
     <td class="mavlink_type" valign="top">6</td>
     <td class="mavlink_name" valign="top">MAV_COLLISION_ACTION_HOVER</td>
     <td class="mavlink_comment">Aircraft to stop in place</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_COLLISION_THREAT_LEVEL" name="ENUM_MAV_COLLISION_THREAT_LEVEL">MAV_COLLISION_THREAT_LEVEL</h2>
  <p class="description">Aircraft-rated danger from this threat.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_COLLISION_THREAT_LEVEL_NONE">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_COLLISION_THREAT_LEVEL_NONE</td>
     <td class="mavlink_comment">Not a threat</td>
    </tr>
    <tr class="mavlink_field" id="MAV_COLLISION_THREAT_LEVEL_LOW">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_COLLISION_THREAT_LEVEL_LOW</td>
     <td class="mavlink_comment">Craft is mildly concerned about this threat</td>
    </tr>
    <tr class="mavlink_field" id="MAV_COLLISION_THREAT_LEVEL_HIGH">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_COLLISION_THREAT_LEVEL_HIGH</td>
     <td class="mavlink_comment">Craft is panicing, and may take actions to avoid threat</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_COLLISION_SRC" name="ENUM_MAV_COLLISION_SRC">MAV_COLLISION_SRC</h2>
  <p class="description">Source of information about this collision.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_COLLISION_SRC_ADSB">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_COLLISION_SRC_ADSB</td>
     <td class="mavlink_comment">ID field references ADSB_VEHICLE packets</td>
    </tr>
    <tr class="mavlink_field" id="MAV_COLLISION_SRC_MAVLINK_GPS_GLOBAL_INT">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_COLLISION_SRC_MAVLINK_GPS_GLOBAL_INT</td>
     <td class="mavlink_comment">ID field references MAVLink SRC ID</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="GPS_FIX_TYPE" name="ENUM_GPS_FIX_TYPE">GPS_FIX_TYPE</h2>
  <p class="description">Type of GPS fix</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="GPS_FIX_TYPE_NO_GPS">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">GPS_FIX_TYPE_NO_GPS</td>
     <td class="mavlink_comment">No GPS connected</td>
    </tr>
    <tr class="mavlink_field" id="GPS_FIX_TYPE_NO_FIX">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">GPS_FIX_TYPE_NO_FIX</td>
     <td class="mavlink_comment">No position information, GPS is connected</td>
    </tr>
    <tr class="mavlink_field" id="GPS_FIX_TYPE_2D_FIX">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">GPS_FIX_TYPE_2D_FIX</td>
     <td class="mavlink_comment">2D position</td>
    </tr>
    <tr class="mavlink_field" id="GPS_FIX_TYPE_3D_FIX">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">GPS_FIX_TYPE_3D_FIX</td>
     <td class="mavlink_comment">3D position</td>
    </tr>
    <tr class="mavlink_field" id="GPS_FIX_TYPE_DGPS">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">GPS_FIX_TYPE_DGPS</td>
     <td class="mavlink_comment">DGPS/SBAS aided 3D position</td>
    </tr>
    <tr class="mavlink_field" id="GPS_FIX_TYPE_RTK_FLOAT">
     <td class="mavlink_type" valign="top">5</td>
     <td class="mavlink_name" valign="top">GPS_FIX_TYPE_RTK_FLOAT</td>
     <td class="mavlink_comment">RTK float, 3D position</td>
    </tr>
    <tr class="mavlink_field" id="GPS_FIX_TYPE_RTK_FIXED">
     <td class="mavlink_type" valign="top">6</td>
     <td class="mavlink_name" valign="top">GPS_FIX_TYPE_RTK_FIXED</td>
     <td class="mavlink_comment">RTK Fixed, 3D position</td>
    </tr>
    <tr class="mavlink_field" id="GPS_FIX_TYPE_STATIC">
     <td class="mavlink_type" valign="top">7</td>
     <td class="mavlink_name" valign="top">GPS_FIX_TYPE_STATIC</td>
     <td class="mavlink_comment">Static fixed, typically used for base stations</td>
    </tr>
    <tr class="mavlink_field" id="GPS_FIX_TYPE_PPP">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">GPS_FIX_TYPE_PPP</td>
     <td class="mavlink_comment">PPP, 3D position.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="LANDING_TARGET_TYPE" name="ENUM_LANDING_TARGET_TYPE">LANDING_TARGET_TYPE</h2>
  <p class="description">Type of landing target</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="LANDING_TARGET_TYPE_LIGHT_BEACON">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">LANDING_TARGET_TYPE_LIGHT_BEACON</td>
     <td class="mavlink_comment">Landing target signaled by light beacon (ex: IR-LOCK)</td>
    </tr>
    <tr class="mavlink_field" id="LANDING_TARGET_TYPE_RADIO_BEACON">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">LANDING_TARGET_TYPE_RADIO_BEACON</td>
     <td class="mavlink_comment">Landing target signaled by radio beacon (ex: ILS, NDB)</td>
    </tr>
    <tr class="mavlink_field" id="LANDING_TARGET_TYPE_VISION_FIDUCIAL">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">LANDING_TARGET_TYPE_VISION_FIDUCIAL</td>
     <td class="mavlink_comment">Landing target represented by a fiducial marker (ex: ARTag)</td>
    </tr>
    <tr class="mavlink_field" id="LANDING_TARGET_TYPE_VISION_OTHER">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">LANDING_TARGET_TYPE_VISION_OTHER</td>
     <td class="mavlink_comment">Landing target represented by a pre-defined visual shape/feature (ex: X-marker, H-marker, square)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="VTOL_TRANSITION_HEADING" name="ENUM_VTOL_TRANSITION_HEADING">VTOL_TRANSITION_HEADING</h2>
  <p class="description">Direction of VTOL transition</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="VTOL_TRANSITION_HEADING_VEHICLE_DEFAULT">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">VTOL_TRANSITION_HEADING_VEHICLE_DEFAULT</td>
     <td class="mavlink_comment">Respect the heading configuration of the vehicle.</td>
    </tr>
    <tr class="mavlink_field" id="VTOL_TRANSITION_HEADING_NEXT_WAYPOINT">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">VTOL_TRANSITION_HEADING_NEXT_WAYPOINT</td>
     <td class="mavlink_comment">Use the heading pointing towards the next waypoint.</td>
    </tr>
    <tr class="mavlink_field" id="VTOL_TRANSITION_HEADING_TAKEOFF">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">VTOL_TRANSITION_HEADING_TAKEOFF</td>
     <td class="mavlink_comment">Use the heading on takeoff (while sitting on the ground).</td>
    </tr>
    <tr class="mavlink_field" id="VTOL_TRANSITION_HEADING_SPECIFIED">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">VTOL_TRANSITION_HEADING_SPECIFIED</td>
     <td class="mavlink_comment">Use the specified heading in parameter 4.</td>
    </tr>
    <tr class="mavlink_field" id="VTOL_TRANSITION_HEADING_ANY">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">VTOL_TRANSITION_HEADING_ANY</td>
     <td class="mavlink_comment">Use the current heading when reaching takeoff altitude (potentially facing the wind when weather-vaning is active).</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="CAMERA_CAP_FLAGS" name="ENUM_CAMERA_CAP_FLAGS">CAMERA_CAP_FLAGS</h2>
  <p class="description">Camera capability flags (Bitmap).</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="CAMERA_CAP_FLAGS_CAPTURE_VIDEO">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">CAMERA_CAP_FLAGS_CAPTURE_VIDEO</td>
     <td class="mavlink_comment">Camera is able to record video.</td>
    </tr>
    <tr class="mavlink_field" id="CAMERA_CAP_FLAGS_CAPTURE_IMAGE">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">CAMERA_CAP_FLAGS_CAPTURE_IMAGE</td>
     <td class="mavlink_comment">Camera is able to capture images.</td>
    </tr>
    <tr class="mavlink_field" id="CAMERA_CAP_FLAGS_HAS_MODES">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">CAMERA_CAP_FLAGS_HAS_MODES</td>
     <td class="mavlink_comment">Camera has separate Video and Image/Photo modes (MAV_CMD_SET_CAMERA_MODE)</td>
    </tr>
    <tr class="mavlink_field" id="CAMERA_CAP_FLAGS_CAN_CAPTURE_IMAGE_IN_VIDEO_MODE">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">CAMERA_CAP_FLAGS_CAN_CAPTURE_IMAGE_IN_VIDEO_MODE</td>
     <td class="mavlink_comment">Camera can capture images while in video mode</td>
    </tr>
    <tr class="mavlink_field" id="CAMERA_CAP_FLAGS_CAN_CAPTURE_VIDEO_IN_IMAGE_MODE">
     <td class="mavlink_type" valign="top">16</td>
     <td class="mavlink_name" valign="top">CAMERA_CAP_FLAGS_CAN_CAPTURE_VIDEO_IN_IMAGE_MODE</td>
     <td class="mavlink_comment">Camera can capture videos while in Photo/Image mode</td>
    </tr>
    <tr class="mavlink_field" id="CAMERA_CAP_FLAGS_HAS_IMAGE_SURVEY_MODE">
     <td class="mavlink_type" valign="top">32</td>
     <td class="mavlink_name" valign="top">CAMERA_CAP_FLAGS_HAS_IMAGE_SURVEY_MODE</td>
     <td class="mavlink_comment">Camera has image survey mode (MAV_CMD_SET_CAMERA_MODE)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="PARAM_ACK" name="ENUM_PARAM_ACK">PARAM_ACK</h2>
  <p class="description">Result from a PARAM_EXT_SET message.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="PARAM_ACK_ACCEPTED">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">PARAM_ACK_ACCEPTED</td>
     <td class="mavlink_comment">Parameter value ACCEPTED and SET</td>
    </tr>
    <tr class="mavlink_field" id="PARAM_ACK_VALUE_UNSUPPORTED">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">PARAM_ACK_VALUE_UNSUPPORTED</td>
     <td class="mavlink_comment">Parameter value UNKNOWN/UNSUPPORTED</td>
    </tr>
    <tr class="mavlink_field" id="PARAM_ACK_FAILED">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">PARAM_ACK_FAILED</td>
     <td class="mavlink_comment">Parameter failed to set</td>
    </tr>
    <tr class="mavlink_field" id="PARAM_ACK_IN_PROGRESS">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">PARAM_ACK_IN_PROGRESS</td>
     <td class="mavlink_comment">Parameter value received but not yet validated or set. A subsequent PARAM_EXT_ACK will follow once operation is completed with the actual result. These are for parameters that may take longer to set. Instead of waiting for an ACK and potentially timing out, you will immediately receive this response to let you know it was received.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="CAMERA_MODE" name="ENUM_CAMERA_MODE">CAMERA_MODE</h2>
  <p class="description">Camera Modes.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="CAMERA_MODE_IMAGE">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">CAMERA_MODE_IMAGE</td>
     <td class="mavlink_comment">Camera is in image/photo capture mode.</td>
    </tr>
    <tr class="mavlink_field" id="CAMERA_MODE_VIDEO">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">CAMERA_MODE_VIDEO</td>
     <td class="mavlink_comment">Camera is in video capture mode.</td>
    </tr>
    <tr class="mavlink_field" id="CAMERA_MODE_IMAGE_SURVEY">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">CAMERA_MODE_IMAGE_SURVEY</td>
     <td class="mavlink_comment">Camera is in image survey capture mode. It allows for camera controller to do specific settings for surveys.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_ARM_AUTH_DENIED_REASON" name="ENUM_MAV_ARM_AUTH_DENIED_REASON">MAV_ARM_AUTH_DENIED_REASON</h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_ARM_AUTH_DENIED_REASON_GENERIC">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_ARM_AUTH_DENIED_REASON_GENERIC</td>
     <td class="mavlink_comment">Not a specific reason</td>
    </tr>
    <tr class="mavlink_field" id="MAV_ARM_AUTH_DENIED_REASON_NONE">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_ARM_AUTH_DENIED_REASON_NONE</td>
     <td class="mavlink_comment">Authorizer will send the error as string to GCS</td>
    </tr>
    <tr class="mavlink_field" id="MAV_ARM_AUTH_DENIED_REASON_INVALID_WAYPOINT">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_ARM_AUTH_DENIED_REASON_INVALID_WAYPOINT</td>
     <td class="mavlink_comment">At least one waypoint have a invalid value</td>
    </tr>
    <tr class="mavlink_field" id="MAV_ARM_AUTH_DENIED_REASON_TIMEOUT">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_ARM_AUTH_DENIED_REASON_TIMEOUT</td>
     <td class="mavlink_comment">Timeout in the authorizer process(in case it depends on network)</td>
    </tr>
    <tr class="mavlink_field" id="MAV_ARM_AUTH_DENIED_REASON_AIRSPACE_IN_USE">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_ARM_AUTH_DENIED_REASON_AIRSPACE_IN_USE</td>
     <td class="mavlink_comment">Airspace of the mission in use by another vehicle, second result parameter can have the waypoint id that caused it to be denied.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_ARM_AUTH_DENIED_REASON_BAD_WEATHER">
     <td class="mavlink_type" valign="top">5</td>
     <td class="mavlink_name" valign="top">MAV_ARM_AUTH_DENIED_REASON_BAD_WEATHER</td>
     <td class="mavlink_comment">Weather is not good to fly</td>
    </tr>
   </tbody>
  </table>
  <h1>MAVLink Messages</h1>
  <h2 class="mavlink_message_name" id="HEARTBEAT" name="HEARTBEAT">HEARTBEAT (<a href="
      #HEARTBEAT">
    #0
   </a>
   )
  </h2>
  <p class="description">The heartbeat message shows that a system is present and responding. The type of the MAV and Autopilot hardware allow the receiving system to treat further messages from this system appropriate (e.g. by laying out the user interface based on the autopilot).</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Type of the MAV (quadrotor, helicopter, etc., up to 15 types, defined in MAV_TYPE ENUM)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">autopilot</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Autopilot type / class. defined in MAV_AUTOPILOT ENUM</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">base_mode</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System mode bitfield, see MAV_MODE_FLAG ENUM in mavlink/include/mavlink_types.h</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">custom_mode</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">A bitfield for use for autopilot-specific flags.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">system_status</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System status flag, see MAV_STATE ENUM</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mavlink_version</td>
     <td class="mavlink_type" valign="top">uint8_t_mavlink_version</td>
     <td class="mavlink_comment">MAVLink version, not writable by user, gets added by protocol because of magic data type: uint8_t_mavlink_version</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SYS_STATUS" name="SYS_STATUS">SYS_STATUS (<a href="
      #SYS_STATUS">
    #1
   </a>
   )
  </h2>
  <p class="description">The general system state. If the system is following the MAVLink standard, the system state is mainly defined by three orthogonal states/modes: The system mode, which is either LOCKED (motors shut down and locked), MANUAL (system under RC control), GUIDED (system with autonomous position control, position setpoint controlled manually) or AUTO (system guided by path/waypoint planner). The NAV_MODE defined the current flight state: LIFTOFF (often an open-loop maneuver), LANDING, WAYPOINTS or VECTOR. This represents the internal navigation state machine. The system status shows whether the system is currently active or not and if an emergency occured. During the CRITICAL and EMERGENCY states the MAV is still considered to be active, but should start emergency procedures autonomously. After a failure occured it should first move from active to critical to allow manual intervention and then move to emergency after a certain timeout.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">onboard_control_sensors_present</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Bitmask showing which onboard controllers and sensors are present. Value of 0: not present. Value of 1: present. Indices defined by ENUM MAV_SYS_STATUS_SENSOR</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">onboard_control_sensors_enabled</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Bitmask showing which onboard controllers and sensors are enabled:  Value of 0: not enabled. Value of 1: enabled. Indices defined by ENUM MAV_SYS_STATUS_SENSOR</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">onboard_control_sensors_health</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Bitmask showing which onboard controllers and sensors are operational or have an error:  Value of 0: not enabled. Value of 1: enabled. Indices defined by ENUM MAV_SYS_STATUS_SENSOR</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">load</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Maximum usage in percent of the mainloop time, (0%: 0, 100%: 1000) should be always below 1000</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">voltage_battery</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Battery voltage, in millivolts (1 = 1 millivolt)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">current_battery</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Battery current, in 10*milliamperes (1 = 10 milliampere), -1: autopilot does not measure the current</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">battery_remaining</td>
     <td class="mavlink_type" valign="top">int8_t</td>
     <td class="mavlink_comment">Remaining battery energy: (0%: 0, 100%: 100), -1: autopilot estimate the remaining battery</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">drop_rate_comm</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Communication drops in percent, (0%: 0, 100%: 10'000), (UART, I2C, SPI, CAN), dropped packets on all links (packets that were corrupted on reception on the MAV)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">errors_comm</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Communication errors (UART, I2C, SPI, CAN), dropped packets on all links (packets that were corrupted on reception on the MAV)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">errors_count1</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Autopilot-specific errors</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">errors_count2</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Autopilot-specific errors</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">errors_count3</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Autopilot-specific errors</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">errors_count4</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Autopilot-specific errors</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SYSTEM_TIME" name="SYSTEM_TIME">SYSTEM_TIME (<a href="
      #SYSTEM_TIME">
    #2
   </a>
   )
  </h2>
  <p class="description">The system time is the time of the master clock, typically the computer clock of the main onboard computer.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_unix_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp of the master clock in microseconds since UNIX epoch.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp of the component clock since boot time in milliseconds.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="PING" name="PING">PING (<a href="
      #PING">
    #4
   </a>
   )
  </h2>
  <p class="description">A ping message either requesting or responding to a ping. This allows to measure the system latencies, including serial port, radio modem and UDP connections.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Unix timestamp in microseconds or since system boot if smaller than MAVLink epoch (1.1.2009)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">seq</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">PING sequence</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">0: request ping from all receiving systems, if greater than 0: message is a ping response and number is the system id of the requesting system</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">0: request ping from all receiving components, if greater than 0: message is a ping response and number is the system id of the requesting system</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="CHANGE_OPERATOR_CONTROL" name="CHANGE_OPERATOR_CONTROL">CHANGE_OPERATOR_CONTROL (<a href="
      #CHANGE_OPERATOR_CONTROL">
    #5
   </a>
   )
  </h2>
  <p class="description">Request to control this MAV</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System the GCS requests control for</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">control_request</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">0: request control of this MAV, 1: Release control of this MAV</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">version</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">0: key as plaintext, 1-255: future, different hashing/encryption variants. The GCS should in general use the safest mode possible initially and then gradually move down the encryption level if it gets a NACK message indicating an encryption mismatch.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">passkey</td>
     <td class="mavlink_type" valign="top">char[25]</td>
     <td class="mavlink_comment">Password / Key, depending on version plaintext or encrypted. 25 or less characters, NULL terminated. The characters may involve A-Z, a-z, 0-9, and "!?,.-"</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="CHANGE_OPERATOR_CONTROL_ACK" name="CHANGE_OPERATOR_CONTROL_ACK">CHANGE_OPERATOR_CONTROL_ACK (<a href="
      #CHANGE_OPERATOR_CONTROL_ACK">
    #6
   </a>
   )
  </h2>
  <p class="description">Accept / deny control of this MAV</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">gcs_system_id</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">ID of the GCS this message</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">control_request</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">0: request control of this MAV, 1: Release control of this MAV</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ack</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">0: ACK, 1: NACK: Wrong passkey, 2: NACK: Unsupported passkey encryption method, 3: NACK: Already under control</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="AUTH_KEY" name="AUTH_KEY">AUTH_KEY (<a href="
      #AUTH_KEY">
    #7
   </a>
   )
  </h2>
  <p class="description">Emit an encrypted signature / key identifying this system. PLEASE NOTE: This protocol has been kept simple, so transmitting the key requires an encrypted channel for true safety.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">key</td>
     <td class="mavlink_type" valign="top">char[32]</td>
     <td class="mavlink_comment">key</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SET_MODE" name="SET_MODE">SET_MODE (<a href="
      #SET_MODE">
    #11
   </a>
   )
  </h2>
  <p class="description">THIS INTERFACE IS DEPRECATED. USE COMMAND_LONG with MAV_CMD_DO_SET_MODE INSTEAD. Set the system mode, as defined by enum MAV_MODE. There is no target component id as the mode is by definition for the overall aircraft, not only for one component.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">The system setting the mode</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">base_mode</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">The new base mode</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">custom_mode</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">The new autopilot-specific mode. This field can be ignored by an autopilot.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="PARAM_REQUEST_READ" name="PARAM_REQUEST_READ">PARAM_REQUEST_READ (<a href="
      #PARAM_REQUEST_READ">
    #20
   </a>
   )
  </h2>
  <p class="description">Request to read the onboard parameter with the param_id string id. Onboard parameters are stored as key[const char*] -&gt; value[float]. This allows to send a parameter to any other component (such as the GCS) without the need of previous knowledge of possible parameter names. Thus the same GCS can store different parameters for different autopilots. See also http://qgroundcontrol.org/parameter_interface for a full documentation of QGroundControl and IMU code.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_id</td>
     <td class="mavlink_type" valign="top">char[16]</td>
     <td class="mavlink_comment">Onboard parameter id, terminated by NULL if the length is less than 16 human-readable chars and WITHOUT null termination (NULL) byte if the length is exactly 16 chars - applications have to provide 16+1 bytes storage if the ID is stored as string</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_index</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Parameter index. Send -1 to use the param ID field as identifier (else the param id will be ignored)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="PARAM_REQUEST_LIST" name="PARAM_REQUEST_LIST">PARAM_REQUEST_LIST (<a href="
      #PARAM_REQUEST_LIST">
    #21
   </a>
   )
  </h2>
  <p class="description">Request all parameters of this component. After this request, all parameters are emitted.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="PARAM_VALUE" name="PARAM_VALUE">PARAM_VALUE (<a href="
      #PARAM_VALUE">
    #22
   </a>
   )
  </h2>
  <p class="description">Emit the value of a onboard parameter. The inclusion of param_count and param_index in the message allows the recipient to keep track of received parameters and allows him to re-request missing parameters after a loss or timeout.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_id</td>
     <td class="mavlink_type" valign="top">char[16]</td>
     <td class="mavlink_comment">Onboard parameter id, terminated by NULL if the length is less than 16 human-readable chars and WITHOUT null termination (NULL) byte if the length is exactly 16 chars - applications have to provide 16+1 bytes storage if the ID is stored as string</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_value</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Onboard parameter value</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Onboard parameter type: see the MAV_PARAM_TYPE enum for supported data types.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_count</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Total number of onboard parameters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_index</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Index of this onboard parameter</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="PARAM_SET" name="PARAM_SET">PARAM_SET (<a href="
      #PARAM_SET">
    #23
   </a>
   )
  </h2>
  <p class="description">Set a parameter value TEMPORARILY to RAM. It will be reset to default on system reboot. Send the ACTION MAV_ACTION_STORAGE_WRITE to PERMANENTLY write the RAM contents to EEPROM. IMPORTANT: The receiving component should acknowledge the new parameter value by sending a param_value message to all communication partners. This will also ensure that multiple GCS all have an up-to-date list of all parameters. If the sending GCS did not receive a PARAM_VALUE message within its timeout time, it should re-send the PARAM_SET message.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_id</td>
     <td class="mavlink_type" valign="top">char[16]</td>
     <td class="mavlink_comment">Onboard parameter id, terminated by NULL if the length is less than 16 human-readable chars and WITHOUT null termination (NULL) byte if the length is exactly 16 chars - applications have to provide 16+1 bytes storage if the ID is stored as string</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_value</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Onboard parameter value</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Onboard parameter type: see the MAV_PARAM_TYPE enum for supported data types.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="GPS_RAW_INT" name="GPS_RAW_INT">GPS_RAW_INT (<a href="
      #GPS_RAW_INT">
    #24
   </a>
   )
  </h2>
  <p class="description">The global position, as returned by the Global Positioning System (GPS). This is
                NOT the global position estimate of the system, but rather a RAW sensor value. See message GLOBAL_POSITION for the global position estimate. Coordinate frame is right-handed, Z-axis up (GPS frame).</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since UNIX epoch or microseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">fix_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">See the GPS_FIX_TYPE enum.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lat</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude (WGS84, EGM96 ellipsoid), in degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lon</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude (WGS84, EGM96 ellipsoid), in degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">alt</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Altitude (AMSL, NOT WGS84), in meters * 1000 (positive for up). Note that virtually all GPS modules provide the AMSL altitude in addition to the WGS84 altitude.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">eph</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">GPS HDOP horizontal dilution of position (unitless). If unknown, set to: UINT16_MAX</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">epv</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">GPS VDOP vertical dilution of position (unitless). If unknown, set to: UINT16_MAX</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vel</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">GPS ground speed (m/s * 100). If unknown, set to: UINT16_MAX</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">cog</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Course over ground (NOT heading, but direction of movement) in degrees * 100, 0.0..359.99 degrees. If unknown, set to: UINT16_MAX</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">satellites_visible</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Number of satellites visible. If unknown, set to 255</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">alt_ellipsoid</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Altitude (above WGS84, EGM96 ellipsoid), in meters * 1000 (positive for up).</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">h_acc</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Position uncertainty in meters * 1000 (positive for up).</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">v_acc</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Altitude uncertainty in meters * 1000 (positive for up).</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vel_acc</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Speed uncertainty in meters * 1000 (positive for up).</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">hdg_acc</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Heading / track uncertainty in degrees * 1e5.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="GPS_STATUS" name="GPS_STATUS">GPS_STATUS (<a href="
      #GPS_STATUS">
    #25
   </a>
   )
  </h2>
  <p class="description">The positioning status, as reported by GPS. This message is intended to display status information about each satellite visible to the receiver. See message GLOBAL_POSITION for the global position estimate. This message can contain information for up to 20 satellites.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">satellites_visible</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Number of satellites visible</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">satellite_prn</td>
     <td class="mavlink_type" valign="top">uint8_t[20]</td>
     <td class="mavlink_comment">Global satellite ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">satellite_used</td>
     <td class="mavlink_type" valign="top">uint8_t[20]</td>
     <td class="mavlink_comment">0: Satellite not used, 1: used for localization</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">satellite_elevation</td>
     <td class="mavlink_type" valign="top">uint8_t[20]</td>
     <td class="mavlink_comment">Elevation (0: right on top of receiver, 90: on the horizon) of satellite</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">satellite_azimuth</td>
     <td class="mavlink_type" valign="top">uint8_t[20]</td>
     <td class="mavlink_comment">Direction of satellite, 0: 0 deg, 255: 360 deg.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">satellite_snr</td>
     <td class="mavlink_type" valign="top">uint8_t[20]</td>
     <td class="mavlink_comment">Signal to noise ratio of satellite</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SCALED_IMU" name="SCALED_IMU">SCALED_IMU (<a href="
      #SCALED_IMU">
    #26
   </a>
   )
  </h2>
  <p class="description">The RAW IMU readings for the usual 9DOF sensor setup. This message should contain the scaled values to the described units</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xacc</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">X acceleration (mg)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yacc</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Y acceleration (mg)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zacc</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Z acceleration (mg)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xgyro</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Angular speed around X axis (millirad /sec)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ygyro</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Angular speed around Y axis (millirad /sec)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zgyro</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Angular speed around Z axis (millirad /sec)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xmag</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">X Magnetic field (milli tesla)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ymag</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Y Magnetic field (milli tesla)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zmag</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Z Magnetic field (milli tesla)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="RAW_IMU" name="RAW_IMU">RAW_IMU (<a href="
      #RAW_IMU">
    #27
   </a>
   )
  </h2>
  <p class="description">The RAW IMU readings for the usual 9DOF sensor setup. This message should always contain the true raw values without any scaling to allow data capture and system debugging.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since UNIX epoch or microseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xacc</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">X acceleration (raw)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yacc</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Y acceleration (raw)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zacc</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Z acceleration (raw)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xgyro</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Angular speed around X axis (raw)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ygyro</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Angular speed around Y axis (raw)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zgyro</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Angular speed around Z axis (raw)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xmag</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">X Magnetic field (raw)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ymag</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Y Magnetic field (raw)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zmag</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Z Magnetic field (raw)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="RAW_PRESSURE" name="RAW_PRESSURE">RAW_PRESSURE (<a href="
      #RAW_PRESSURE">
    #28
   </a>
   )
  </h2>
  <p class="description">The RAW pressure readings for the typical setup of one absolute pressure and one differential pressure sensor. The sensor values should be the raw, UNSCALED ADC values.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since UNIX epoch or microseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">press_abs</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Absolute pressure (raw)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">press_diff1</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Differential pressure 1 (raw, 0 if nonexistant)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">press_diff2</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Differential pressure 2 (raw, 0 if nonexistant)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">temperature</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Raw Temperature measurement (raw)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SCALED_PRESSURE" name="SCALED_PRESSURE">SCALED_PRESSURE (<a href="
      #SCALED_PRESSURE">
    #29
   </a>
   )
  </h2>
  <p class="description">The pressure readings for the typical setup of one absolute and differential pressure sensor. The units are as specified in each field.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">press_abs</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Absolute pressure (hectopascal)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">press_diff</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Differential pressure 1 (hectopascal)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">temperature</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Temperature measurement (0.01 degrees celsius)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="ATTITUDE" name="ATTITUDE">ATTITUDE (<a href="
      #ATTITUDE">
    #30
   </a>
   )
  </h2>
  <p class="description">The attitude in the aeronautical frame (right-handed, Z-down, X-front, Y-right).</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">roll</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Roll angle (rad, -pi..+pi)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pitch</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Pitch angle (rad, -pi..+pi)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Yaw angle (rad, -pi..+pi)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rollspeed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Roll angular speed (rad/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pitchspeed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Pitch angular speed (rad/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yawspeed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Yaw angular speed (rad/s)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="ATTITUDE_QUATERNION" name="ATTITUDE_QUATERNION">ATTITUDE_QUATERNION (<a href="
      #ATTITUDE_QUATERNION">
    #31
   </a>
   )
  </h2>
  <p class="description">The attitude in the aeronautical frame (right-handed, Z-down, X-front, Y-right), expressed as quaternion. Quaternion order is w, x, y, z and a zero rotation would be expressed as (1 0 0 0).</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">q1</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Quaternion component 1, w (1 in null-rotation)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">q2</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Quaternion component 2, x (0 in null-rotation)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">q3</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Quaternion component 3, y (0 in null-rotation)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">q4</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Quaternion component 4, z (0 in null-rotation)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rollspeed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Roll angular speed (rad/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pitchspeed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Pitch angular speed (rad/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yawspeed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Yaw angular speed (rad/s)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="LOCAL_POSITION_NED" name="LOCAL_POSITION_NED">LOCAL_POSITION_NED (<a href="
      #LOCAL_POSITION_NED">
    #32
   </a>
   )
  </h2>
  <p class="description">The filtered local position (e.g. fused computer vision and accelerometers). Coordinate frame is right-handed, Z-axis down (aeronautical frame, NED / north-east-down convention)</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X Position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y Position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z Position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vx</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X Speed</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vy</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y Speed</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vz</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z Speed</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="GLOBAL_POSITION_INT" name="GLOBAL_POSITION_INT">GLOBAL_POSITION_INT (<a href="
      #GLOBAL_POSITION_INT">
    #33
   </a>
   )
  </h2>
  <p class="description">The filtered global position (e.g. fused GPS and accelerometers). The position is in GPS-frame (right-handed, Z-up). It
               is designed as scaled integer message since the resolution of float is not sufficient.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lat</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude, expressed as degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lon</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude, expressed as degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">alt</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Altitude in meters, expressed as * 1000 (millimeters), AMSL (not WGS84 - note that virtually all GPS modules provide the AMSL as well)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">relative_alt</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Altitude above ground in meters, expressed as * 1000 (millimeters)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vx</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Ground X Speed (Latitude, positive north), expressed as m/s * 100</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vy</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Ground Y Speed (Longitude, positive east), expressed as m/s * 100</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vz</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Ground Z Speed (Altitude, positive down), expressed as m/s * 100</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">hdg</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Vehicle heading (yaw angle) in degrees * 100, 0.0..359.99 degrees. If unknown, set to: UINT16_MAX</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="RC_CHANNELS_SCALED" name="RC_CHANNELS_SCALED">RC_CHANNELS_SCALED (<a href="
      #RC_CHANNELS_SCALED">
    #34
   </a>
   )
  </h2>
  <p class="description">The scaled values of the RC channels received. (-100%) -10000, (0%) 0, (100%) 10000. Channels that are inactive should be set to UINT16_MAX.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">port</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Servo output port (set of 8 outputs = 1 port). Most MAVs will just use one, but this allows for more than 8 servos.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan1_scaled</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">RC channel 1 value scaled, (-100%) -10000, (0%) 0, (100%) 10000, (invalid) INT16_MAX.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan2_scaled</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">RC channel 2 value scaled, (-100%) -10000, (0%) 0, (100%) 10000, (invalid) INT16_MAX.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan3_scaled</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">RC channel 3 value scaled, (-100%) -10000, (0%) 0, (100%) 10000, (invalid) INT16_MAX.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan4_scaled</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">RC channel 4 value scaled, (-100%) -10000, (0%) 0, (100%) 10000, (invalid) INT16_MAX.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan5_scaled</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">RC channel 5 value scaled, (-100%) -10000, (0%) 0, (100%) 10000, (invalid) INT16_MAX.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan6_scaled</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">RC channel 6 value scaled, (-100%) -10000, (0%) 0, (100%) 10000, (invalid) INT16_MAX.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan7_scaled</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">RC channel 7 value scaled, (-100%) -10000, (0%) 0, (100%) 10000, (invalid) INT16_MAX.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan8_scaled</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">RC channel 8 value scaled, (-100%) -10000, (0%) 0, (100%) 10000, (invalid) INT16_MAX.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rssi</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Receive signal strength indicator, 0: 0%, 100: 100%, 255: invalid/unknown.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="RC_CHANNELS_RAW" name="RC_CHANNELS_RAW">RC_CHANNELS_RAW (<a href="
      #RC_CHANNELS_RAW">
    #35
   </a>
   )
  </h2>
  <p class="description">The RAW values of the RC channels received. The standard PPM modulation is as follows: 1000 microseconds: 0%, 2000 microseconds: 100%. Individual receivers/transmitters might violate this specification.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">port</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Servo output port (set of 8 outputs = 1 port). Most MAVs will just use one, but this allows for more than 8 servos.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan1_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 1 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan2_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 2 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan3_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 3 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan4_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 4 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan5_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 5 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan6_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 6 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan7_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 7 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan8_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 8 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rssi</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Receive signal strength indicator, 0: 0%, 100: 100%, 255: invalid/unknown.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SERVO_OUTPUT_RAW" name="SERVO_OUTPUT_RAW">SERVO_OUTPUT_RAW (<a href="
      #SERVO_OUTPUT_RAW">
    #36
   </a>
   )
  </h2>
  <p class="description">The RAW values of the servo outputs (for RC input from the remote, use the RC_CHANNELS messages). The standard PPM modulation is as follows: 1000 microseconds: 0%, 2000 microseconds: 100%.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">port</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Servo output port (set of 8 outputs = 1 port). Most MAVs will just use one, but this allows to encode more than 8 servos.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">servo1_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Servo output 1 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">servo2_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Servo output 2 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">servo3_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Servo output 3 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">servo4_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Servo output 4 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">servo5_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Servo output 5 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">servo6_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Servo output 6 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">servo7_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Servo output 7 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">servo8_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Servo output 8 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">servo9_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Servo output 9 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">servo10_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Servo output 10 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">servo11_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Servo output 11 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">servo12_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Servo output 12 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">servo13_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Servo output 13 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">servo14_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Servo output 14 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">servo15_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Servo output 15 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">servo16_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Servo output 16 value, in microseconds</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MISSION_REQUEST_PARTIAL_LIST" name="MISSION_REQUEST_PARTIAL_LIST">MISSION_REQUEST_PARTIAL_LIST (<a href="
      #MISSION_REQUEST_PARTIAL_LIST">
    #37
   </a>
   )
  </h2>
  <p class="description">Request a partial list of mission items from the system/component. http://qgroundcontrol.org/mavlink/waypoint_protocol. If start and end index are the same, just send one waypoint.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">start_index</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Start index, 0 by default</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">end_index</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">End index, -1 by default (-1: send list to end). Else a valid index of the list</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mission_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Mission type, see MAV_MISSION_TYPE</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MISSION_WRITE_PARTIAL_LIST" name="MISSION_WRITE_PARTIAL_LIST">MISSION_WRITE_PARTIAL_LIST (<a href="
      #MISSION_WRITE_PARTIAL_LIST">
    #38
   </a>
   )
  </h2>
  <p class="description">This message is sent to the MAV to write a partial list. If start index == end index, only one item will be transmitted / updated. If the start index is NOT 0 and above the current list size, this request should be REJECTED!</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">start_index</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Start index, 0 by default and smaller / equal to the largest index of the current onboard list.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">end_index</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">End index, equal or greater than start index.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mission_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Mission type, see MAV_MISSION_TYPE</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MISSION_ITEM" name="MISSION_ITEM">MISSION_ITEM (<a href="
      #MISSION_ITEM">
    #39
   </a>
   )
  </h2>
  <p class="description">Message encoding a mission item. This message is emitted to announce
                the presence of a mission item and to set a mission item on the system. The mission item can be either in x, y, z meters (type: LOCAL) or x:lat, y:lon, z:altitude. Local frame is Z-down, right handed (NED), global frame is Z-up, right handed (ENU). See also http://qgroundcontrol.org/mavlink/waypoint_protocol.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">seq</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Sequence</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">frame</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">The coordinate system of the waypoint. see MAV_FRAME in mavlink_types.h</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">command</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">The scheduled action for the waypoint. see MAV_CMD in common.xml MAVLink specs</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">current</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">false:0, true:1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">autocontinue</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">autocontinue to next wp</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param1</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">PARAM1, see MAV_CMD enum</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param2</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">PARAM2, see MAV_CMD enum</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param3</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">PARAM3, see MAV_CMD enum</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param4</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">PARAM4, see MAV_CMD enum</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">PARAM5 / local: x position, global: latitude</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">PARAM6 / y position: global: longitude</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">PARAM7 / z position: global: altitude (relative or absolute, depending on frame.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mission_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Mission type, see MAV_MISSION_TYPE</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MISSION_REQUEST" name="MISSION_REQUEST">MISSION_REQUEST (<a href="
      #MISSION_REQUEST">
    #40
   </a>
   )
  </h2>
  <p class="description">Request the information of the mission item with the sequence number seq. The response of the system to this message should be a MISSION_ITEM message. http://qgroundcontrol.org/mavlink/waypoint_protocol</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">seq</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Sequence</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mission_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Mission type, see MAV_MISSION_TYPE</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MISSION_SET_CURRENT" name="MISSION_SET_CURRENT">MISSION_SET_CURRENT (<a href="
      #MISSION_SET_CURRENT">
    #41
   </a>
   )
  </h2>
  <p class="description">Set the mission item with sequence number seq as current item. This means that the MAV will continue to this mission item on the shortest path (not following the mission items in-between).</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">seq</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Sequence</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MISSION_CURRENT" name="MISSION_CURRENT">MISSION_CURRENT (<a href="
      #MISSION_CURRENT">
    #42
   </a>
   )
  </h2>
  <p class="description">Message that announces the sequence number of the current active mission item. The MAV will fly towards this mission item.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">seq</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Sequence</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MISSION_REQUEST_LIST" name="MISSION_REQUEST_LIST">MISSION_REQUEST_LIST (<a href="
      #MISSION_REQUEST_LIST">
    #43
   </a>
   )
  </h2>
  <p class="description">Request the overall list of mission items from the system/component.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mission_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Mission type, see MAV_MISSION_TYPE</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MISSION_COUNT" name="MISSION_COUNT">MISSION_COUNT (<a href="
      #MISSION_COUNT">
    #44
   </a>
   )
  </h2>
  <p class="description">This message is emitted as response to MISSION_REQUEST_LIST by the MAV and to initiate a write transaction. The GCS can then request the individual mission item based on the knowledge of the total number of waypoints.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">count</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Number of mission items in the sequence</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mission_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Mission type, see MAV_MISSION_TYPE</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MISSION_CLEAR_ALL" name="MISSION_CLEAR_ALL">MISSION_CLEAR_ALL (<a href="
      #MISSION_CLEAR_ALL">
    #45
   </a>
   )
  </h2>
  <p class="description">Delete all mission items at once.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mission_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Mission type, see MAV_MISSION_TYPE</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MISSION_ITEM_REACHED" name="MISSION_ITEM_REACHED">MISSION_ITEM_REACHED (<a href="
      #MISSION_ITEM_REACHED">
    #46
   </a>
   )
  </h2>
  <p class="description">A certain mission item has been reached. The system will either hold this position (or circle on the orbit) or (if the autocontinue on the WP was set) continue to the next waypoint.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">seq</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Sequence</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MISSION_ACK" name="MISSION_ACK">MISSION_ACK (<a href="
      #MISSION_ACK">
    #47
   </a>
   )
  </h2>
  <p class="description">Ack message during waypoint handling. The type field states if this message is a positive ack (type=0) or if an error happened (type=non-zero).</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">See MAV_MISSION_RESULT enum</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mission_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Mission type, see MAV_MISSION_TYPE</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SET_GPS_GLOBAL_ORIGIN" name="SET_GPS_GLOBAL_ORIGIN">SET_GPS_GLOBAL_ORIGIN (<a href="
      #SET_GPS_GLOBAL_ORIGIN">
    #48
   </a>
   )
  </h2>
  <p class="description">As local waypoints exist, the global waypoint reference allows to transform between the local coordinate frame and the global (GPS) coordinate frame. This can be necessary when e.g. in- and outdoor settings are connected and the MAV should move from in- to outdoor.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">latitude</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude (WGS84), in degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">longitude</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude (WGS84, in degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">altitude</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Altitude (AMSL), in meters * 1000 (positive for up)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since UNIX epoch or microseconds since system boot)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="GPS_GLOBAL_ORIGIN" name="GPS_GLOBAL_ORIGIN">GPS_GLOBAL_ORIGIN (<a href="
      #GPS_GLOBAL_ORIGIN">
    #49
   </a>
   )
  </h2>
  <p class="description">Once the MAV sets a new GPS-Local correspondence, this message announces the origin (0,0,0) position</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">latitude</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude (WGS84), in degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">longitude</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude (WGS84), in degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">altitude</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Altitude (AMSL), in meters * 1000 (positive for up)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since UNIX epoch or microseconds since system boot)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="PARAM_MAP_RC" name="PARAM_MAP_RC">PARAM_MAP_RC (<a href="
      #PARAM_MAP_RC">
    #50
   </a>
   )
  </h2>
  <p class="description">Bind a RC channel to a parameter. The parameter should change accoding to the RC channel value.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_id</td>
     <td class="mavlink_type" valign="top">char[16]</td>
     <td class="mavlink_comment">Onboard parameter id, terminated by NULL if the length is less than 16 human-readable chars and WITHOUT null termination (NULL) byte if the length is exactly 16 chars - applications have to provide 16+1 bytes storage if the ID is stored as string</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_index</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Parameter index. Send -1 to use the param ID field as identifier (else the param id will be ignored), send -2 to disable any existing map for this rc_channel_index.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">parameter_rc_channel_index</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Index of parameter RC channel. Not equal to the RC channel id. Typically correpsonds to a potentiometer-knob on the RC.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_value0</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Initial parameter value</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">scale</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Scale, maps the RC range [-1, 1] to a parameter value</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_value_min</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Minimum param value. The protocol does not define if this overwrites an onboard minimum value. (Depends on implementation)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_value_max</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Maximum param value. The protocol does not define if this overwrites an onboard maximum value. (Depends on implementation)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MISSION_REQUEST_INT" name="MISSION_REQUEST_INT">MISSION_REQUEST_INT (<a href="
      #MISSION_REQUEST_INT">
    #51
   </a>
   )
  </h2>
  <p class="description">Request the information of the mission item with the sequence number seq. The response of the system to this message should be a MISSION_ITEM_INT message. http://qgroundcontrol.org/mavlink/waypoint_protocol</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">seq</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Sequence</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mission_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Mission type, see MAV_MISSION_TYPE</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SAFETY_SET_ALLOWED_AREA" name="SAFETY_SET_ALLOWED_AREA">SAFETY_SET_ALLOWED_AREA (<a href="
      #SAFETY_SET_ALLOWED_AREA">
    #54
   </a>
   )
  </h2>
  <p class="description">Set a safety zone (volume), which is defined by two corners of a cube. This message can be used to tell the MAV which setpoints/waypoints to accept and which to reject. Safety areas are often enforced by national or competition regulations.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">frame</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Coordinate frame, as defined by MAV_FRAME enum in mavlink_types.h. Can be either global, GPS, right-handed with Z axis up or local, right handed, Z axis down.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">p1x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">x position 1 / Latitude 1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">p1y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">y position 1 / Longitude 1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">p1z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">z position 1 / Altitude 1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">p2x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">x position 2 / Latitude 2</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">p2y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">y position 2 / Longitude 2</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">p2z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">z position 2 / Altitude 2</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SAFETY_ALLOWED_AREA" name="SAFETY_ALLOWED_AREA">SAFETY_ALLOWED_AREA (<a href="
      #SAFETY_ALLOWED_AREA">
    #55
   </a>
   )
  </h2>
  <p class="description">Read out the safety zone the MAV currently assumes.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">frame</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Coordinate frame, as defined by MAV_FRAME enum in mavlink_types.h. Can be either global, GPS, right-handed with Z axis up or local, right handed, Z axis down.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">p1x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">x position 1 / Latitude 1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">p1y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">y position 1 / Longitude 1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">p1z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">z position 1 / Altitude 1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">p2x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">x position 2 / Latitude 2</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">p2y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">y position 2 / Longitude 2</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">p2z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">z position 2 / Altitude 2</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="ATTITUDE_QUATERNION_COV" name="ATTITUDE_QUATERNION_COV">ATTITUDE_QUATERNION_COV (<a href="
      #ATTITUDE_QUATERNION_COV">
    #61
   </a>
   )
  </h2>
  <p class="description">The attitude in the aeronautical frame (right-handed, Z-down, X-front, Y-right), expressed as quaternion. Quaternion order is w, x, y, z and a zero rotation would be expressed as (1 0 0 0).</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since system boot or since UNIX epoch)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">q</td>
     <td class="mavlink_type" valign="top">float[4]</td>
     <td class="mavlink_comment">Quaternion components, w, x, y, z (1 0 0 0 is the null-rotation)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rollspeed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Roll angular speed (rad/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pitchspeed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Pitch angular speed (rad/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yawspeed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Yaw angular speed (rad/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">covariance</td>
     <td class="mavlink_type" valign="top">float[9]</td>
     <td class="mavlink_comment">Attitude covariance</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="NAV_CONTROLLER_OUTPUT" name="NAV_CONTROLLER_OUTPUT">NAV_CONTROLLER_OUTPUT (<a href="
      #NAV_CONTROLLER_OUTPUT">
    #62
   </a>
   )
  </h2>
  <p class="description">The state of the fixed wing navigation and position controller.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">nav_roll</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Current desired roll in degrees</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">nav_pitch</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Current desired pitch in degrees</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">nav_bearing</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Current desired heading in degrees</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_bearing</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Bearing to current waypoint/target in degrees</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">wp_dist</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Distance to active waypoint in meters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">alt_error</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Current altitude error in meters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">aspd_error</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Current airspeed error in meters/second</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xtrack_error</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Current crosstrack error on x-y plane in meters</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="GLOBAL_POSITION_INT_COV" name="GLOBAL_POSITION_INT_COV">GLOBAL_POSITION_INT_COV (<a href="
      #GLOBAL_POSITION_INT_COV">
    #63
   </a>
   )
  </h2>
  <p class="description">The filtered global position (e.g. fused GPS and accelerometers). The position is in GPS-frame (right-handed, Z-up). It  is designed as scaled integer message since the resolution of float is not sufficient. NOTE: This message is intended for onboard networks / companion computers and higher-bandwidth links and optimized for accuracy and completeness. Please use the GLOBAL_POSITION_INT message for a minimal subset.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since system boot or since UNIX epoch)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">estimator_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Class id of the estimator this estimate originated from.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lat</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude, expressed as degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lon</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude, expressed as degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">alt</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Altitude in meters, expressed as * 1000 (millimeters), above MSL</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">relative_alt</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Altitude above ground in meters, expressed as * 1000 (millimeters)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vx</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Ground X Speed (Latitude), expressed as m/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vy</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Ground Y Speed (Longitude), expressed as m/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vz</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Ground Z Speed (Altitude), expressed as m/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">covariance</td>
     <td class="mavlink_type" valign="top">float[36]</td>
     <td class="mavlink_comment">Covariance matrix (first six entries are the first ROW, next six entries are the second row, etc.)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="LOCAL_POSITION_NED_COV" name="LOCAL_POSITION_NED_COV">LOCAL_POSITION_NED_COV (<a href="
      #LOCAL_POSITION_NED_COV">
    #64
   </a>
   )
  </h2>
  <p class="description">The filtered local position (e.g. fused computer vision and accelerometers). Coordinate frame is right-handed, Z-axis down (aeronautical frame, NED / north-east-down convention)</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since system boot or since UNIX epoch)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">estimator_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Class id of the estimator this estimate originated from.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X Position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y Position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z Position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vx</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X Speed (m/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vy</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y Speed (m/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vz</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z Speed (m/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ax</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X Acceleration (m/s^2)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ay</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y Acceleration (m/s^2)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">az</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z Acceleration (m/s^2)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">covariance</td>
     <td class="mavlink_type" valign="top">float[45]</td>
     <td class="mavlink_comment">Covariance matrix upper right triangular (first nine entries are the first ROW, next eight entries are the second row, etc.)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="RC_CHANNELS" name="RC_CHANNELS">RC_CHANNELS (<a href="
      #RC_CHANNELS">
    #65
   </a>
   )
  </h2>
  <p class="description">The PPM values of the RC channels received. The standard PPM modulation is as follows: 1000 microseconds: 0%, 2000 microseconds: 100%. Individual receivers/transmitters might violate this specification.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chancount</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Total number of RC channels being received. This can be larger than 18, indicating that more channels are available but not given in this message. This value should be 0 when no RC channels are available.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan1_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 1 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan2_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 2 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan3_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 3 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan4_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 4 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan5_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 5 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan6_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 6 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan7_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 7 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan8_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 8 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan9_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 9 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan10_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 10 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan11_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 11 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan12_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 12 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan13_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 13 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan14_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 14 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan15_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 15 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan16_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 16 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan17_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 17 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan18_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 18 value, in microseconds. A value of UINT16_MAX implies the channel is unused.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rssi</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Receive signal strength indicator, 0: 0%, 100: 100%, 255: invalid/unknown.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="REQUEST_DATA_STREAM" name="REQUEST_DATA_STREAM">REQUEST_DATA_STREAM (<a href="
      #REQUEST_DATA_STREAM">
    #66
   </a>
   )
  </h2>
  <p class="description">THIS INTERFACE IS DEPRECATED. USE SET_MESSAGE_INTERVAL INSTEAD.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">The target requested to send the message stream.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">The target requested to send the message stream.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">req_stream_id</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">The ID of the requested data stream</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">req_message_rate</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">The requested message rate</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">start_stop</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">1 to start sending, 0 to stop sending.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="DATA_STREAM" name="DATA_STREAM">DATA_STREAM (<a href="
      #DATA_STREAM">
    #67
   </a>
   )
  </h2>
  <p class="description">THIS INTERFACE IS DEPRECATED. USE MESSAGE_INTERVAL INSTEAD.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">stream_id</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">The ID of the requested data stream</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">message_rate</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">The message rate</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">on_off</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">1 stream is enabled, 0 stream is stopped.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MANUAL_CONTROL" name="MANUAL_CONTROL">MANUAL_CONTROL (<a href="
      #MANUAL_CONTROL">
    #69
   </a>
   )
  </h2>
  <p class="description">This message provides an API for manually controlling the vehicle using standard joystick axes nomenclature, along with a joystick-like input device. Unused axes can be disabled an buttons are also transmit as boolean values of their</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">The system to be controlled.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">X-axis, normalized to the range [-1000,1000]. A value of INT16_MAX indicates that this axis is invalid. Generally corresponds to forward(1000)-backward(-1000) movement on a joystick and the pitch of a vehicle.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Y-axis, normalized to the range [-1000,1000]. A value of INT16_MAX indicates that this axis is invalid. Generally corresponds to left(-1000)-right(1000) movement on a joystick and the roll of a vehicle.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Z-axis, normalized to the range [-1000,1000]. A value of INT16_MAX indicates that this axis is invalid. Generally corresponds to a separate slider movement with maximum being 1000 and minimum being -1000 on a joystick and the thrust of a vehicle. Positive values are positive thrust, negative values are negative thrust.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">r</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">R-axis, normalized to the range [-1000,1000]. A value of INT16_MAX indicates that this axis is invalid. Generally corresponds to a twisting of the joystick, with counter-clockwise being 1000 and clockwise being -1000, and the yaw of a vehicle.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">buttons</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">A bitfield corresponding to the joystick buttons' current state, 1 for pressed, 0 for released. The lowest bit corresponds to Button 1.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="RC_CHANNELS_OVERRIDE" name="RC_CHANNELS_OVERRIDE">RC_CHANNELS_OVERRIDE (<a href="
      #RC_CHANNELS_OVERRIDE">
    #70
   </a>
   )
  </h2>
  <p class="description">The RAW values of the RC channels sent to the MAV to override info received from the RC radio. A value of UINT16_MAX means no change to that channel. A value of 0 means control of that channel should be released back to the RC radio. The standard PPM modulation is as follows: 1000 microseconds: 0%, 2000 microseconds: 100%. Individual receivers/transmitters might violate this specification.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan1_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 1 value, in microseconds. A value of UINT16_MAX means to ignore this field.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan2_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 2 value, in microseconds. A value of UINT16_MAX means to ignore this field.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan3_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 3 value, in microseconds. A value of UINT16_MAX means to ignore this field.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan4_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 4 value, in microseconds. A value of UINT16_MAX means to ignore this field.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan5_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 5 value, in microseconds. A value of UINT16_MAX means to ignore this field.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan6_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 6 value, in microseconds. A value of UINT16_MAX means to ignore this field.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan7_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 7 value, in microseconds. A value of UINT16_MAX means to ignore this field.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan8_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 8 value, in microseconds. A value of UINT16_MAX means to ignore this field.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MISSION_ITEM_INT" name="MISSION_ITEM_INT">MISSION_ITEM_INT (<a href="
      #MISSION_ITEM_INT">
    #73
   </a>
   )
  </h2>
  <p class="description">Message encoding a mission item. This message is emitted to announce
                the presence of a mission item and to set a mission item on the system. The mission item can be either in x, y, z meters (type: LOCAL) or x:lat, y:lon, z:altitude. Local frame is Z-down, right handed (NED), global frame is Z-up, right handed (ENU). See alsohttp://qgroundcontrol.org/mavlink/waypoint_protocol.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">seq</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Waypoint ID (sequence number). Starts at zero. Increases monotonically for each waypoint, no gaps in the sequence (0,1,2,3,4).</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">frame</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">The coordinate system of the waypoint. see MAV_FRAME in mavlink_types.h</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">command</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">The scheduled action for the waypoint. see MAV_CMD in common.xml MAVLink specs</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">current</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">false:0, true:1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">autocontinue</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">autocontinue to next wp</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param1</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">PARAM1, see MAV_CMD enum</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param2</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">PARAM2, see MAV_CMD enum</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param3</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">PARAM3, see MAV_CMD enum</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param4</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">PARAM4, see MAV_CMD enum</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">PARAM5 / local: x position in meters * 1e4, global: latitude in degrees * 10^7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">PARAM6 / y position: local: x position in meters * 1e4, global: longitude in degrees *10^7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">PARAM7 / z position: global: altitude in meters (relative or absolute, depending on frame.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mission_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Mission type, see MAV_MISSION_TYPE</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="VFR_HUD" name="VFR_HUD">VFR_HUD (<a href="
      #VFR_HUD">
    #74
   </a>
   )
  </h2>
  <p class="description">Metrics typically displayed on a HUD for fixed wing aircraft</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">airspeed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Current airspeed in m/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">groundspeed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Current ground speed in m/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">heading</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Current heading in degrees, in compass units (0..360, 0=north)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">throttle</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Current throttle setting in integer percent, 0 to 100</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">alt</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Current altitude (MSL), in meters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">climb</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Current climb rate in meters/second</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="COMMAND_INT" name="COMMAND_INT">COMMAND_INT (<a href="
      #COMMAND_INT">
    #75
   </a>
   )
  </h2>
  <p class="description">Message encoding a command with parameters as scaled integers. Scaling depends on the actual command value.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">frame</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">The coordinate system of the COMMAND. see MAV_FRAME in mavlink_types.h</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">command</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">The scheduled action for the mission item. see MAV_CMD in common.xml MAVLink specs</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">current</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">false:0, true:1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">autocontinue</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">autocontinue to next wp</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param1</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">PARAM1, see MAV_CMD enum</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param2</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">PARAM2, see MAV_CMD enum</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param3</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">PARAM3, see MAV_CMD enum</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param4</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">PARAM4, see MAV_CMD enum</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">PARAM5 / local: x position in meters * 1e4, global: latitude in degrees * 10^7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">PARAM6 / local: y position in meters * 1e4, global: longitude in degrees * 10^7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">PARAM7 / z position: global: altitude in meters (relative or absolute, depending on frame.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="COMMAND_LONG" name="COMMAND_LONG">COMMAND_LONG (<a href="
      #COMMAND_LONG">
    #76
   </a>
   )
  </h2>
  <p class="description">Send a command with up to seven parameters to the MAV</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System which should execute the command</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component which should execute the command, 0 for all components</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">command</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Command ID, as defined by MAV_CMD enum.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">confirmation</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">0: First transmission of this command. 1-255: Confirmation transmissions (e.g. for kill command)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param1</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Parameter 1, as defined by MAV_CMD enum.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param2</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Parameter 2, as defined by MAV_CMD enum.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param3</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Parameter 3, as defined by MAV_CMD enum.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param4</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Parameter 4, as defined by MAV_CMD enum.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param5</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Parameter 5, as defined by MAV_CMD enum.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param6</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Parameter 6, as defined by MAV_CMD enum.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param7</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Parameter 7, as defined by MAV_CMD enum.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="COMMAND_ACK" name="COMMAND_ACK">COMMAND_ACK (<a href="
      #COMMAND_ACK">
    #77
   </a>
   )
  </h2>
  <p class="description">Report status of a command. Includes feedback whether the command was executed.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">command</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Command ID, as defined by MAV_CMD enum.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">result</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">See MAV_RESULT enum</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">progress</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">WIP: Also used as result_param1, it can be set with a enum containing the errors reasons of why the command was denied or the progress percentage or 255 if unknown the progress when result is MAV_RESULT_IN_PROGRESS.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">result_param2</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">WIP: Additional parameter of the result, example: which parameter of MAV_CMD_NAV_WAYPOINT caused it to be denied.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">WIP: System which requested the command to be executed</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">WIP: Component which requested the command to be executed</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MANUAL_SETPOINT" name="MANUAL_SETPOINT">MANUAL_SETPOINT (<a href="
      #MANUAL_SETPOINT">
    #81
   </a>
   )
  </h2>
  <p class="description">Setpoint in roll, pitch, yaw and thrust from the operator</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp in milliseconds since system boot</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">roll</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Desired roll rate in radians per second</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pitch</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Desired pitch rate in radians per second</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Desired yaw rate in radians per second</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">thrust</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Collective thrust, normalized to 0 .. 1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mode_switch</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Flight mode switch position, 0.. 255</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">manual_override_switch</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Override mode switch position, 0.. 255</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SET_ATTITUDE_TARGET" name="SET_ATTITUDE_TARGET">SET_ATTITUDE_TARGET (<a href="
      #SET_ATTITUDE_TARGET">
    #82
   </a>
   )
  </h2>
  <p class="description">Sets a desired vehicle attitude. Used by an external controller to command the vehicle (manual controller or other system).</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp in milliseconds since system boot</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">type_mask</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Mappings: If any of these bits are set, the corresponding input should be ignored: bit 1: body roll rate, bit 2: body pitch rate, bit 3: body yaw rate. bit 4-bit 6: reserved, bit 7: throttle, bit 8: attitude</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">q</td>
     <td class="mavlink_type" valign="top">float[4]</td>
     <td class="mavlink_comment">Attitude quaternion (w, x, y, z order, zero-rotation is 1, 0, 0, 0)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">body_roll_rate</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Body roll rate in radians per second</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">body_pitch_rate</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Body roll rate in radians per second</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">body_yaw_rate</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Body roll rate in radians per second</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">thrust</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Collective thrust, normalized to 0 .. 1 (-1 .. 1 for vehicles capable of reverse trust)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="ATTITUDE_TARGET" name="ATTITUDE_TARGET">ATTITUDE_TARGET (<a href="
      #ATTITUDE_TARGET">
    #83
   </a>
   )
  </h2>
  <p class="description">Reports the current commanded attitude of the vehicle as specified by the autopilot. This should match the commands sent in a SET_ATTITUDE_TARGET message if the vehicle is being controlled this way.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp in milliseconds since system boot</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">type_mask</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Mappings: If any of these bits are set, the corresponding input should be ignored: bit 1: body roll rate, bit 2: body pitch rate, bit 3: body yaw rate. bit 4-bit 7: reserved, bit 8: attitude</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">q</td>
     <td class="mavlink_type" valign="top">float[4]</td>
     <td class="mavlink_comment">Attitude quaternion (w, x, y, z order, zero-rotation is 1, 0, 0, 0)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">body_roll_rate</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Body roll rate in radians per second</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">body_pitch_rate</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Body pitch rate in radians per second</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">body_yaw_rate</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Body yaw rate in radians per second</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">thrust</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Collective thrust, normalized to 0 .. 1 (-1 .. 1 for vehicles capable of reverse trust)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SET_POSITION_TARGET_LOCAL_NED" name="SET_POSITION_TARGET_LOCAL_NED">SET_POSITION_TARGET_LOCAL_NED (<a href="
      #SET_POSITION_TARGET_LOCAL_NED">
    #84
   </a>
   )
  </h2>
  <p class="description">Sets a desired vehicle position in a local north-east-down coordinate frame. Used by an external controller to command the vehicle (manual controller or other system).</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp in milliseconds since system boot</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">coordinate_frame</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Valid options are: MAV_FRAME_LOCAL_NED = 1, MAV_FRAME_LOCAL_OFFSET_NED = 7, MAV_FRAME_BODY_NED = 8, MAV_FRAME_BODY_OFFSET_NED = 9</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">type_mask</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Bitmask to indicate which dimensions should be ignored by the vehicle: a value of 0b0000000000000000 or 0b0000001000000000 indicates that none of the setpoint dimensions should be ignored. If bit 10 is set the floats afx afy afz should be interpreted as force instead of acceleration. Mapping: bit 1: x, bit 2: y, bit 3: z, bit 4: vx, bit 5: vy, bit 6: vz, bit 7: ax, bit 8: ay, bit 9: az, bit 10: is force setpoint, bit 11: yaw, bit 12: yaw rate</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X Position in NED frame in meters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y Position in NED frame in meters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z Position in NED frame in meters (note, altitude is negative in NED)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vx</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X velocity in NED frame in meter / s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vy</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y velocity in NED frame in meter / s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vz</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z velocity in NED frame in meter / s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">afx</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X acceleration or force (if bit 10 of type_mask is set) in NED frame in meter / s^2 or N</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">afy</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y acceleration or force (if bit 10 of type_mask is set) in NED frame in meter / s^2 or N</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">afz</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z acceleration or force (if bit 10 of type_mask is set) in NED frame in meter / s^2 or N</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">yaw setpoint in rad</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw_rate</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">yaw rate setpoint in rad/s</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="POSITION_TARGET_LOCAL_NED" name="POSITION_TARGET_LOCAL_NED">POSITION_TARGET_LOCAL_NED (<a href="
      #POSITION_TARGET_LOCAL_NED">
    #85
   </a>
   )
  </h2>
  <p class="description">Reports the current commanded vehicle position, velocity, and acceleration as specified by the autopilot. This should match the commands sent in SET_POSITION_TARGET_LOCAL_NED if the vehicle is being controlled this way.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp in milliseconds since system boot</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">coordinate_frame</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Valid options are: MAV_FRAME_LOCAL_NED = 1, MAV_FRAME_LOCAL_OFFSET_NED = 7, MAV_FRAME_BODY_NED = 8, MAV_FRAME_BODY_OFFSET_NED = 9</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">type_mask</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Bitmask to indicate which dimensions should be ignored by the vehicle: a value of 0b0000000000000000 or 0b0000001000000000 indicates that none of the setpoint dimensions should be ignored. If bit 10 is set the floats afx afy afz should be interpreted as force instead of acceleration. Mapping: bit 1: x, bit 2: y, bit 3: z, bit 4: vx, bit 5: vy, bit 6: vz, bit 7: ax, bit 8: ay, bit 9: az, bit 10: is force setpoint, bit 11: yaw, bit 12: yaw rate</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X Position in NED frame in meters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y Position in NED frame in meters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z Position in NED frame in meters (note, altitude is negative in NED)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vx</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X velocity in NED frame in meter / s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vy</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y velocity in NED frame in meter / s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vz</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z velocity in NED frame in meter / s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">afx</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X acceleration or force (if bit 10 of type_mask is set) in NED frame in meter / s^2 or N</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">afy</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y acceleration or force (if bit 10 of type_mask is set) in NED frame in meter / s^2 or N</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">afz</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z acceleration or force (if bit 10 of type_mask is set) in NED frame in meter / s^2 or N</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">yaw setpoint in rad</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw_rate</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">yaw rate setpoint in rad/s</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SET_POSITION_TARGET_GLOBAL_INT" name="SET_POSITION_TARGET_GLOBAL_INT">SET_POSITION_TARGET_GLOBAL_INT (<a href="
      #SET_POSITION_TARGET_GLOBAL_INT">
    #86
   </a>
   )
  </h2>
  <p class="description">Sets a desired vehicle position, velocity, and/or acceleration in a global coordinate system (WGS84). Used by an external controller to command the vehicle (manual controller or other system).</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp in milliseconds since system boot. The rationale for the timestamp in the setpoint is to allow the system to compensate for the transport delay of the setpoint. This allows the system to compensate processing latency.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">coordinate_frame</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Valid options are: MAV_FRAME_GLOBAL_INT = 5, MAV_FRAME_GLOBAL_RELATIVE_ALT_INT = 6, MAV_FRAME_GLOBAL_TERRAIN_ALT_INT = 11</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">type_mask</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Bitmask to indicate which dimensions should be ignored by the vehicle: a value of 0b0000000000000000 or 0b0000001000000000 indicates that none of the setpoint dimensions should be ignored. If bit 10 is set the floats afx afy afz should be interpreted as force instead of acceleration. Mapping: bit 1: x, bit 2: y, bit 3: z, bit 4: vx, bit 5: vy, bit 6: vz, bit 7: ax, bit 8: ay, bit 9: az, bit 10: is force setpoint, bit 11: yaw, bit 12: yaw rate</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lat_int</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">X Position in WGS84 frame in 1e7 * meters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lon_int</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Y Position in WGS84 frame in 1e7 * meters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">alt</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Altitude in meters in AMSL altitude, not WGS84 if absolute or relative, above terrain if GLOBAL_TERRAIN_ALT_INT</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vx</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X velocity in NED frame in meter / s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vy</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y velocity in NED frame in meter / s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vz</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z velocity in NED frame in meter / s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">afx</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X acceleration or force (if bit 10 of type_mask is set) in NED frame in meter / s^2 or N</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">afy</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y acceleration or force (if bit 10 of type_mask is set) in NED frame in meter / s^2 or N</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">afz</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z acceleration or force (if bit 10 of type_mask is set) in NED frame in meter / s^2 or N</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">yaw setpoint in rad</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw_rate</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">yaw rate setpoint in rad/s</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="POSITION_TARGET_GLOBAL_INT" name="POSITION_TARGET_GLOBAL_INT">POSITION_TARGET_GLOBAL_INT (<a href="
      #POSITION_TARGET_GLOBAL_INT">
    #87
   </a>
   )
  </h2>
  <p class="description">Reports the current commanded vehicle position, velocity, and acceleration as specified by the autopilot. This should match the commands sent in SET_POSITION_TARGET_GLOBAL_INT if the vehicle is being controlled this way.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp in milliseconds since system boot. The rationale for the timestamp in the setpoint is to allow the system to compensate for the transport delay of the setpoint. This allows the system to compensate processing latency.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">coordinate_frame</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Valid options are: MAV_FRAME_GLOBAL_INT = 5, MAV_FRAME_GLOBAL_RELATIVE_ALT_INT = 6, MAV_FRAME_GLOBAL_TERRAIN_ALT_INT = 11</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">type_mask</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Bitmask to indicate which dimensions should be ignored by the vehicle: a value of 0b0000000000000000 or 0b0000001000000000 indicates that none of the setpoint dimensions should be ignored. If bit 10 is set the floats afx afy afz should be interpreted as force instead of acceleration. Mapping: bit 1: x, bit 2: y, bit 3: z, bit 4: vx, bit 5: vy, bit 6: vz, bit 7: ax, bit 8: ay, bit 9: az, bit 10: is force setpoint, bit 11: yaw, bit 12: yaw rate</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lat_int</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">X Position in WGS84 frame in 1e7 * meters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lon_int</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Y Position in WGS84 frame in 1e7 * meters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">alt</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Altitude in meters in AMSL altitude, not WGS84 if absolute or relative, above terrain if GLOBAL_TERRAIN_ALT_INT</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vx</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X velocity in NED frame in meter / s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vy</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y velocity in NED frame in meter / s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vz</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z velocity in NED frame in meter / s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">afx</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X acceleration or force (if bit 10 of type_mask is set) in NED frame in meter / s^2 or N</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">afy</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y acceleration or force (if bit 10 of type_mask is set) in NED frame in meter / s^2 or N</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">afz</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z acceleration or force (if bit 10 of type_mask is set) in NED frame in meter / s^2 or N</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">yaw setpoint in rad</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw_rate</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">yaw rate setpoint in rad/s</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="LOCAL_POSITION_NED_SYSTEM_GLOBAL_OFFSET" name="LOCAL_POSITION_NED_SYSTEM_GLOBAL_OFFSET">LOCAL_POSITION_NED_SYSTEM_GLOBAL_OFFSET (<a href="
      #LOCAL_POSITION_NED_SYSTEM_GLOBAL_OFFSET">
    #89
   </a>
   )
  </h2>
  <p class="description">The offset in X, Y, Z and yaw between the LOCAL_POSITION_NED messages of MAV X and the global coordinate frame in NED coordinates. Coordinate frame is right-handed, Z-axis down (aeronautical frame, NED / north-east-down convention)</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X Position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y Position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z Position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">roll</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Roll</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pitch</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Pitch</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Yaw</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="HIL_STATE" name="HIL_STATE">HIL_STATE (<a href="
      #HIL_STATE">
    #90
   </a>
   )
  </h2>
  <p class="description">DEPRECATED PACKET! Suffers from missing airspeed fields and singularities due to Euler angles. Please use HIL_STATE_QUATERNION instead. Sent from simulation to autopilot. This packet is useful for high throughput applications such as hardware in the loop simulations.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since UNIX epoch or microseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">roll</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Roll angle (rad)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pitch</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Pitch angle (rad)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Yaw angle (rad)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rollspeed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Body frame roll / phi angular speed (rad/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pitchspeed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Body frame pitch / theta angular speed (rad/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yawspeed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Body frame yaw / psi angular speed (rad/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lat</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude, expressed as * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lon</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude, expressed as * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">alt</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Altitude in meters, expressed as * 1000 (millimeters)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vx</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Ground X Speed (Latitude), expressed as m/s * 100</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vy</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Ground Y Speed (Longitude), expressed as m/s * 100</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vz</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Ground Z Speed (Altitude), expressed as m/s * 100</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xacc</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">X acceleration (mg)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yacc</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Y acceleration (mg)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zacc</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Z acceleration (mg)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="HIL_CONTROLS" name="HIL_CONTROLS">HIL_CONTROLS (<a href="
      #HIL_CONTROLS">
    #91
   </a>
   )
  </h2>
  <p class="description">Sent from autopilot to simulation. Hardware in the loop control outputs</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since UNIX epoch or microseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">roll_ailerons</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Control output -1 .. 1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pitch_elevator</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Control output -1 .. 1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw_rudder</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Control output -1 .. 1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">throttle</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Throttle 0 .. 1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">aux1</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Aux 1, -1 .. 1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">aux2</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Aux 2, -1 .. 1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">aux3</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Aux 3, -1 .. 1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">aux4</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Aux 4, -1 .. 1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mode</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System mode (MAV_MODE)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">nav_mode</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Navigation mode (MAV_NAV_MODE)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="HIL_RC_INPUTS_RAW" name="HIL_RC_INPUTS_RAW">HIL_RC_INPUTS_RAW (<a href="
      #HIL_RC_INPUTS_RAW">
    #92
   </a>
   )
  </h2>
  <p class="description">Sent from simulation to autopilot. The RAW values of the RC channels received. The standard PPM modulation is as follows: 1000 microseconds: 0%, 2000 microseconds: 100%. Individual receivers/transmitters might violate this specification.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since UNIX epoch or microseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan1_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 1 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan2_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 2 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan3_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 3 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan4_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 4 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan5_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 5 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan6_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 6 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan7_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 7 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan8_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 8 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan9_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 9 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan10_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 10 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan11_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 11 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">chan12_raw</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">RC channel 12 value, in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rssi</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Receive signal strength indicator, 0: 0%, 255: 100%</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="HIL_ACTUATOR_CONTROLS" name="HIL_ACTUATOR_CONTROLS">HIL_ACTUATOR_CONTROLS (<a href="
      #HIL_ACTUATOR_CONTROLS">
    #93
   </a>
   )
  </h2>
  <p class="description">Sent from autopilot to simulation. Hardware in the loop control outputs (replacement for HIL_CONTROLS)</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since UNIX epoch or microseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">controls</td>
     <td class="mavlink_type" valign="top">float[16]</td>
     <td class="mavlink_comment">Control outputs -1 .. 1. Channel assignment depends on the simulated hardware.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mode</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System mode (MAV_MODE), includes arming state.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">flags</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Flags as bitfield, reserved for future use.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="OPTICAL_FLOW" name="OPTICAL_FLOW">OPTICAL_FLOW (<a href="
      #OPTICAL_FLOW">
    #100
   </a>
   )
  </h2>
  <p class="description">Optical flow from a flow sensor (e.g. optical mouse sensor)</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (UNIX)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">sensor_id</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Sensor ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">flow_x</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Flow in pixels * 10 in x-sensor direction (dezi-pixels)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">flow_y</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Flow in pixels * 10 in y-sensor direction (dezi-pixels)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">flow_comp_m_x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Flow in meters in x-sensor direction, angular-speed compensated</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">flow_comp_m_y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Flow in meters in y-sensor direction, angular-speed compensated</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">quality</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Optical flow quality / confidence. 0: bad, 255: maximum quality</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ground_distance</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Ground distance in meters. Positive value: distance known. Negative value: Unknown distance</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">flow_rate_x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Flow rate in radians/second about X axis</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">flow_rate_y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Flow rate in radians/second about Y axis</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="GLOBAL_VISION_POSITION_ESTIMATE" name="GLOBAL_VISION_POSITION_ESTIMATE">GLOBAL_VISION_POSITION_ESTIMATE (<a href="
      #GLOBAL_VISION_POSITION_ESTIMATE">
    #101
   </a>
   )
  </h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds, synced to UNIX time or since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Global X position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Global Y position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Global Z position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">roll</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Roll angle in rad</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pitch</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Pitch angle in rad</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Yaw angle in rad</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="VISION_POSITION_ESTIMATE" name="VISION_POSITION_ESTIMATE">VISION_POSITION_ESTIMATE (<a href="
      #VISION_POSITION_ESTIMATE">
    #102
   </a>
   )
  </h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds, synced to UNIX time or since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Global X position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Global Y position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Global Z position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">roll</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Roll angle in rad</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pitch</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Pitch angle in rad</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Yaw angle in rad</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="VISION_SPEED_ESTIMATE" name="VISION_SPEED_ESTIMATE">VISION_SPEED_ESTIMATE (<a href="
      #VISION_SPEED_ESTIMATE">
    #103
   </a>
   )
  </h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds, synced to UNIX time or since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Global X speed</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Global Y speed</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Global Z speed</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="VICON_POSITION_ESTIMATE" name="VICON_POSITION_ESTIMATE">VICON_POSITION_ESTIMATE (<a href="
      #VICON_POSITION_ESTIMATE">
    #104
   </a>
   )
  </h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds, synced to UNIX time or since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Global X position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Global Y position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Global Z position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">roll</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Roll angle in rad</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pitch</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Pitch angle in rad</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Yaw angle in rad</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="HIGHRES_IMU" name="HIGHRES_IMU">HIGHRES_IMU (<a href="
      #HIGHRES_IMU">
    #105
   </a>
   )
  </h2>
  <p class="description">The IMU readings in SI units in NED body frame</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds, synced to UNIX time or since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xacc</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X acceleration (m/s^2)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yacc</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y acceleration (m/s^2)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zacc</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z acceleration (m/s^2)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xgyro</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Angular speed around X axis (rad / sec)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ygyro</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Angular speed around Y axis (rad / sec)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zgyro</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Angular speed around Z axis (rad / sec)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xmag</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X Magnetic field (Gauss)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ymag</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y Magnetic field (Gauss)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zmag</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z Magnetic field (Gauss)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">abs_pressure</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Absolute pressure in millibar</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">diff_pressure</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Differential pressure in millibar</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pressure_alt</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Altitude calculated from pressure</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">temperature</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Temperature in degrees celsius</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">fields_updated</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Bitmask for fields that have updated since last message, bit 0 = xacc, bit 12: temperature</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="OPTICAL_FLOW_RAD" name="OPTICAL_FLOW_RAD">OPTICAL_FLOW_RAD (<a href="
      #OPTICAL_FLOW_RAD">
    #106
   </a>
   )
  </h2>
  <p class="description">Optical flow from an angular rate flow sensor (e.g. PX4FLOW or mouse sensor)</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds, synced to UNIX time or since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">sensor_id</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Sensor ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">integration_time_us</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Integration time in microseconds. Divide integrated_x and integrated_y by the integration time to obtain average flow. The integration time also indicates the.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">integrated_x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Flow in radians around X axis (Sensor RH rotation about the X axis induces a positive flow. Sensor linear motion along the positive Y axis induces a negative flow.)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">integrated_y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Flow in radians around Y axis (Sensor RH rotation about the Y axis induces a positive flow. Sensor linear motion along the positive X axis induces a positive flow.)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">integrated_xgyro</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">RH rotation around X axis (rad)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">integrated_ygyro</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">RH rotation around Y axis (rad)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">integrated_zgyro</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">RH rotation around Z axis (rad)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">temperature</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Temperature * 100 in centi-degrees Celsius</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">quality</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Optical flow quality / confidence. 0: no valid flow, 255: maximum quality</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_delta_distance_us</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Time in microseconds since the distance was sampled.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">distance</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Distance to the center of the flow field in meters. Positive value (including zero): distance known. Negative value: Unknown distance.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="HIL_SENSOR" name="HIL_SENSOR">HIL_SENSOR (<a href="
      #HIL_SENSOR">
    #107
   </a>
   )
  </h2>
  <p class="description">The IMU readings in SI units in NED body frame</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds, synced to UNIX time or since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xacc</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X acceleration (m/s^2)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yacc</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y acceleration (m/s^2)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zacc</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z acceleration (m/s^2)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xgyro</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Angular speed around X axis in body frame (rad / sec)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ygyro</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Angular speed around Y axis in body frame (rad / sec)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zgyro</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Angular speed around Z axis in body frame (rad / sec)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xmag</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X Magnetic field (Gauss)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ymag</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y Magnetic field (Gauss)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zmag</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z Magnetic field (Gauss)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">abs_pressure</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Absolute pressure in millibar</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">diff_pressure</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Differential pressure (airspeed) in millibar</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pressure_alt</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Altitude calculated from pressure</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">temperature</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Temperature in degrees celsius</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">fields_updated</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Bitmask for fields that have updated since last message, bit 0 = xacc, bit 12: temperature, bit 31: full reset of attitude/position/velocities/etc was performed in sim.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SIM_STATE" name="SIM_STATE">SIM_STATE (<a href="
      #SIM_STATE">
    #108
   </a>
   )
  </h2>
  <p class="description">Status of simulation environment, if used</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">q1</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">True attitude quaternion component 1, w (1 in null-rotation)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">q2</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">True attitude quaternion component 2, x (0 in null-rotation)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">q3</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">True attitude quaternion component 3, y (0 in null-rotation)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">q4</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">True attitude quaternion component 4, z (0 in null-rotation)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">roll</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Attitude roll expressed as Euler angles, not recommended except for human-readable outputs</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pitch</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Attitude pitch expressed as Euler angles, not recommended except for human-readable outputs</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Attitude yaw expressed as Euler angles, not recommended except for human-readable outputs</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xacc</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X acceleration m/s/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yacc</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y acceleration m/s/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zacc</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z acceleration m/s/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xgyro</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Angular speed around X axis rad/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ygyro</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Angular speed around Y axis rad/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zgyro</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Angular speed around Z axis rad/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lat</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Latitude in degrees</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lon</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Longitude in degrees</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">alt</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Altitude in meters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">std_dev_horz</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Horizontal position standard deviation</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">std_dev_vert</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Vertical position standard deviation</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vn</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">True velocity in m/s in NORTH direction in earth-fixed NED frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ve</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">True velocity in m/s in EAST direction in earth-fixed NED frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vd</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">True velocity in m/s in DOWN direction in earth-fixed NED frame</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="RADIO_STATUS" name="RADIO_STATUS">RADIO_STATUS (<a href="
      #RADIO_STATUS">
    #109
   </a>
   )
  </h2>
  <p class="description">Status generated by radio and injected into MAVLink stream.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rssi</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Local signal strength</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">remrssi</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Remote signal strength</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">txbuf</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Remaining free buffer space in percent.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">noise</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Background noise level</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">remnoise</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Remote background noise level</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rxerrors</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Receive errors</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">fixed</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Count of error corrected packets</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="FILE_TRANSFER_PROTOCOL" name="FILE_TRANSFER_PROTOCOL">FILE_TRANSFER_PROTOCOL (<a href="
      #FILE_TRANSFER_PROTOCOL">
    #110
   </a>
   )
  </h2>
  <p class="description">File transfer message</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_network</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Network ID (0 for broadcast)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID (0 for broadcast)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID (0 for broadcast)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">payload</td>
     <td class="mavlink_type" valign="top">uint8_t[251]</td>
     <td class="mavlink_comment">Variable length payload. The length is defined by the remaining message length when subtracting the header and other fields.  The entire content of this block is opaque unless you understand any the encoding message_type.  The particular encoding used can be extension specific and might not always be documented as part of the mavlink specification.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="TIMESYNC" name="TIMESYNC">TIMESYNC (<a href="
      #TIMESYNC">
    #111
   </a>
   )
  </h2>
  <p class="description">Time synchronization message.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">tc1</td>
     <td class="mavlink_type" valign="top">int64_t</td>
     <td class="mavlink_comment">Time sync timestamp 1</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ts1</td>
     <td class="mavlink_type" valign="top">int64_t</td>
     <td class="mavlink_comment">Time sync timestamp 2</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="CAMERA_TRIGGER" name="CAMERA_TRIGGER">CAMERA_TRIGGER (<a href="
      #CAMERA_TRIGGER">
    #112
   </a>
   )
  </h2>
  <p class="description">Camera-IMU triggering and synchronisation message.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp for the image frame in microseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">seq</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Image frame sequence</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="HIL_GPS" name="HIL_GPS">HIL_GPS (<a href="
      #HIL_GPS">
    #113
   </a>
   )
  </h2>
  <p class="description">The global position, as returned by the Global Positioning System (GPS). This is
                 NOT the global position estimate of the sytem, but rather a RAW sensor value. See message GLOBAL_POSITION for the global position estimate. Coordinate frame is right-handed, Z-axis up (GPS frame).</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since UNIX epoch or microseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">fix_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">0-1: no fix, 2: 2D fix, 3: 3D fix. Some applications will not use the value of this field unless it is at least two, so always correctly fill in the fix.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lat</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude (WGS84), in degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lon</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude (WGS84), in degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">alt</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Altitude (AMSL, not WGS84), in meters * 1000 (positive for up)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">eph</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">GPS HDOP horizontal dilution of position in cm (m*100). If unknown, set to: 65535</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">epv</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">GPS VDOP vertical dilution of position in cm (m*100). If unknown, set to: 65535</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vel</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">GPS ground speed in cm/s. If unknown, set to: 65535</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vn</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">GPS velocity in cm/s in NORTH direction in earth-fixed NED frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ve</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">GPS velocity in cm/s in EAST direction in earth-fixed NED frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vd</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">GPS velocity in cm/s in DOWN direction in earth-fixed NED frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">cog</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Course over ground (NOT heading, but direction of movement) in degrees * 100, 0.0..359.99 degrees. If unknown, set to: 65535</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">satellites_visible</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Number of satellites visible. If unknown, set to 255</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="HIL_OPTICAL_FLOW" name="HIL_OPTICAL_FLOW">HIL_OPTICAL_FLOW (<a href="
      #HIL_OPTICAL_FLOW">
    #114
   </a>
   )
  </h2>
  <p class="description">Simulated optical flow from a flow sensor (e.g. PX4FLOW or optical mouse sensor)</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds, synced to UNIX time or since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">sensor_id</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Sensor ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">integration_time_us</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Integration time in microseconds. Divide integrated_x and integrated_y by the integration time to obtain average flow. The integration time also indicates the.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">integrated_x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Flow in radians around X axis (Sensor RH rotation about the X axis induces a positive flow. Sensor linear motion along the positive Y axis induces a negative flow.)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">integrated_y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Flow in radians around Y axis (Sensor RH rotation about the Y axis induces a positive flow. Sensor linear motion along the positive X axis induces a positive flow.)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">integrated_xgyro</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">RH rotation around X axis (rad)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">integrated_ygyro</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">RH rotation around Y axis (rad)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">integrated_zgyro</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">RH rotation around Z axis (rad)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">temperature</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Temperature * 100 in centi-degrees Celsius</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">quality</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Optical flow quality / confidence. 0: no valid flow, 255: maximum quality</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_delta_distance_us</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Time in microseconds since the distance was sampled.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">distance</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Distance to the center of the flow field in meters. Positive value (including zero): distance known. Negative value: Unknown distance.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="HIL_STATE_QUATERNION" name="HIL_STATE_QUATERNION">HIL_STATE_QUATERNION (<a href="
      #HIL_STATE_QUATERNION">
    #115
   </a>
   )
  </h2>
  <p class="description">Sent from simulation to autopilot, avoids in contrast to HIL_STATE singularities. This packet is useful for high throughput applications such as hardware in the loop simulations.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since UNIX epoch or microseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">attitude_quaternion</td>
     <td class="mavlink_type" valign="top">float[4]</td>
     <td class="mavlink_comment">Vehicle attitude expressed as normalized quaternion in w, x, y, z order (with 1 0 0 0 being the null-rotation)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rollspeed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Body frame roll / phi angular speed (rad/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pitchspeed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Body frame pitch / theta angular speed (rad/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yawspeed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Body frame yaw / psi angular speed (rad/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lat</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude, expressed as * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lon</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude, expressed as * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">alt</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Altitude in meters, expressed as * 1000 (millimeters)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vx</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Ground X Speed (Latitude), expressed as cm/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vy</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Ground Y Speed (Longitude), expressed as cm/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vz</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Ground Z Speed (Altitude), expressed as cm/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ind_airspeed</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Indicated airspeed, expressed as cm/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">true_airspeed</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">True airspeed, expressed as cm/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xacc</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">X acceleration (mg)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yacc</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Y acceleration (mg)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zacc</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Z acceleration (mg)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SCALED_IMU2" name="SCALED_IMU2">SCALED_IMU2 (<a href="
      #SCALED_IMU2">
    #116
   </a>
   )
  </h2>
  <p class="description">The RAW IMU readings for secondary 9DOF sensor setup. This message should contain the scaled values to the described units</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xacc</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">X acceleration (mg)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yacc</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Y acceleration (mg)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zacc</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Z acceleration (mg)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xgyro</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Angular speed around X axis (millirad /sec)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ygyro</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Angular speed around Y axis (millirad /sec)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zgyro</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Angular speed around Z axis (millirad /sec)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xmag</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">X Magnetic field (milli tesla)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ymag</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Y Magnetic field (milli tesla)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zmag</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Z Magnetic field (milli tesla)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="LOG_REQUEST_LIST" name="LOG_REQUEST_LIST">LOG_REQUEST_LIST (<a href="
      #LOG_REQUEST_LIST">
    #117
   </a>
   )
  </h2>
  <p class="description">Request a list of available logs. On some systems calling this may stop on-board logging until LOG_REQUEST_END is called.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">start</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">First log id (0 for first available)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">end</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Last log id (0xffff for last available)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="LOG_ENTRY" name="LOG_ENTRY">LOG_ENTRY (<a href="
      #LOG_ENTRY">
    #118
   </a>
   )
  </h2>
  <p class="description">Reply to LOG_REQUEST_LIST</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">id</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Log id</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">num_logs</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Total number of logs</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">last_log_num</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">High log number</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_utc</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">UTC timestamp of log in seconds since 1970, or 0 if not available</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">size</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Size of the log (may be approximate) in bytes</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="LOG_REQUEST_DATA" name="LOG_REQUEST_DATA">LOG_REQUEST_DATA (<a href="
      #LOG_REQUEST_DATA">
    #119
   </a>
   )
  </h2>
  <p class="description">Request a chunk of a log</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">id</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Log id (from LOG_ENTRY reply)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ofs</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Offset into the log</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">count</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Number of bytes</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="LOG_DATA" name="LOG_DATA">LOG_DATA (<a href="
      #LOG_DATA">
    #120
   </a>
   )
  </h2>
  <p class="description">Reply to LOG_REQUEST_DATA</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">id</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Log id (from LOG_ENTRY reply)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ofs</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Offset into the log</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">count</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Number of bytes (zero for end of log)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">data</td>
     <td class="mavlink_type" valign="top">uint8_t[90]</td>
     <td class="mavlink_comment">log data</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="LOG_ERASE" name="LOG_ERASE">LOG_ERASE (<a href="
      #LOG_ERASE">
    #121
   </a>
   )
  </h2>
  <p class="description">Erase all logs</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="LOG_REQUEST_END" name="LOG_REQUEST_END">LOG_REQUEST_END (<a href="
      #LOG_REQUEST_END">
    #122
   </a>
   )
  </h2>
  <p class="description">Stop log transfer and resume normal logging</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="GPS_INJECT_DATA" name="GPS_INJECT_DATA">GPS_INJECT_DATA (<a href="
      #GPS_INJECT_DATA">
    #123
   </a>
   )
  </h2>
  <p class="description">data for injecting into the onboard GPS (used for DGPS)</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">len</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">data length</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">data</td>
     <td class="mavlink_type" valign="top">uint8_t[110]</td>
     <td class="mavlink_comment">raw data (110 is enough for 12 satellites of RTCMv2)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="GPS2_RAW" name="GPS2_RAW">GPS2_RAW (<a href="
      #GPS2_RAW">
    #124
   </a>
   )
  </h2>
  <p class="description">Second GPS data. Coordinate frame is right-handed, Z-axis up (GPS frame).</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since UNIX epoch or microseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">fix_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">See the GPS_FIX_TYPE enum.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lat</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude (WGS84), in degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lon</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude (WGS84), in degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">alt</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Altitude (AMSL, not WGS84), in meters * 1000 (positive for up)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">eph</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">GPS HDOP horizontal dilution of position in cm (m*100). If unknown, set to: UINT16_MAX</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">epv</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">GPS VDOP vertical dilution of position in cm (m*100). If unknown, set to: UINT16_MAX</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vel</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">GPS ground speed (m/s * 100). If unknown, set to: UINT16_MAX</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">cog</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Course over ground (NOT heading, but direction of movement) in degrees * 100, 0.0..359.99 degrees. If unknown, set to: UINT16_MAX</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">satellites_visible</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Number of satellites visible. If unknown, set to 255</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">dgps_numch</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Number of DGPS satellites</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">dgps_age</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Age of DGPS info</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="POWER_STATUS" name="POWER_STATUS">POWER_STATUS (<a href="
      #POWER_STATUS">
    #125
   </a>
   )
  </h2>
  <p class="description">Power supply status</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">Vcc</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">5V rail voltage in millivolts</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">Vservo</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">servo rail voltage in millivolts</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">flags</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">power supply status flags (see MAV_POWER_STATUS enum)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SERIAL_CONTROL" name="SERIAL_CONTROL">SERIAL_CONTROL (<a href="
      #SERIAL_CONTROL">
    #126
   </a>
   )
  </h2>
  <p class="description">Control a serial port. This can be used for raw access to an onboard serial peripheral such as a GPS or telemetry radio. It is designed to make it possible to update the devices firmware via MAVLink messages or change the devices settings. A message with zero bytes can be used to change just the baudrate.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">device</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">See SERIAL_CONTROL_DEV enum</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">flags</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">See SERIAL_CONTROL_FLAG enum</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">timeout</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Timeout for reply data in milliseconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">baudrate</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Baudrate of transfer. Zero means no change.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">count</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">how many bytes in this transfer</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">data</td>
     <td class="mavlink_type" valign="top">uint8_t[70]</td>
     <td class="mavlink_comment">serial data</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="GPS_RTK" name="GPS_RTK">GPS_RTK (<a href="
      #GPS_RTK">
    #127
   </a>
   )
  </h2>
  <p class="description">RTK GPS data. Gives information on the relative baseline calculation the GPS is reporting</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_last_baseline_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Time since boot of last baseline message received in ms.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rtk_receiver_id</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Identification of connected RTK receiver.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">wn</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">GPS Week Number of last baseline</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">tow</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">GPS Time of Week of last baseline</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rtk_health</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">GPS-specific health report for RTK data.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rtk_rate</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Rate of baseline messages being received by GPS, in HZ</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">nsats</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Current number of sats used for RTK calculation.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">baseline_coords_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Coordinate system of baseline. 0 == ECEF, 1 == NED</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">baseline_a_mm</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Current baseline in ECEF x or NED north component in mm.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">baseline_b_mm</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Current baseline in ECEF y or NED east component in mm.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">baseline_c_mm</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Current baseline in ECEF z or NED down component in mm.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">accuracy</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Current estimate of baseline accuracy.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">iar_num_hypotheses</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Current number of integer ambiguity hypotheses.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="GPS2_RTK" name="GPS2_RTK">GPS2_RTK (<a href="
      #GPS2_RTK">
    #128
   </a>
   )
  </h2>
  <p class="description">RTK GPS data. Gives information on the relative baseline calculation the GPS is reporting</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_last_baseline_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Time since boot of last baseline message received in ms.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rtk_receiver_id</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Identification of connected RTK receiver.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">wn</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">GPS Week Number of last baseline</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">tow</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">GPS Time of Week of last baseline</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rtk_health</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">GPS-specific health report for RTK data.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rtk_rate</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Rate of baseline messages being received by GPS, in HZ</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">nsats</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Current number of sats used for RTK calculation.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">baseline_coords_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Coordinate system of baseline. 0 == ECEF, 1 == NED</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">baseline_a_mm</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Current baseline in ECEF x or NED north component in mm.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">baseline_b_mm</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Current baseline in ECEF y or NED east component in mm.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">baseline_c_mm</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Current baseline in ECEF z or NED down component in mm.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">accuracy</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Current estimate of baseline accuracy.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">iar_num_hypotheses</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Current number of integer ambiguity hypotheses.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SCALED_IMU3" name="SCALED_IMU3">SCALED_IMU3 (<a href="
      #SCALED_IMU3">
    #129
   </a>
   )
  </h2>
  <p class="description">The RAW IMU readings for 3rd 9DOF sensor setup. This message should contain the scaled values to the described units</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xacc</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">X acceleration (mg)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yacc</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Y acceleration (mg)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zacc</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Z acceleration (mg)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xgyro</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Angular speed around X axis (millirad /sec)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ygyro</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Angular speed around Y axis (millirad /sec)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zgyro</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Angular speed around Z axis (millirad /sec)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">xmag</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">X Magnetic field (milli tesla)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ymag</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Y Magnetic field (milli tesla)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">zmag</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Z Magnetic field (milli tesla)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="DATA_TRANSMISSION_HANDSHAKE" name="DATA_TRANSMISSION_HANDSHAKE">DATA_TRANSMISSION_HANDSHAKE (<a href="
      #DATA_TRANSMISSION_HANDSHAKE">
    #130
   </a>
   )
  </h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">type of requested/acknowledged data (as defined in ENUM DATA_TYPES in mavlink/include/mavlink_types.h)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">size</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">total data size in bytes (set on ACK only)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">width</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Width of a matrix or image</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">height</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Height of a matrix or image</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">packets</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">number of packets beeing sent (set on ACK only)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">payload</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">payload size per packet (normally 253 byte, see DATA field size in message ENCAPSULATED_DATA) (set on ACK only)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">jpg_quality</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">JPEG quality out of [1,100]</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="ENCAPSULATED_DATA" name="ENCAPSULATED_DATA">ENCAPSULATED_DATA (<a href="
      #ENCAPSULATED_DATA">
    #131
   </a>
   )
  </h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">seqnr</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">sequence number (starting with 0 on every transmission)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">data</td>
     <td class="mavlink_type" valign="top">uint8_t[253]</td>
     <td class="mavlink_comment">image data bytes</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="DISTANCE_SENSOR" name="DISTANCE_SENSOR">DISTANCE_SENSOR (<a href="
      #DISTANCE_SENSOR">
    #132
   </a>
   )
  </h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Time since system boot</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">min_distance</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Minimum distance the sensor can measure in centimeters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">max_distance</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Maximum distance the sensor can measure in centimeters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">current_distance</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Current distance reading</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Type from MAV_DISTANCE_SENSOR enum.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">id</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Onboard ID of the sensor</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">orientation</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Direction the sensor faces from MAV_SENSOR_ORIENTATION enum. downward-facing: ROTATION_PITCH_270, upward-facing: ROTATION_PITCH_90, backward-facing: ROTATION_PITCH_180, forward-facing: ROTATION_NONE, left-facing: ROTATION_YAW_90, right-facing: ROTATION_YAW_270</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">covariance</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Measurement covariance in centimeters, 0 for unknown / invalid readings</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="TERRAIN_REQUEST" name="TERRAIN_REQUEST">TERRAIN_REQUEST (<a href="
      #TERRAIN_REQUEST">
    #133
   </a>
   )
  </h2>
  <p class="description">Request for terrain data and terrain status</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lat</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude of SW corner of first grid (degrees *10^7)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lon</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude of SW corner of first grid (in degrees *10^7)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">grid_spacing</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Grid spacing in meters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mask</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Bitmask of requested 4x4 grids (row major 8x7 array of grids, 56 bits)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="TERRAIN_DATA" name="TERRAIN_DATA">TERRAIN_DATA (<a href="
      #TERRAIN_DATA">
    #134
   </a>
   )
  </h2>
  <p class="description">Terrain data sent from GCS. The lat/lon and grid_spacing must be the same as a lat/lon from a TERRAIN_REQUEST</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lat</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude of SW corner of first grid (degrees *10^7)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lon</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude of SW corner of first grid (in degrees *10^7)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">grid_spacing</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Grid spacing in meters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">gridbit</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">bit within the terrain request mask</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">data</td>
     <td class="mavlink_type" valign="top">int16_t[16]</td>
     <td class="mavlink_comment">Terrain data in meters AMSL</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="TERRAIN_CHECK" name="TERRAIN_CHECK">TERRAIN_CHECK (<a href="
      #TERRAIN_CHECK">
    #135
   </a>
   )
  </h2>
  <p class="description">Request that the vehicle report terrain height at the given location. Used by GCS to check if vehicle has all terrain data needed for a mission.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lat</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude (degrees *10^7)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lon</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude (degrees *10^7)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="TERRAIN_REPORT" name="TERRAIN_REPORT">TERRAIN_REPORT (<a href="
      #TERRAIN_REPORT">
    #136
   </a>
   )
  </h2>
  <p class="description">Response from a TERRAIN_CHECK request</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lat</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude (degrees *10^7)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lon</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude (degrees *10^7)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">spacing</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">grid spacing (zero if terrain at this location unavailable)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">terrain_height</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Terrain height in meters AMSL</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">current_height</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Current vehicle height above lat/lon terrain height (meters)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pending</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Number of 4x4 terrain blocks waiting to be received or read from disk</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">loaded</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Number of 4x4 terrain blocks in memory</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SCALED_PRESSURE2" name="SCALED_PRESSURE2">SCALED_PRESSURE2 (<a href="
      #SCALED_PRESSURE2">
    #137
   </a>
   )
  </h2>
  <p class="description">Barometer readings for 2nd barometer</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">press_abs</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Absolute pressure (hectopascal)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">press_diff</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Differential pressure 1 (hectopascal)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">temperature</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Temperature measurement (0.01 degrees celsius)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="ATT_POS_MOCAP" name="ATT_POS_MOCAP">ATT_POS_MOCAP (<a href="
      #ATT_POS_MOCAP">
    #138
   </a>
   )
  </h2>
  <p class="description">Motion capture attitude and position</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (micros since boot or Unix epoch)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">q</td>
     <td class="mavlink_type" valign="top">float[4]</td>
     <td class="mavlink_comment">Attitude quaternion (w, x, y, z order, zero-rotation is 1, 0, 0, 0)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X position in meters (NED)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y position in meters (NED)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z position in meters (NED)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SET_ACTUATOR_CONTROL_TARGET" name="SET_ACTUATOR_CONTROL_TARGET">SET_ACTUATOR_CONTROL_TARGET (<a href="
      #SET_ACTUATOR_CONTROL_TARGET">
    #139
   </a>
   )
  </h2>
  <p class="description">Set the vehicle attitude and body angular rates.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (micros since boot or Unix epoch)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">group_mlx</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Actuator group. The "_mlx" indicates this is a multi-instance message and a MAVLink parser should use this field to difference between instances.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">controls</td>
     <td class="mavlink_type" valign="top">float[8]</td>
     <td class="mavlink_comment">Actuator controls. Normed to -1..+1 where 0 is neutral position. Throttle for single rotation direction motors is 0..1, negative range for reverse direction. Standard mapping for attitude controls (group 0): (index 0-7): roll, pitch, yaw, throttle, flaps, spoilers, airbrakes, landing gear. Load a pass-through mixer to repurpose them as generic outputs.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="ACTUATOR_CONTROL_TARGET" name="ACTUATOR_CONTROL_TARGET">ACTUATOR_CONTROL_TARGET (<a href="
      #ACTUATOR_CONTROL_TARGET">
    #140
   </a>
   )
  </h2>
  <p class="description">Set the vehicle attitude and body angular rates.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (micros since boot or Unix epoch)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">group_mlx</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Actuator group. The "_mlx" indicates this is a multi-instance message and a MAVLink parser should use this field to difference between instances.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">controls</td>
     <td class="mavlink_type" valign="top">float[8]</td>
     <td class="mavlink_comment">Actuator controls. Normed to -1..+1 where 0 is neutral position. Throttle for single rotation direction motors is 0..1, negative range for reverse direction. Standard mapping for attitude controls (group 0): (index 0-7): roll, pitch, yaw, throttle, flaps, spoilers, airbrakes, landing gear. Load a pass-through mixer to repurpose them as generic outputs.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="ALTITUDE" name="ALTITUDE">ALTITUDE (<a href="
      #ALTITUDE">
    #141
   </a>
   )
  </h2>
  <p class="description">The current system altitude.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (micros since boot or Unix epoch)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">altitude_monotonic</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">This altitude measure is initialized on system boot and monotonic (it is never reset, but represents the local altitude change). The only guarantee on this field is that it will never be reset and is consistent within a flight. The recommended value for this field is the uncorrected barometric altitude at boot time. This altitude will also drift and vary between flights.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">altitude_amsl</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">This altitude measure is strictly above mean sea level and might be non-monotonic (it might reset on events like GPS lock or when a new QNH value is set). It should be the altitude to which global altitude waypoints are compared to. Note that it is *not* the GPS altitude, however, most GPS modules already output AMSL by default and not the WGS84 altitude.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">altitude_local</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">This is the local altitude in the local coordinate frame. It is not the altitude above home, but in reference to the coordinate origin (0, 0, 0). It is up-positive.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">altitude_relative</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">This is the altitude above the home position. It resets on each change of the current home position.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">altitude_terrain</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">This is the altitude above terrain. It might be fed by a terrain database or an altimeter. Values smaller than -1000 should be interpreted as unknown.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">bottom_clearance</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">This is not the altitude, but the clear space below the system according to the fused clearance estimate. It generally should max out at the maximum range of e.g. the laser altimeter. It is generally a moving target. A negative value indicates no measurement available.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="RESOURCE_REQUEST" name="RESOURCE_REQUEST">RESOURCE_REQUEST (<a href="
      #RESOURCE_REQUEST">
    #142
   </a>
   )
  </h2>
  <p class="description">The autopilot is requesting a resource (file, binary, other type of data)</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">request_id</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Request ID. This ID should be re-used when sending back URI contents</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">uri_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">The type of requested URI. 0 = a file via URL. 1 = a UAVCAN binary</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">uri</td>
     <td class="mavlink_type" valign="top">uint8_t[120]</td>
     <td class="mavlink_comment">The requested unique resource identifier (URI). It is not necessarily a straight domain name (depends on the URI type enum)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">transfer_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">The way the autopilot wants to receive the URI. 0 = MAVLink FTP. 1 = binary stream.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">storage</td>
     <td class="mavlink_type" valign="top">uint8_t[120]</td>
     <td class="mavlink_comment">The storage path the autopilot wants the URI to be stored in. Will only be valid if the transfer_type has a storage associated (e.g. MAVLink FTP).</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SCALED_PRESSURE3" name="SCALED_PRESSURE3">SCALED_PRESSURE3 (<a href="
      #SCALED_PRESSURE3">
    #143
   </a>
   )
  </h2>
  <p class="description">Barometer readings for 3rd barometer</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">press_abs</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Absolute pressure (hectopascal)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">press_diff</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Differential pressure 1 (hectopascal)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">temperature</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Temperature measurement (0.01 degrees celsius)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="FOLLOW_TARGET" name="FOLLOW_TARGET">FOLLOW_TARGET (<a href="
      #FOLLOW_TARGET">
    #144
   </a>
   )
  </h2>
  <p class="description">current motion information from a designated system</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">timestamp</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp in milliseconds since system boot</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">est_capabilities</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">bit positions for tracker reporting capabilities (POS = 0, VEL = 1, ACCEL = 2, ATT + RATES = 3)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lat</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude (WGS84), in degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lon</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude (WGS84), in degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">alt</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">AMSL, in meters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vel</td>
     <td class="mavlink_type" valign="top">float[3]</td>
     <td class="mavlink_comment">target velocity (0,0,0) for unknown</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">acc</td>
     <td class="mavlink_type" valign="top">float[3]</td>
     <td class="mavlink_comment">linear target acceleration (0,0,0) for unknown</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">attitude_q</td>
     <td class="mavlink_type" valign="top">float[4]</td>
     <td class="mavlink_comment">
      (1 0 0 0 for unknown)
     </td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rates</td>
     <td class="mavlink_type" valign="top">float[3]</td>
     <td class="mavlink_comment">
      (0 0 0 for unknown)
     </td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">position_cov</td>
     <td class="mavlink_type" valign="top">float[3]</td>
     <td class="mavlink_comment">eph epv</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">custom_state</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">button states or switches of a tracker device</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="CONTROL_SYSTEM_STATE" name="CONTROL_SYSTEM_STATE">CONTROL_SYSTEM_STATE (<a href="
      #CONTROL_SYSTEM_STATE">
    #146
   </a>
   )
  </h2>
  <p class="description">The smoothed, monotonic system state used to feed the control loops of the system.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (micros since boot or Unix epoch)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x_acc</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X acceleration in body frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y_acc</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y acceleration in body frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z_acc</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z acceleration in body frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x_vel</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X velocity in body frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y_vel</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y velocity in body frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z_vel</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z velocity in body frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x_pos</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X position in local frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y_pos</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y position in local frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z_pos</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z position in local frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">airspeed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Airspeed, set to -1 if unknown</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vel_variance</td>
     <td class="mavlink_type" valign="top">float[3]</td>
     <td class="mavlink_comment">Variance of body velocity estimate</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pos_variance</td>
     <td class="mavlink_type" valign="top">float[3]</td>
     <td class="mavlink_comment">Variance in local position</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">q</td>
     <td class="mavlink_type" valign="top">float[4]</td>
     <td class="mavlink_comment">The attitude, represented as Quaternion</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">roll_rate</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Angular rate in roll axis</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pitch_rate</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Angular rate in pitch axis</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw_rate</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Angular rate in yaw axis</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="BATTERY_STATUS" name="BATTERY_STATUS">BATTERY_STATUS (<a href="
      #BATTERY_STATUS">
    #147
   </a>
   )
  </h2>
  <p class="description">Battery information</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">id</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Battery ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">battery_function</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Function of the battery</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Type (chemistry) of the battery</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">temperature</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Temperature of the battery in centi-degrees celsius. INT16_MAX for unknown temperature.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">voltages</td>
     <td class="mavlink_type" valign="top">uint16_t[10]</td>
     <td class="mavlink_comment">Battery voltage of cells, in millivolts (1 = 1 millivolt). Cells above the valid cell count for this battery should have the UINT16_MAX value.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">current_battery</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Battery current, in 10*milliamperes (1 = 10 milliampere), -1: autopilot does not measure the current</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">current_consumed</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Consumed charge, in milliampere hours (1 = 1 mAh), -1: autopilot does not provide mAh consumption estimate</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">energy_consumed</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Consumed energy, in HectoJoules (intergrated U*I*dt)  (1 = 100 Joule), -1: autopilot does not provide energy consumption estimate</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">battery_remaining</td>
     <td class="mavlink_type" valign="top">int8_t</td>
     <td class="mavlink_comment">Remaining battery energy: (0%: 0, 100%: 100), -1: autopilot does not estimate the remaining battery</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="AUTOPILOT_VERSION" name="AUTOPILOT_VERSION">AUTOPILOT_VERSION (<a href="
      #AUTOPILOT_VERSION">
    #148
   </a>
   )
  </h2>
  <p class="description">Version and capability of autopilot software</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">capabilities</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">bitmask of capabilities (see MAV_PROTOCOL_CAPABILITY enum)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">flight_sw_version</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Firmware version number</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">middleware_sw_version</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Middleware version number</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">os_sw_version</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Operating system version number</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">board_version</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">HW / board version (last 8 bytes should be silicon ID, if any)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">flight_custom_version</td>
     <td class="mavlink_type" valign="top">uint8_t[8]</td>
     <td class="mavlink_comment">Custom version field, commonly the first 8 bytes of the git hash. This is not an unique identifier, but should allow to identify the commit using the main version number even for very large code bases.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">middleware_custom_version</td>
     <td class="mavlink_type" valign="top">uint8_t[8]</td>
     <td class="mavlink_comment">Custom version field, commonly the first 8 bytes of the git hash. This is not an unique identifier, but should allow to identify the commit using the main version number even for very large code bases.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">os_custom_version</td>
     <td class="mavlink_type" valign="top">uint8_t[8]</td>
     <td class="mavlink_comment">Custom version field, commonly the first 8 bytes of the git hash. This is not an unique identifier, but should allow to identify the commit using the main version number even for very large code bases.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vendor_id</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">ID of the board vendor</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">product_id</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">ID of the product</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">uid</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">UID if provided by hardware (see uid2)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">uid2</td>
     <td class="mavlink_type" valign="top">uint8_t[18]</td>
     <td class="mavlink_comment">UID if provided by hardware (supersedes the uid field. If this is non-zero, use this field, otherwise use uid)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="LANDING_TARGET" name="LANDING_TARGET">LANDING_TARGET (<a href="
      #LANDING_TARGET">
    #149
   </a>
   )
  </h2>
  <p class="description">The location of a landing area captured from a downward facing camera</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (micros since boot or Unix epoch)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_num</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">The ID of the target if multiple targets are present</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">frame</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">MAV_FRAME enum specifying the whether the following feilds are earth-frame, body-frame, etc.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">angle_x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X-axis angular offset (in radians) of the target from the center of the image</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">angle_y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y-axis angular offset (in radians) of the target from the center of the image</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">distance</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Distance to the target from the vehicle in meters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">size_x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Size in radians of target along x-axis</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">size_y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Size in radians of target along y-axis</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">X Position of the landing target on MAV_FRAME</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Y Position of the landing target on MAV_FRAME</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Z Position of the landing target on MAV_FRAME</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">q</td>
     <td class="mavlink_type" valign="top">float[4]</td>
     <td class="mavlink_comment">Quaternion of landing target orientation (w, x, y, z order, zero-rotation is 1, 0, 0, 0)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">LANDING_TARGET_TYPE enum specifying the type of landing target</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">position_valid</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Boolean indicating known position (1) or default unkown position (0), for validation of positioning of the landing target</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="ESTIMATOR_STATUS" name="ESTIMATOR_STATUS">ESTIMATOR_STATUS (<a href="
      #ESTIMATOR_STATUS">
    #230
   </a>
   )
  </h2>
  <p class="description">Estimator status message including flags, innovation test ratios and estimated accuracies. The flags message is an integer bitmask containing information on which EKF outputs are valid. See the ESTIMATOR_STATUS_FLAGS enum definition for further information. The innovaton test ratios show the magnitude of the sensor innovation divided by the innovation check threshold. Under normal operation the innovaton test ratios should be below 0.5 with occasional values up to 1.0. Values greater than 1.0 should be rare under normal operation and indicate that a measurement has been rejected by the filter. The user should be notified if an innovation test ratio greater than 1.0 is recorded. Notifications for values in the range between 0.5 and 1.0 should be optional and controllable by the user.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (micros since boot or Unix epoch)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">flags</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Integer bitmask indicating which EKF outputs are valid. See definition for ESTIMATOR_STATUS_FLAGS.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vel_ratio</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Velocity innovation test ratio</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pos_horiz_ratio</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Horizontal position innovation test ratio</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pos_vert_ratio</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Vertical position innovation test ratio</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mag_ratio</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Magnetometer innovation test ratio</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">hagl_ratio</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Height above terrain innovation test ratio</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">tas_ratio</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">True airspeed innovation test ratio</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pos_horiz_accuracy</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Horizontal position 1-STD accuracy relative to the EKF local origin (m)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pos_vert_accuracy</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Vertical position 1-STD accuracy relative to the EKF local origin (m)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="WIND_COV" name="WIND_COV">WIND_COV (<a href="
      #WIND_COV">
    #231
   </a>
   )
  </h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (micros since boot or Unix epoch)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">wind_x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Wind in X (NED) direction in m/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">wind_y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Wind in Y (NED) direction in m/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">wind_z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Wind in Z (NED) direction in m/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">var_horiz</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Variability of the wind in XY. RMS of a 1 Hz lowpassed wind estimate.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">var_vert</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Variability of the wind in Z. RMS of a 1 Hz lowpassed wind estimate.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">wind_alt</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">AMSL altitude (m) this measurement was taken at</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">horiz_accuracy</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Horizontal speed 1-STD accuracy</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vert_accuracy</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Vertical speed 1-STD accuracy</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="GPS_INPUT" name="GPS_INPUT">GPS_INPUT (<a href="
      #GPS_INPUT">
    #232
   </a>
   )
  </h2>
  <p class="description">GPS sensor input message.  This is a raw sensor value sent by the GPS. This is NOT the global position estimate of the sytem.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (micros since boot or Unix epoch)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">gps_id</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">ID of the GPS for multiple GPS inputs</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ignore_flags</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Flags indicating which fields to ignore (see GPS_INPUT_IGNORE_FLAGS enum).  All other fields must be provided.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_week_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">GPS time (milliseconds from start of GPS week)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_week</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">GPS week number</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">fix_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">0-1: no fix, 2: 2D fix, 3: 3D fix. 4: 3D with DGPS. 5: 3D with RTK</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lat</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude (WGS84), in degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lon</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude (WGS84), in degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">alt</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Altitude (AMSL, not WGS84), in m (positive for up)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">hdop</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">GPS HDOP horizontal dilution of position in m</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vdop</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">GPS VDOP vertical dilution of position in m</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vn</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">GPS velocity in m/s in NORTH direction in earth-fixed NED frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ve</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">GPS velocity in m/s in EAST direction in earth-fixed NED frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vd</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">GPS velocity in m/s in DOWN direction in earth-fixed NED frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">speed_accuracy</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">GPS speed accuracy in m/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">horiz_accuracy</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">GPS horizontal accuracy in m</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vert_accuracy</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">GPS vertical accuracy in m</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">satellites_visible</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Number of satellites visible.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="GPS_RTCM_DATA" name="GPS_RTCM_DATA">GPS_RTCM_DATA (<a href="
      #GPS_RTCM_DATA">
    #233
   </a>
   )
  </h2>
  <p class="description">RTCM message for injecting into the onboard GPS (used for DGPS)</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">flags</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">LSB: 1 means message is fragmented, next 2 bits are the fragment ID, the remaining 5 bits are used for the sequence ID. Messages are only to be flushed to the GPS when the entire message has been reconstructed on the autopilot. The fragment ID specifies which order the fragments should be assembled into a buffer, while the sequence ID is used to detect a mismatch between different buffers. The buffer is considered fully reconstructed when either all 4 fragments are present, or all the fragments before the first fragment with a non full payload is received. This management is used to ensure that normal GPS operation doesn't corrupt RTCM data, and to recover from a unreliable transport delivery order.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">len</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">data length</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">data</td>
     <td class="mavlink_type" valign="top">uint8_t[180]</td>
     <td class="mavlink_comment">RTCM message (may be fragmented)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="HIGH_LATENCY" name="HIGH_LATENCY">HIGH_LATENCY (<a href="
      #HIGH_LATENCY">
    #234
   </a>
   )
  </h2>
  <p class="description">Message appropriate for high latency connections like Iridium</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">base_mode</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System mode bitfield, see MAV_MODE_FLAG ENUM in mavlink/include/mavlink_types.h</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">custom_mode</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">A bitfield for use for autopilot-specific flags.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">landed_state</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">The landed state. Is set to MAV_LANDED_STATE_UNDEFINED if landed state is unknown.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">roll</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">roll (centidegrees)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pitch</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">pitch (centidegrees)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">heading</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">heading (centidegrees)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">throttle</td>
     <td class="mavlink_type" valign="top">int8_t</td>
     <td class="mavlink_comment">throttle (percentage)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">heading_sp</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">heading setpoint (centidegrees)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">latitude</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude, expressed as degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">longitude</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude, expressed as degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">altitude_amsl</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Altitude above mean sea level (meters)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">altitude_sp</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Altitude setpoint relative to the home position (meters)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">airspeed</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">airspeed (m/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">airspeed_sp</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">airspeed setpoint (m/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">groundspeed</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">groundspeed (m/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">climb_rate</td>
     <td class="mavlink_type" valign="top">int8_t</td>
     <td class="mavlink_comment">climb rate (m/s)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">gps_nsat</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Number of satellites visible. If unknown, set to 255</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">gps_fix_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">See the GPS_FIX_TYPE enum.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">battery_remaining</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Remaining battery (percentage)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">temperature</td>
     <td class="mavlink_type" valign="top">int8_t</td>
     <td class="mavlink_comment">Autopilot temperature (degrees C)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">temperature_air</td>
     <td class="mavlink_type" valign="top">int8_t</td>
     <td class="mavlink_comment">Air temperature (degrees C) from airspeed sensor</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">failsafe</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">failsafe (each bit represents a failsafe where 0=ok, 1=failsafe active (bit0:RC, bit1:batt, bit2:GPS, bit3:GCS, bit4:fence)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">wp_num</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">current waypoint number</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">wp_distance</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">distance to target (meters)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="VIBRATION" name="VIBRATION">VIBRATION (<a href="
      #VIBRATION">
    #241
   </a>
   )
  </h2>
  <p class="description">Vibration levels and accelerometer clipping</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (micros since boot or Unix epoch)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vibration_x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Vibration levels on X-axis</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vibration_y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Vibration levels on Y-axis</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vibration_z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Vibration levels on Z-axis</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">clipping_0</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">first accelerometer clipping count</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">clipping_1</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">second accelerometer clipping count</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">clipping_2</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">third accelerometer clipping count</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="HOME_POSITION" name="HOME_POSITION">HOME_POSITION (<a href="
      #HOME_POSITION">
    #242
   </a>
   )
  </h2>
  <p class="description">This message can be requested by sending the MAV_CMD_GET_HOME_POSITION command. The position the system will return to and land on. The position is set automatically by the system during the takeoff in case it was not explicitely set by the operator before or after. The position the system will return to and land on. The global and local positions encode the position in the respective coordinate frames, while the q parameter encodes the orientation of the surface. Under normal conditions it describes the heading and terrain slope, which can be used by the aircraft to adjust the approach. The approach 3D vector describes the point to which the system should fly in normal flight mode and then perform a landing sequence along the vector.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">latitude</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude (WGS84), in degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">longitude</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude (WGS84, in degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">altitude</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Altitude (AMSL), in meters * 1000 (positive for up)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Local X position of this position in the local coordinate frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Local Y position of this position in the local coordinate frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Local Z position of this position in the local coordinate frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">q</td>
     <td class="mavlink_type" valign="top">float[4]</td>
     <td class="mavlink_comment">World to surface normal and heading transformation of the takeoff position. Used to indicate the heading and slope of the ground</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">approach_x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Local X position of the end of the approach vector. Multicopters should set this position based on their takeoff path. Grass-landing fixed wing aircraft should set it the same way as multicopters. Runway-landing fixed wing aircraft should set it to the opposite direction of the takeoff, assuming the takeoff happened from the threshold / touchdown zone.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">approach_y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Local Y position of the end of the approach vector. Multicopters should set this position based on their takeoff path. Grass-landing fixed wing aircraft should set it the same way as multicopters. Runway-landing fixed wing aircraft should set it to the opposite direction of the takeoff, assuming the takeoff happened from the threshold / touchdown zone.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">approach_z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Local Z position of the end of the approach vector. Multicopters should set this position based on their takeoff path. Grass-landing fixed wing aircraft should set it the same way as multicopters. Runway-landing fixed wing aircraft should set it to the opposite direction of the takeoff, assuming the takeoff happened from the threshold / touchdown zone.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since UNIX epoch or microseconds since system boot)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SET_HOME_POSITION" name="SET_HOME_POSITION">SET_HOME_POSITION (<a href="
      #SET_HOME_POSITION">
    #243
   </a>
   )
  </h2>
  <p class="description">The position the system will return to and land on. The position is set automatically by the system during the takeoff in case it was not explicitely set by the operator before or after. The global and local positions encode the position in the respective coordinate frames, while the q parameter encodes the orientation of the surface. Under normal conditions it describes the heading and terrain slope, which can be used by the aircraft to adjust the approach. The approach 3D vector describes the point to which the system should fly in normal flight mode and then perform a landing sequence along the vector.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">latitude</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude (WGS84), in degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">longitude</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude (WGS84, in degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">altitude</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Altitude (AMSL), in meters * 1000 (positive for up)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Local X position of this position in the local coordinate frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Local Y position of this position in the local coordinate frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Local Z position of this position in the local coordinate frame</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">q</td>
     <td class="mavlink_type" valign="top">float[4]</td>
     <td class="mavlink_comment">World to surface normal and heading transformation of the takeoff position. Used to indicate the heading and slope of the ground</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">approach_x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Local X position of the end of the approach vector. Multicopters should set this position based on their takeoff path. Grass-landing fixed wing aircraft should set it the same way as multicopters. Runway-landing fixed wing aircraft should set it to the opposite direction of the takeoff, assuming the takeoff happened from the threshold / touchdown zone.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">approach_y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Local Y position of the end of the approach vector. Multicopters should set this position based on their takeoff path. Grass-landing fixed wing aircraft should set it the same way as multicopters. Runway-landing fixed wing aircraft should set it to the opposite direction of the takeoff, assuming the takeoff happened from the threshold / touchdown zone.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">approach_z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Local Z position of the end of the approach vector. Multicopters should set this position based on their takeoff path. Grass-landing fixed wing aircraft should set it the same way as multicopters. Runway-landing fixed wing aircraft should set it to the opposite direction of the takeoff, assuming the takeoff happened from the threshold / touchdown zone.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since UNIX epoch or microseconds since system boot)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MESSAGE_INTERVAL" name="MESSAGE_INTERVAL">MESSAGE_INTERVAL (<a href="
      #MESSAGE_INTERVAL">
    #244
   </a>
   )
  </h2>
  <p class="description">This interface replaces DATA_STREAM</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">message_id</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">The ID of the requested MAVLink message. v1.0 is limited to 254 messages.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">interval_us</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">The interval between two messages, in microseconds. A value of -1 indicates this stream is disabled, 0 indicates it is not available, &gt; 0 indicates the interval at which it is sent.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="EXTENDED_SYS_STATE" name="EXTENDED_SYS_STATE">EXTENDED_SYS_STATE (<a href="
      #EXTENDED_SYS_STATE">
    #245
   </a>
   )
  </h2>
  <p class="description">Provides state for additional features</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vtol_state</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">The VTOL state if applicable. Is set to MAV_VTOL_STATE_UNDEFINED if UAV is not in VTOL configuration.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">landed_state</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">The landed state. Is set to MAV_LANDED_STATE_UNDEFINED if landed state is unknown.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="ADSB_VEHICLE" name="ADSB_VEHICLE">ADSB_VEHICLE (<a href="
      #ADSB_VEHICLE">
    #246
   </a>
   )
  </h2>
  <p class="description">The location and information of an ADSB vehicle</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ICAO_address</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">ICAO address</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lat</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude, expressed as degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lon</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude, expressed as degrees * 1E7</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">altitude_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Type from ADSB_ALTITUDE_TYPE enum</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">altitude</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Altitude(ASL) in millimeters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">heading</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Course over ground in centidegrees</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">hor_velocity</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">The horizontal velocity in centimeters/second</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ver_velocity</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">The vertical velocity in centimeters/second, positive is up</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">callsign</td>
     <td class="mavlink_type" valign="top">char[9]</td>
     <td class="mavlink_comment">The callsign, 8+null</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">emitter_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Type from ADSB_EMITTER_TYPE enum</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">tslc</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Time since last communication in seconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">flags</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Flags to indicate various statuses including valid data fields</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">squawk</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Squawk code</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="COLLISION" name="COLLISION">COLLISION (<a href="
      #COLLISION">
    #247
   </a>
   )
  </h2>
  <p class="description">Information about a potential collision</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">src</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Collision data source</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">id</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Unique identifier, domain based on src field</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">action</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Action that is being taken to avoid this collision</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">threat_level</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">How concerned the aircraft is about this collision</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_to_minimum_delta</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Estimated time until collision occurs (seconds)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">altitude_minimum_delta</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Closest vertical distance in meters between vehicle and object</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">horizontal_minimum_delta</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Closest horizontal distance in meteres between vehicle and object</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="V2_EXTENSION" name="V2_EXTENSION">V2_EXTENSION (<a href="
      #V2_EXTENSION">
    #248
   </a>
   )
  </h2>
  <p class="description">Message implementing parts of the V2 payload specs in V1 frames for transitional support.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_network</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Network ID (0 for broadcast)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID (0 for broadcast)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID (0 for broadcast)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">message_type</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">A code that identifies the software component that understands this message (analogous to usb device classes or mime type strings).  If this code is less than 32768, it is considered a 'registered' protocol extension and the corresponding entry should be added to https://github.com/mavlink/mavlink/extension-message-ids.xml.  Software creators can register blocks of message IDs as needed (useful for GCS specific metadata, etc...). Message_types greater than 32767 are considered local experiments and should not be checked in to any widely distributed codebase.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">payload</td>
     <td class="mavlink_type" valign="top">uint8_t[249]</td>
     <td class="mavlink_comment">Variable length payload. The length is defined by the remaining message length when subtracting the header and other fields.  The entire content of this block is opaque unless you understand any the encoding message_type.  The particular encoding used can be extension specific and might not always be documented as part of the mavlink specification.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MEMORY_VECT" name="MEMORY_VECT">MEMORY_VECT (<a href="
      #MEMORY_VECT">
    #249
   </a>
   )
  </h2>
  <p class="description">Send raw controller memory. The use of this message is discouraged for normal packets, but a quite efficient way for testing new messages and getting experimental debug output.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">address</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Starting address of the debug variables</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ver</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Version code of the type variable. 0=unknown, type ignored and assumed int16_t. 1=as below</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Type code of the memory variables. for ver = 1: 0=16 x int16_t, 1=16 x uint16_t, 2=16 x Q15, 3=16 x 1Q14</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">value</td>
     <td class="mavlink_type" valign="top">int8_t[32]</td>
     <td class="mavlink_comment">Memory contents at specified address</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="DEBUG_VECT" name="DEBUG_VECT">DEBUG_VECT (<a href="
      #DEBUG_VECT">
    #250
   </a>
   )
  </h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">name</td>
     <td class="mavlink_type" valign="top">char[10]</td>
     <td class="mavlink_comment">Name</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">x</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">x</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">y</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">y</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">z</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">z</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="NAMED_VALUE_FLOAT" name="NAMED_VALUE_FLOAT">NAMED_VALUE_FLOAT (<a href="
      #NAMED_VALUE_FLOAT">
    #251
   </a>
   )
  </h2>
  <p class="description">Send a key-value pair as float. The use of this message is discouraged for normal packets, but a quite efficient way for testing new messages and getting experimental debug output.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">name</td>
     <td class="mavlink_type" valign="top">char[10]</td>
     <td class="mavlink_comment">Name of the debug variable</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">value</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Floating point value</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="NAMED_VALUE_INT" name="NAMED_VALUE_INT">NAMED_VALUE_INT (<a href="
      #NAMED_VALUE_INT">
    #252
   </a>
   )
  </h2>
  <p class="description">Send a key-value pair as integer. The use of this message is discouraged for normal packets, but a quite efficient way for testing new messages and getting experimental debug output.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">name</td>
     <td class="mavlink_type" valign="top">char[10]</td>
     <td class="mavlink_comment">Name of the debug variable</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">value</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Signed integer value</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="STATUSTEXT" name="STATUSTEXT">STATUSTEXT (<a href="
      #STATUSTEXT">
    #253
   </a>
   )
  </h2>
  <p class="description">Status text message. These messages are printed in yellow in the COMM console of QGroundControl. WARNING: They consume quite some bandwidth, so use only for important status and error messages. If implemented wisely, these messages are buffered on the MCU and sent only at a limited rate (e.g. 10 Hz).</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">severity</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Severity of status. Relies on the definitions within RFC-5424. See enum MAV_SEVERITY.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">text</td>
     <td class="mavlink_type" valign="top">char[50]</td>
     <td class="mavlink_comment">Status text message, without null termination character</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="DEBUG" name="DEBUG">DEBUG (<a href="
      #DEBUG">
    #254
   </a>
   )
  </h2>
  <p class="description">Send a debug value. The index is used to discriminate between values. These values show up in the plot of QGroundControl as DEBUG N.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ind</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">index of debug variable</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">value</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">DEBUG value</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SETUP_SIGNING" name="SETUP_SIGNING">SETUP_SIGNING (<a href="
      #SETUP_SIGNING">
    #256
   </a>
   )
  </h2>
  <p class="description">Setup a MAVLink2 signing key. If called with secret_key of all zero and zero initial_timestamp will disable signing</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">system id of the target</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">component ID of the target</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">secret_key</td>
     <td class="mavlink_type" valign="top">uint8_t[32]</td>
     <td class="mavlink_comment">signing key</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">initial_timestamp</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">initial timestamp</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="BUTTON_CHANGE" name="BUTTON_CHANGE">BUTTON_CHANGE (<a href="
      #BUTTON_CHANGE">
    #257
   </a>
   )
  </h2>
  <p class="description">Report button state change</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">last_change_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Time of last change of button state</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">state</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Bitmap state of buttons</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="PLAY_TUNE" name="PLAY_TUNE">PLAY_TUNE (<a href="
      #PLAY_TUNE">
    #258
   </a>
   )
  </h2>
  <p class="description">Control vehicle tone generation (buzzer)</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">tune</td>
     <td class="mavlink_type" valign="top">char[30]</td>
     <td class="mavlink_comment">tune in board specific format</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="CAMERA_INFORMATION" name="CAMERA_INFORMATION">CAMERA_INFORMATION (<a href="
      #CAMERA_INFORMATION">
    #259
   </a>
   )
  </h2>
  <p class="description">WIP: Information about a camera</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vendor_name</td>
     <td class="mavlink_type" valign="top">uint8_t[32]</td>
     <td class="mavlink_comment">Name of the camera vendor</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">model_name</td>
     <td class="mavlink_type" valign="top">uint8_t[32]</td>
     <td class="mavlink_comment">Name of the camera model</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">firmware_version</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Version of the camera firmware (v &lt;&lt; 24 &amp; 0xff = Dev, v &lt;&lt; 16 &amp; 0xff = Patch, v &lt;&lt; 8 &amp; 0xff = Minor, v &amp; 0xff = Major)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">focal_length</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Focal length in mm</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">sensor_size_h</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Image sensor size horizontal in mm</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">sensor_size_v</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Image sensor size vertical in mm</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">resolution_h</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Image resolution in pixels horizontal</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">resolution_v</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Image resolution in pixels vertical</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lens_id</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Reserved for a lens ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">flags</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">CAMERA_CAP_FLAGS enum flags (bitmap) describing camera capabilities.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">cam_definition_version</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Camera definition version (iteration)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">cam_definition_uri</td>
     <td class="mavlink_type" valign="top">char[140]</td>
     <td class="mavlink_comment">Camera definition URI (if any, otherwise only basic functions will be available).</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="CAMERA_SETTINGS" name="CAMERA_SETTINGS">CAMERA_SETTINGS (<a href="
      #CAMERA_SETTINGS">
    #260
   </a>
   )
  </h2>
  <p class="description">WIP: Settings of a camera, can be requested using MAV_CMD_REQUEST_CAMERA_SETTINGS.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mode_id</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Camera mode (CAMERA_MODE)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="STORAGE_INFORMATION" name="STORAGE_INFORMATION">STORAGE_INFORMATION (<a href="
      #STORAGE_INFORMATION">
    #261
   </a>
   )
  </h2>
  <p class="description">WIP: Information about a storage medium.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">storage_id</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Storage ID (1 for first, 2 for second, etc.)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">storage_count</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Number of storage devices</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">status</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Status of storage (0 not available, 1 unformatted, 2 formatted)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">total_capacity</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Total capacity in MiB</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">used_capacity</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Used capacity in MiB</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">available_capacity</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Available capacity in MiB</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">read_speed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Read speed in MiB/s</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">write_speed</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Write speed in MiB/s</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="CAMERA_CAPTURE_STATUS" name="CAMERA_CAPTURE_STATUS">CAMERA_CAPTURE_STATUS (<a href="
      #CAMERA_CAPTURE_STATUS">
    #262
   </a>
   )
  </h2>
  <p class="description">WIP: Information about the status of a capture</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">image_status</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Current status of image capturing (0: idle, 1: capture in progress, 2: interval set but idle, 3: interval set and capture in progress)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">video_status</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Current status of video capturing (0: idle, 1: capture in progress)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">image_interval</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Image capture interval in seconds</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">recording_time_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Time in milliseconds since recording started</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">available_capacity</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Available storage capacity in MiB</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="CAMERA_IMAGE_CAPTURED" name="CAMERA_IMAGE_CAPTURED">CAMERA_IMAGE_CAPTURED (<a href="
      #CAMERA_IMAGE_CAPTURED">
    #263
   </a>
   )
  </h2>
  <p class="description">Information about a captured image</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_utc</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since UNIX epoch) in UTC. 0 for unknown.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">camera_id</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Camera ID (1 for first, 2 for second, etc.)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lat</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Latitude, expressed as degrees * 1E7 where image was taken</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">lon</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Longitude, expressed as degrees * 1E7 where capture was taken</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">alt</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Altitude in meters, expressed as * 1E3 (AMSL, not WGS84) where image was taken</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">relative_alt</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Altitude above ground in meters, expressed as * 1E3 where image was taken</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">q</td>
     <td class="mavlink_type" valign="top">float[4]</td>
     <td class="mavlink_comment">Quaternion of camera orientation (w, x, y, z order, zero-rotation is 0, 0, 0, 0)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">image_index</td>
     <td class="mavlink_type" valign="top">int32_t</td>
     <td class="mavlink_comment">Zero based index of this image (image count since armed -1)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">capture_result</td>
     <td class="mavlink_type" valign="top">int8_t</td>
     <td class="mavlink_comment">Boolean indicating success (1) or failure (0) while capturing this image.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">file_url</td>
     <td class="mavlink_type" valign="top">char[205]</td>
     <td class="mavlink_comment">URL of image taken. Either local storage or http://foo.jpg if camera provides an HTTP interface.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="FLIGHT_INFORMATION" name="FLIGHT_INFORMATION">FLIGHT_INFORMATION (<a href="
      #FLIGHT_INFORMATION">
    #264
   </a>
   )
  </h2>
  <p class="description">WIP: Information about flight since last arming</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">arming_time_utc</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp at arming (microseconds since UNIX epoch) in UTC, 0 for unknown</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">takeoff_time_utc</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp at takeoff (microseconds since UNIX epoch) in UTC, 0 for unknown</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">flight_uuid</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Universally unique identifier (UUID) of flight, should correspond to name of logfiles</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MOUNT_ORIENTATION" name="MOUNT_ORIENTATION">MOUNT_ORIENTATION (<a href="
      #MOUNT_ORIENTATION">
    #265
   </a>
   )
  </h2>
  <p class="description">WIP: Orientation of a mount</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_boot_ms</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Timestamp (milliseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">roll</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Roll in degrees</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pitch</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Pitch in degrees</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">yaw</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Yaw in degrees</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="LOGGING_DATA" name="LOGGING_DATA">LOGGING_DATA (<a href="
      #LOGGING_DATA">
    #266
   </a>
   )
  </h2>
  <p class="description">A message containing logged data (see also MAV_CMD_LOGGING_START)</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">system ID of the target</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">component ID of the target</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">sequence</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">sequence number (can wrap)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">length</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">data length</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">first_message_offset</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">offset into data where first message starts. This can be used for recovery, when a previous message got lost (set to 255 if no start exists).</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">data</td>
     <td class="mavlink_type" valign="top">uint8_t[249]</td>
     <td class="mavlink_comment">logged data</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="LOGGING_DATA_ACKED" name="LOGGING_DATA_ACKED">LOGGING_DATA_ACKED (<a href="
      #LOGGING_DATA_ACKED">
    #267
   </a>
   )
  </h2>
  <p class="description">A message containing logged data which requires a LOGGING_ACK to be sent back</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">system ID of the target</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">component ID of the target</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">sequence</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">sequence number (can wrap)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">length</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">data length</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">first_message_offset</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">offset into data where first message starts. This can be used for recovery, when a previous message got lost (set to 255 if no start exists).</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">data</td>
     <td class="mavlink_type" valign="top">uint8_t[249]</td>
     <td class="mavlink_comment">logged data</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="LOGGING_ACK" name="LOGGING_ACK">LOGGING_ACK (<a href="
      #LOGGING_ACK">
    #268
   </a>
   )
  </h2>
  <p class="description">An ack for a LOGGING_DATA_ACKED message</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">system ID of the target</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">component ID of the target</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">sequence</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">sequence number (must match the one in LOGGING_DATA_ACKED)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="VIDEO_STREAM_INFORMATION" name="VIDEO_STREAM_INFORMATION">VIDEO_STREAM_INFORMATION (<a href="
      #VIDEO_STREAM_INFORMATION">
    #269
   </a>
   )
  </h2>
  <p class="description">WIP: Information about video stream</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">camera_id</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Camera ID (1 for first, 2 for second, etc.)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">status</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Current status of video streaming (0: not running, 1: in progress)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">framerate</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Frames per second</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">resolution_h</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Resolution horizontal in pixels</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">resolution_v</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Resolution vertical in pixels</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">bitrate</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Bit rate in bits per second</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rotation</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Video image rotation clockwise</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">uri</td>
     <td class="mavlink_type" valign="top">char[230]</td>
     <td class="mavlink_comment">Video stream URI</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SET_VIDEO_STREAM_SETTINGS" name="SET_VIDEO_STREAM_SETTINGS">SET_VIDEO_STREAM_SETTINGS (<a href="
      #SET_VIDEO_STREAM_SETTINGS">
    #270
   </a>
   )
  </h2>
  <p class="description">WIP: Message that sets video stream settings</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">system ID of the target</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">component ID of the target</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">camera_id</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Camera ID (1 for first, 2 for second, etc.)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">framerate</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">Frames per second (set to -1 for highest framerate possible)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">resolution_h</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Resolution horizontal in pixels (set to -1 for highest resolution possible)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">resolution_v</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Resolution vertical in pixels (set to -1 for highest resolution possible)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">bitrate</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Bit rate in bits per second (set to -1 for auto)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rotation</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Video image rotation clockwise (0-359 degrees)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">uri</td>
     <td class="mavlink_type" valign="top">char[230]</td>
     <td class="mavlink_comment">Video stream URI</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="WIFI_CONFIG_AP" name="WIFI_CONFIG_AP">WIFI_CONFIG_AP (<a href="
      #WIFI_CONFIG_AP">
    #299
   </a>
   )
  </h2>
  <p class="description">Configure AP SSID and Password.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">ssid</td>
     <td class="mavlink_type" valign="top">char[32]</td>
     <td class="mavlink_comment">Name of Wi-Fi network (SSID). Leave it blank to leave it unchanged.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">password</td>
     <td class="mavlink_type" valign="top">char[64]</td>
     <td class="mavlink_comment">Password. Leave it blank for an open AP.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="PROTOCOL_VERSION" name="PROTOCOL_VERSION">PROTOCOL_VERSION (<a href="
      #PROTOCOL_VERSION">
    #300
   </a>
   )
  </h2>
  <p class="description">WIP: Version and capability of protocol version. This message is the response to REQUEST_PROTOCOL_VERSION and is used as part of the handshaking to establish which MAVLink version should be used on the network. Every node should respond to REQUEST_PROTOCOL_VERSION to enable the handshaking. Library implementers should consider adding this into the default decoding state machine to allow the protocol core to respond directly.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">version</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Currently active MAVLink version number * 100: v1.0 is 100, v2.0 is 200, etc.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">min_version</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Minimum MAVLink version supported</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">max_version</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Maximum MAVLink version supported (set to the same value as version by default)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">spec_version_hash</td>
     <td class="mavlink_type" valign="top">uint8_t[8]</td>
     <td class="mavlink_comment">The first 8 bytes (not characters printed in hex!) of the git hash.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">library_version_hash</td>
     <td class="mavlink_type" valign="top">uint8_t[8]</td>
     <td class="mavlink_comment">The first 8 bytes (not characters printed in hex!) of the git hash.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="UAVCAN_NODE_STATUS" name="UAVCAN_NODE_STATUS">UAVCAN_NODE_STATUS (<a href="
      #UAVCAN_NODE_STATUS">
    #310
   </a>
   )
  </h2>
  <p class="description">General status information of an UAVCAN node. Please refer to the definition of the UAVCAN message "uavcan.protocol.NodeStatus" for the background information. The UAVCAN specification is available at http://uavcan.org.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since UNIX epoch or microseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">uptime_sec</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">The number of seconds since the start-up of the node.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">health</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Generalized node health status.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mode</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Generalized operating mode.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">sub_mode</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Not used currently.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">vendor_specific_status_code</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Vendor-specific status information.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="UAVCAN_NODE_INFO" name="UAVCAN_NODE_INFO">UAVCAN_NODE_INFO (<a href="
      #UAVCAN_NODE_INFO">
    #311
   </a>
   )
  </h2>
  <p class="description">General information describing a particular UAVCAN node. Please refer to the definition of the UAVCAN service "uavcan.protocol.GetNodeInfo" for the background information. This message should be emitted by the system whenever a new node appears online, or an existing node reboots. Additionally, it can be emitted upon request from the other end of the MAVLink channel (see MAV_CMD_UAVCAN_GET_NODE_INFO). It is also not prohibited to emit this message unconditionally at a low frequency. The UAVCAN specification is available at http://uavcan.org.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">time_usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds since UNIX epoch or microseconds since system boot)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">uptime_sec</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">The number of seconds since the start-up of the node.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">name</td>
     <td class="mavlink_type" valign="top">char[80]</td>
     <td class="mavlink_comment">Node name string. For example, "sapog.px4.io".</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">hw_version_major</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Hardware major version number.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">hw_version_minor</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Hardware minor version number.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">hw_unique_id</td>
     <td class="mavlink_type" valign="top">uint8_t[16]</td>
     <td class="mavlink_comment">Hardware unique 128-bit ID.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">sw_version_major</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Software major version number.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">sw_version_minor</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Software minor version number.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">sw_vcs_commit</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">Version control system (VCS) revision identifier (e.g. git short commit hash). Zero if unknown.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="PARAM_EXT_REQUEST_READ" name="PARAM_EXT_REQUEST_READ">PARAM_EXT_REQUEST_READ (<a href="
      #PARAM_EXT_REQUEST_READ">
    #320
   </a>
   )
  </h2>
  <p class="description">Request to read the value of a parameter with the either the param_id string id or param_index.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_id</td>
     <td class="mavlink_type" valign="top">char[16]</td>
     <td class="mavlink_comment">Parameter id, terminated by NULL if the length is less than 16 human-readable chars and WITHOUT null termination (NULL) byte if the length is exactly 16 chars - applications have to provide 16+1 bytes storage if the ID is stored as string</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_index</td>
     <td class="mavlink_type" valign="top">int16_t</td>
     <td class="mavlink_comment">Parameter index. Set to -1 to use the Parameter ID field as identifier (else param_id will be ignored)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="PARAM_EXT_REQUEST_LIST" name="PARAM_EXT_REQUEST_LIST">PARAM_EXT_REQUEST_LIST (<a href="
      #PARAM_EXT_REQUEST_LIST">
    #321
   </a>
   )
  </h2>
  <p class="description">Request all parameters of this component. After this request, all parameters are emitted.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="PARAM_EXT_VALUE" name="PARAM_EXT_VALUE">PARAM_EXT_VALUE (<a href="
      #PARAM_EXT_VALUE">
    #322
   </a>
   )
  </h2>
  <p class="description">Emit the value of a parameter. The inclusion of param_count and param_index in the message allows the recipient to keep track of received parameters and allows them to re-request missing parameters after a loss or timeout.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_id</td>
     <td class="mavlink_type" valign="top">char[16]</td>
     <td class="mavlink_comment">Parameter id, terminated by NULL if the length is less than 16 human-readable chars and WITHOUT null termination (NULL) byte if the length is exactly 16 chars - applications have to provide 16+1 bytes storage if the ID is stored as string</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_value</td>
     <td class="mavlink_type" valign="top">char[128]</td>
     <td class="mavlink_comment">Parameter value</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Parameter type: see the MAV_PARAM_EXT_TYPE enum for supported data types.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_count</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Total number of parameters</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_index</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Index of this parameter</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="PARAM_EXT_SET" name="PARAM_EXT_SET">PARAM_EXT_SET (<a href="
      #PARAM_EXT_SET">
    #323
   </a>
   )
  </h2>
  <p class="description">Set a parameter value. In order to deal with message loss (and retransmission of PARAM_EXT_SET), when setting a parameter value and the new value is the same as the current value, you will immediately get a PARAM_ACK_ACCEPTED response. If the current state is PARAM_ACK_IN_PROGRESS, you will accordingly receive a PARAM_ACK_IN_PROGRESS in response.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_id</td>
     <td class="mavlink_type" valign="top">char[16]</td>
     <td class="mavlink_comment">Parameter id, terminated by NULL if the length is less than 16 human-readable chars and WITHOUT null termination (NULL) byte if the length is exactly 16 chars - applications have to provide 16+1 bytes storage if the ID is stored as string</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_value</td>
     <td class="mavlink_type" valign="top">char[128]</td>
     <td class="mavlink_comment">Parameter value</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Parameter type: see the MAV_PARAM_EXT_TYPE enum for supported data types.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="PARAM_EXT_ACK" name="PARAM_EXT_ACK">PARAM_EXT_ACK (<a href="
      #PARAM_EXT_ACK">
    #324
   </a>
   )
  </h2>
  <p class="description">Response from a PARAM_EXT_SET message.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_id</td>
     <td class="mavlink_type" valign="top">char[16]</td>
     <td class="mavlink_comment">Parameter id, terminated by NULL if the length is less than 16 human-readable chars and WITHOUT null termination (NULL) byte if the length is exactly 16 chars - applications have to provide 16+1 bytes storage if the ID is stored as string</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_value</td>
     <td class="mavlink_type" valign="top">char[128]</td>
     <td class="mavlink_comment">Parameter value (new value if PARAM_ACK_ACCEPTED, current value otherwise)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Parameter type: see the MAV_PARAM_EXT_TYPE enum for supported data types.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">param_result</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Result code: see the PARAM_ACK enum for possible codes.</td>
    </tr>
   </tbody>
  </table>
 </body>
</html>