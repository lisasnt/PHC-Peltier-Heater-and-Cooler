# PHC-Peltier-Heater-and-Cooler
Date: 23 May 2023


Schematic-only design of an STM32L010 board wich aims to control a Peltier Cell. 
Using an H-bridge circuit driving it is possible to reverse polarity of the cell to heat or cool the surface.

This board wants to have an educational purpose so different basics circuits/peripherals are included:
- USB port with ESD protection
- 3v3 switching node
- USB to UART interface
- SWD interface
- RBG LED, Potentiometer, LCD display
- Fans driver
- Temperature sensor
- H-bridge driver

