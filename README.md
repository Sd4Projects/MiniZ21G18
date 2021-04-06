# MiniZ21G18 draft info.

This design will be used to replace the Version 1 series boards that were listed in Sd4Projects before. The MiniMega boards (version 1) will not work with this series board.

This board is released under CERN Open Hardware License, CERN OHL v.1.2.
Please see the CERN OHL v.1.2 for applicable conditions. (http://ohwr.org/cernohl).

Design files were done with KiCad Version 5.1.8

Zip file with design files: MiniZ21G18_v4b.zip

Schematic file: MiniZ21G18_v4b.sch.pdf

BOM file: MiniZ21G18_v4b.BOM.pdf

Finished Board Top View

![alt text](https://github.com/Sd4Projects/MiniZ21G18/blob/main/MiniZ21G18_top_v4b.jpg?raw=true "finishedboard")

Overview: The board was designed to use Arduino ZERO boot firmware. There are some differences with the MiniX21G18 board. Host usb mode is not supported, there is no 5 volt power on the board. The board uses a buck power supply for much greater range of power input (5 to 16 volts) and better efficiency.

To install the boot firmware I used an Atmel-ICE programmer and the standard Ardiuno IDE.

![alt text](https://github.com/Sd4Projects/MiniZ21G18/blob/main/Arduino_boot_config1.png?raw=true "ArduinoProgrammer")

![alt text](https://github.com/Sd4Projects/MiniZ21G18/blob/main/Arduino_boot_config2.jpg?raw=true "Atem-ICE")

The usb cable that plugs into the cpu is for power only. The usb cable that plugs into the Atmel-ICE does the programming.

Bare board can be ordered from OSH Park. https://oshpark.com/shared_projects/rFaZbuVc with project name MiniZ21G18_v4b.kicad_pcb or use source files and order from whoever you want.
  
See project files for more info till full upload done.
