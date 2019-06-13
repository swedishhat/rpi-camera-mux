# rpi-camera-mux
2:1 camera multiplexer for Raspberry Pi MIPI CSI-2 interface

Creating a 2:1 MIPI mux board, that allows for a 2 Camera Extention to an RPi
Each Camera will not be able to be used in parallel. Using a mux chip (TS5MP646) the RPi will be able to
select between either of the cameras

datasheet for TS5MP646:
http://www.ti.com/lit/ds/symlink/ts5mp646.pdf?HQS=TI-null-null-mousermode-df-pf-null-wwe&DCM=yes&ref_url=https%3A%2F%2Fwww.mouser.com%2F

Software:
Some type of C++ or Python script that allows for someone to select either camera from within the RPi system

Hardware:
PCB that consist of 3 Camera Connector ports, 2 for external Camera devices, and 1 to connect to RPi Mipi camera interface
possible external LDO for powering mux chip
