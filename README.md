@"
# 3-Phase Rectifier PCB Design V1.0

## 📌 Project Overview
This project is a **PCB design for a 3-Phase Bridge Rectifier** using six diodes and a filter capacitor to convert AC to DC. The design is implemented in **Altium Designer** and fully **DRC-compliant**.

It demonstrates:
- Schematic to PCB workflow
- Manual routing techniques
- Compact, industry-style PCB layout
- 3D rendering for real-world visualization

## 🎯 Features
- Converts **3-phase AC input** to **DC output**
- Uses **6 × 1N4007 diodes** in a bridge configuration
- Includes a **470µF capacitor** for DC filtering
- Screw terminals for **AC input** and **DC output**
- Optimized layout with clear labeling

## 🗂️ Files Included
| File Name | Description |
|-----------|-------------|
| `3_phase_rectifier.pdf` | Schematic and PCB documentation |
| `top_view_1D.jpg` | PCB layout view |
| `top_view_2D.jpg` | 2D routed view |
| `top_view_3D.jpg` | 3D rendered PCB view |

## 🔧 How It Works
- The **3-phase AC input** enters through a screw terminal.
- Six diodes form a **full-wave bridge rectifier**.
- A filter capacitor smoothens the DC output.
- Output is available via a DC screw terminal.

## 🧑‍💻 Designed By
**Mohit Jagtap**
"@ | Out-File -FilePath README.md -Encoding utf8
