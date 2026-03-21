# MeshSlide - Modular Meshtastic Case for Heltec V4

This print kit is designed for Heltec V4

![](assets/20260128224045.jpg)

## Features

MeshSlide is a modular Meshtastic case, specifically designed for Heltec V4. It features a slide-in pogopin rail system that supports hot-swappable expansion modules.

Currently, four expansion modules have been designed for MeshSlide:

- SlideZero - Rail contact protection module with lanyard hole, no additional functionality
- SlideRotary - Rotary knob module based on EC11
- SlideTriple - Button module based on Kailh/Gateron low-profile switches
- SlideKB - Full keyboard input module based on CardKB

![](assets/20260128224035.jpg)

![](assets/20260128224125.jpg)

### SlideZero

Placeholder protection module

- Primarily used to cover and protect the rail and pogopin contacts
- Includes a lanyard hole, with adjustable position by changing the slide-in direction

![](assets/1769684606677.jpg)

### SlideRotary

Rotary knob module based on EC11 rotary encoder

- Clockwise/counterclockwise rotation for scrolling + press to confirm
- Used for menu navigation and preset message selection

![](assets/1769684247219.jpg)

### SlideTriple

Button module based on Kailh/Gateron low-profile switches

- From top to bottom: Up, Down, Confirm
- Used for menu navigation and preset message selection

![](assets/1769684340032.jpg)

### SlideKB

Full keyboard input module based on CardKB

- Enables complete text input using the keyboard
- Features an adjustable stand for switching between handheld and desktop modes
- Internal space of 76mm x 46mm x 5mm reserved for installation and wiring, suitable for additional sensors

![](assets/1769683724492.jpg)

## MeshSlide

### BOM List

This list includes MeshSlide and SlideZero

1. 3D printed case S1
2. 3D printed case R1
3. 3D printed case M1
4. 3D printed case U1
5. 3D printed case L1
6. 3D printed case S2
7. Rubber duck antenna
8. 3D printed case ZS (2 pieces)
9. 3D printed case ZM
10. 3D printed case B1 (2 pieces)
11. Heltec V4 with L76K GNSS module
12. pogopin magnetic connector 8P female socket
13. Battery (dimensions 4.6mm x 22mm x 76mm)
14. IPEX to SMA female connector cable, 5cm length (1 piece)
15. Fasteners
    1. M2x7 hex socket head bolts (10 pieces)
    2. M2x5 hex socket head bolts (1 piece)
    3. M2x4 hex socket flat head bolts (1 piece)
    4. M2x5 double-pass copper pillar knurled nuts, outer diameter 3mm (3 pieces)

![](assets/IMG_20260126203819.png)

The specific dimensions of the pogopin 8P magnetic connector are shown in the figure below

![](assets/8Pin.png)

### Assembly Instructions

#### MeshSlide

Solder the pogopin pins to Heltec V4. The pinout is as shown in the figure, from left to right: GND, 18(SCL), 17(SDA), 1, 2, 3, 4, 3V3. All expansion modules are based on this definition

![](assets/IMG_20260126210414.png)

Embed the M2x5 knurled nuts into the printed cases M1 and S1

![](assets/IMG_20260126210816.jpg)

Install the SMA connector cable to the printed case S1, connect the SMA cable to Heltec V4, and install the Heltec V4 with L76K GNSS module to the printed case M1

![](assets/20260321104856.jpg)

Connect the battery to Heltec V4, bending the cable as much as possible without causing damage

![](assets/20260321104902.jpg)

Install the printed case L1, install the printed case B1. The printed case L1 can accommodate a battery with maximum dimensions of 5mm x 24mm x 82mm

![](assets/20260321104908.jpg)

Embed the pogopin into the printed case S2, install the printed case S2 to the printed case M1

![](assets/20260321104914.jpg)

Install the printed case U1

![](assets/20260126213426.jpg)

Install the printed case R1

![](assets/20260126213527.jpg)

Install 6 M2x7 hex socket head bolts

![](assets/20260126213801.jpg)

![](assets/20260126213813.jpg)

Install 1 M2x5 hex socket head bolt

![](assets/20260126214403.jpg)

Install 1 M2x4 hex socket flat head bolt

![](assets/20260126214411.jpg)

Install the rubber duck antenna

![](assets/20260126214832.jpg)

Assembly complete

#### SlideZero

Assemble the printed cases ZS and ZM using 4 M2x7 hex socket head bolts

![](assets/20260126215609.jpg)

![](assets/20260126215617.jpg)

Assembly complete

Slide SlideZero into MeshSlide

![](assets/20260126215738.jpg)

![](assets/20260126215748.jpg)

## SlideRotary

### BOM List

1. 3D printed case S1
2. 3D printed case S2
3. 3D printed case M1
4. 3D printed case C1
5. 3D printed case U1
6. pogopin magnetic connector 8P male plug
7. EC11 rotary encoder 15mm
8. M2x7 hex socket head bolts (4 pieces)

