# PHC - Peltier Heater and Cooler
Date: 23 May 2023

Schematic-only design with Kicad v6 of an [STM32L010](https://www.farnell.com/datasheets/2710889.pdf) board wich controls a [Peltier Cell](https://en.wikipedia.org/wiki/Thermoelectric_cooling) (TEC1-12706). 

This board wants to have an educational purpose so different basics circuits/peripherals are included:
- USB port with ESD protection
- 3V3 switching node
- USB-to-UART interface
- SWD interface
- RBG LED, potentiometer, LCD display
- Fans driver
- Temperature sensor
- H-bridge driver

