# VOLTIX V1 DC-DC Boost Converter

a DC-DC Boost Converter circuit designed in KiCad which it takes an input voltage of 5V DC and provides a nominally regulated 9V output.

##
<img width="751" height="522" alt="image" src="https://github.com/user-attachments/assets/ef0757db-f984-4a9b-ae63-006064efa6ae" />

## shematics
<img width="858" height="547" alt="image" src="https://github.com/user-attachments/assets/69767f51-3915-40e8-a626-7ca1cef3f49d" />

## PCB 
<img width="795" height="549" alt="image" src="https://github.com/user-attachments/assets/44c46df7-e41b-40b8-a4f3-240369dac5c2" />

## Design

| Parameter | Target |
|---|---:|
| Input voltage | 5 V DC |
| Output voltage | 9 V DC |
| Maximum output current | 100 mA |
| Converter IC | MC34063AD |
| PCB | 2-layer |
| Board outline | 41 mm × 29 mm |


## Components

MC34063AD switch mode regulator

120uH Inductor

1N5819 Schottky Diode

Feedback Resistors and Current Sensing Resistor

Input, Output and Timing Capacitors

2-Pin Input and Output Connectors

the list of components can be found in the BOM.csv 

## Project Files

`PCB/VOLTIX.kicad_sch`

KiCad Schematic

`PCB/VOLTIX.kicad_pcb`

KiCad PCB

`PCB/VOLTIX.kicad_pro`

KiCad Project file.

`Production/Gerbers.zip`

Gerbers and Drills/Fabrication.

`journal.md`

Project notes.

`BOM.csv`

Bill of Materials

## Opening Project

Download or Clone the project.

Open `PCB/VOLTIX.kicad_pro`.

From the project manager open either the Schematic or PCB.

Before using the fabrication files check that everything is correct on the schematic and PCB. Run ERC and DRC checks using your installed KiCad version.

## Manufacturing

The Gerbers have been provided in the Production folder
