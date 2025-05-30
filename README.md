J1939-22 Custom Device
===================

### NOTE ###

This custom device is being adapted from the original J1939-21 implementation by Dan Eaton to work for the newly released J1939-22 specification using CAN-FD and MultiPG support.

### Description ###

This addon implements the J1939-22 specification for support of high bandwidth messages utilizing the increased data rates of CAN-FD.  The user can import J1939 messages from a .DBC file and then read or write those messages. In addition, this addon supports requesting and clearing active and previously active diagnostic trouble code. It supports address claiming for the addon's configured address. A custom workspace object and tool are provided for viewing network topology and DTCs among other things.

### Help ###

Help is included in most System Explorer sections.

### Built Availability ###

https://github.com/ni/J1939-22-Custom-Device/releases

### Built Dependencies ###

### Source Version ###

LabVIEW 2023 Q3 64-bit

### Source Dependencies ###

NI XNET 23.0

NI Veristand Custom Device Development Tools (https://github.com/ni/niveristand-custom-device-development-tools/releases)

NI Simple Messaging Library 3.1.0.9 (https://www.vipm.io/package/ni_lib_stm/)

NI Asynchronous Messaging Communication Library 3.3.1.22 (https://www.vipm.io/package/ni_lib_amc/)

SubModules:

Frame Protection Support (https://github.com/NIVeriStandAdd-Ons/Frame-Protection-Support)
