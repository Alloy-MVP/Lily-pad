# Lily-pad

## 3D Cad Model
<img width="1101" height="803" alt="image" src="https://github.com/user-attachments/assets/acadd8aa-4754-4fd0-8920-7827d0858fa5" />
This was made in Fusion 360 which luckily I have a lot of experience in so the case didn't take as long as the PCB.


## PCB Schematic
<img width="1489" height="887" alt="Screenshot 2026-09-06 211511" src="https://github.com/user-attachments/assets/cd140fd4-efe0-44ab-b2c9-1ca6a6cc763b" />
The first iteration used normal manual wiring but after adding the encoder and screen I ran out of pins so I had to resort to learning about matrixes and therefore added a 3x3 matrix to save 1 pin.


## PCB
<img width="1272" height="828" alt="Screenshot 2026-09-06 211425" src="https://github.com/user-attachments/assets/d9809e5e-f5c8-466d-bb56-65311d91c95d" />
This is the second PCB I made after trying a test one with just 4 buttons and a microcontroller to get used to KiCAD which is why the routing isn't perfect.


## How the case fits together
<img width="1000" height="715" alt="image" src="https://github.com/user-attachments/assets/298b9907-bbb2-4e50-9d12-188e1983563e" />
The top plate is screwed together with the base to hold the PCB inside and a gap for the USB on one side.


## Finished Product
<img width="4000" height="3000" alt="V2 Case" src="https://github.com/user-attachments/assets/d32c952e-eb11-443b-a101-f6a80d9cef39" />


## Firmware
The folder for the firmware is titled "lily-pad" and uses QMK. Currently the switches are mapped to: 4:a,5:b,6:c,7:d,1:e,2:f,3:g going from left to right (top to bottom if there is more than one key in a column) and the rotary encoder is set to increase decrease volume depending on the rotation.

## BOM (Bill of Materials)

### Materials Needed:
* 7x Cherry MX Switches
* 7x White DSA Keycaps
* 7x 1N4148 Diodes
* 1x EC11E Rotary Encoder
* 1x 0.91 Inch OLED Display
* 1x Seeed XIAO RP2040
* 4x M3x16mm Screws
* 1x ~5mm thick piece of foam

### Materials already owned
* 700g White PLA Filament (possible with much less but my printer is very bad so it took 8 attempts before it printed an *acceptible* case)
* Soldering Iron
