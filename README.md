# Dinosaur warrior

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat&logo=espressif&logoColor=white) ![BLE](https://img.shields.io/badge/BLE-0082FC?style=flat&logo=bluetooth&logoColor=white) ![WiFi](https://img.shields.io/badge/WiFi-0D6EFD?style=flat) ![3D Printed](https://img.shields.io/badge/3D%20Printed-FF6B00?style=flat) ![BluuPrint](https://img.shields.io/badge/Built%20with-BluuPrint-5B50F0?style=flat)

![Dinosaur warrior Concept Render](media/concept-render-1.png)

## Quick Index

- [CAD Files](#cad-files)

## Features

- Servo state machine
- I2S Audio playback
- LED animation sequencing
- GPIO Interrupt (Button Trigger)

## Concept Renders

![Render 1](media/concept-render-1.png)
![Render 2](media/concept-render-2.png)
![Render 3](media/concept-render-3.png)

## CAD Files

| Part | Qty | Material | Infill | Supports |
|------|-----|----------|--------|----------|
| Lower Chassis | 1 | PETG | — | — |
| Upper Torso | 1 | PETG | — | — |
| Mecha Head | 1 | PETG | — | — |
| Dorsal Scale Button | 1 | PETG | — | — |
| Left Cannon Barrel | 1 | PETG | — | — |
| Right Cannon Barrel | 1 | PETG | — | — |

> STL files are in the `cad/stl/` folder (compiled from OpenSCAD by BluuPrint).

## Folder Structure

```
├── README.md               # This file
├── BOM.csv                 # Bill of materials with purchase links
├── LICENSE                 # MIT License
├── config/                 # Full project configuration (JSON)
├── product-spec.md         # Detailed product specification
├── cad/                    # CAD specs, OpenSCAD code, compiled STLs
└── media/                  # Concept renders and images
```

---

_Built with [BluuPrint](https://github.com/BluuPrint) — AI-Orchestrated Hardware Design Platform_