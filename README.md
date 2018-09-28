# Dataman-S4-1640
A 40-pin adapter for the Dataman S4 EPROM Programmer 

Allows you to program 16-bits 40 pin EPROMs with your S4 programmer. You'll need a copy of Eagle PCB to open these files.

Parts needed: 
- 18x 1k 0805 resistors
- 5x 100nF 1206
- 5x 74xx573 SMD (SO-20)

Errata:
- There needs to a 1k resistor in series with both the UPPER and LOWER data line. Please refer to the schematic and find a spot on the PCB to put it, maybe cut a trace. Or just fix it on the board :)
