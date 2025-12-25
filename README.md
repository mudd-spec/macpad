# macpad

The macpad is a 9 key macropad/keyboard with 2 EC11 style rotary encoders.

## Features:
- Sandwich style mount - 3D printable, BUT you need screws and heatset inserts
- EC11 Rotary encoders for rotational action AND they serve as switches/keys
- 9 fully programmable keys in a matrix

## CAD Model:
4 heatset inserts and 4 M3 screws are used to keep everything together

The model consists of a bottom case, a plate, and a bracket for the top, so the key switches themselves are less exposed.

There are also optional rotary encoder dials.

<img src=assets/cad.png alt="cad" width="500"/>


## PCB / Schematic
The PCB as well as the schematic is pictured below:

Schematic

<img src=assets/schematic.png alt="schematic" width="300"/>

PCB

<img src=assets/pcb.png alt="pcb" width="300"/>


## Firmware Overview
This hackpad uses [QMK](https://qmk.fm/) firmware for everything. 

- caution: the current keybinds are not advised for actual use

<img src=assets/layout.png alt="keyboard layout" width="300"/>


## BOM:
Here is everything needed to make the macpad

- 9x Cherry MX Switches
- 9x DSA Keycaps
- 4x M3x5x4 Heatset inserts
- 4X M3x12mm SHCS Bolts
- 11x 1N4148 DO-35 Diodes.
- 2x EC11 Rotary Encoder
- 1x XIAO RP2040
- 1x Case (3 3D printed parts)
- 2x Rotary Encoder Dials (2 3D printed parts)
- 1x PCB
