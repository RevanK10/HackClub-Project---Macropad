# Apollopad
---
A 5-key macropad with a rotary encoder, OLED screen, and 2 SK6812 MINI-E LEDs. It runs on KMK firmware.

## Features
---
- Two Piece 3D Printable Case
- 128x32 OLED Display
- EC11 Rotary encoder
- 2 SK6812 MINI-E LEDs
- 5 Keys

## CAD Model
---
The case uses 4 M3 bolts and heatset inserts, one for each corner of the case.
<img width="920" height="541" alt="image" src="https://github.com/user-attachments/assets/c5f85f58-880e-4dda-a72a-e9181f2f4349" />

## PCB
---
Schematic:
<img width="1220" height="492" alt="image" src="https://github.com/user-attachments/assets/c88b1e29-b42c-4667-8474-10c7b485d076" />


PCB:
<img width="870" height="674" alt="image" src="https://github.com/user-attachments/assets/390980d6-a8a5-437e-b67a-6a298604e6b7" />


## Firmware
---
Currently, Astrapad runs on KMK, which allows for rapid development and easy iteration using CircuitPython.
- Rotating the encoder adjusts the system volume up or down, and pressing the encoder toggles mute.
- The top-left button is copy, the bottom-left button is cut, and the bottom-middle button is paste.
- The bottom-right button is play/pause
- The top middle button is a screenshot.
- The OLED display shows the current system volume level of the connected device.

## BOM
---
- 1x Seeed XIAO RP2040
- 1x 0.91-inch OLED displays 
- 1x EC11 rotary encoders
- 1x Case (2 3D printed parts)
- 1x EC11 Rotary Encoder
- 4x M3x5x4 Heatset inserts
- 4x M3x16mm screws
- 5x Cherry MX Switches
- 5x DSA keycaps
- 5x Through-hole 1N4148 Diodes
- 2x SK6812 MINI-E LEDs

## Extra Stuff
---
Idk what to put here, but thank you, BluePrint Hackclub, for the opportunity.