![](assets/IMG_20260127205012.png)

### Assembly Instructions

Solder the pogopin pins to the EC11. The pinout is as shown in the figure. Before soldering, be sure to test the magnetic polarity of the pogopin by attaching it to MeshSlide

![](assets/IMG_20260127210405.png)

![](assets/20260127210650.jpg)

Embed the pogopin into the 3D printed case C1. If the pogopin is loose when embedding, you can use glue to secure it

![](assets/20260127211733.jpg)

Install the EC11 to the 3D printed case M1

![](assets/20260127211755.jpg)

Install the 3D printed case C1 to the 3D printed case M1

![](assets/20260127211954.jpg)

Use 4 M2x7 hex socket head bolts to fix the 3D printed cases S1 and S2 to the 3D printed case M1

![](assets/20260127212155.jpg)

Tighten the EC11 nut

![](assets/20260127212309.jpg)

Install the 3D printed case U1 to the EC11

![](assets/20260127212343.jpg)

Assembly complete

Slide SlideRotary into MeshSlide

![](assets/20260127212434.jpg)

![](assets/20260127212443.jpg)

## SlideTriple

### BOM List

1. 3D printed case S1 (2 pieces)
2. 3D printed case M1
3. 3D printed case C1
4. M2x7 hex socket head bolts (4 pieces)
5. M2x5 hex socket head bolts (1 piece)
6. pogopin magnetic connector 8P male plug
7. Kailh/Gateron low-profile switches (3 pieces)
8. Keycaps (3 pieces)

![](assets/IMG_20260127195444.png)

### Assembly Instructions

Solder the pogopin pins to the 3 low-profile switches. The pinout is as shown in the figure, from left to right: GND, empty, empty, 1, 2, 3, empty, empty. Before soldering, be sure to test the magnetic polarity of the pogopin by attaching it to MeshSlide

![](assets/IMG_20260127201104.png)

![](assets/20260127201509.jpg)

Install the 3 low-profile switches to the 3D printed case M1

![](assets/20260127202306.jpg)

Embed the pogopin into the 3D printed case C1. If the pogopin is loose when embedding, you can use glue to secure it

![](assets/20260127202514.jpg)

Install the 3D printed case C1 to the 3D printed case M1

![](assets/20260127203413.jpg)

Use 4 M2x7 hex socket head bolts to fix the 2 3D printed cases S1 to the 3D printed case M1

![](assets/20260127203521.jpg)

Use 1 M2x5 hex socket head bolt to fix the 3D printed case M1

![](assets/20260127203827.jpg)

Assembly complete

Slide SlideTriple into MeshSlide

![](assets/20260127203934.jpg)

![](assets/20260127203959.jpg)

## SlideKB

### BOM List

1. 3D printed case S1
2. 3D printed case C1
3. 3D printed case K1
4. 3D printed case K2
5. 3D printed case L1
6. 3D printed case U1
7. 3D printed case D1
8. M5Stack CardKB
9. GROVE connection cable HY2.0-4Pin
10. pogopin magnetic connector 8P male plug
11. M2x7 hex socket head bolts (6 pieces)
12. M2x4 hex socket flat head bolts (2 pieces)

![](assets/Pasted%20image%2020260127215115.png)

### Assembly Instructions

Solder the pogopin pins to the GROVE cable. The pinout is as shown in the figure, from left to right: GND, SCL, SDA, empty, empty, empty, empty, 3V3. Before soldering, be sure to test the magnetic polarity of the pogopin by attaching it to MeshSlide

Note: The color coding of the GROVE cable shown in the figure may not match the official Grove cable included with M5Stack CardKB. Please confirm carefully before soldering

![](assets/20260127220009.jpg)

![](assets/20260127220122.jpg)

Embed the pogopin into the 3D printed case C1. If the pogopin is loose when embedding, you can use glue to secure it; connect the GROVE cable to M5Stack CardKB, and install the CardKB to the 3D printed case L1

![](assets/20260127220457.jpg)

The bottom of the 3D printed case L1 reserves approximately 76mm x 46mm x 5mm of space and wiring room, which can accommodate other sensors of suitable size

![](assets/20260127221006.jpg)

Install the 3D printed cases K1 and K2

![](assets/20260127221624.jpg)

Use 2 M2x7 hex socket head bolts to install the 3D printed case U1

![](assets/20260127221631.jpg)

Use 4 M2x7 hex socket head bolts to install the 3D printed case S1

![](assets/20260127221636.jpg)

![](assets/20260127221642.jpg)

Use 2 M2x4 hex socket flat head bolts to install the 3D printed case D1

![](assets/20260127222633.jpg)

![](assets/20260127222648.jpg)

Assembly complete

Slide SlideKB into MeshSlide

![](assets/20260127222955.jpg)

![](assets/20260127223002.jpg)

Deploy the stand

![](assets/20260127222835.jpg)

## Software Configuration

![](assets/20260126222704.jpg)
