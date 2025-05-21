# Digital Logic Simulator
## By Ryan & Samuel

[![Language](https://img.shields.io/badge/Language-C-4B8BBE?style=for-the-badge&logo=c&logoColor=white)](https://en.wikipedia.org/wiki/C_(programming_language))
[![Platform](https://img.shields.io/badge/Platform-DE1--SoC%20FPGA-FD7E14?style=for-the-badge)](https://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&CategoryNo=139&No=836)
[![Display](https://img.shields.io/badge/Output-VGA-DA1884?style=for-the-badge)]()
[![Input](https://img.shields.io/badge/Input-PS%2F2%20Keyboard-228B22?style=for-the-badge)]()

**Visualizing Circuit Behavior on RISC-V FPGA**

Full-featured, VGA-rendered implementation of a logic circuit simulator, created on an FPGA platform (DE1-SoC) using C. This project supports real-time hardware interaction through PS/2 keyboard input and full circuit simulation built entirely from NAND gate logics. Users can draw gates and wires, toggle inputs, and save or reuse custom components — all from the keyboard, with visual feedback rendered directly on-screen.

## 🎮 Features

- **VGA-Rendered Logic UI**  
  Visually interactive grid-based circuit layout rendered in 640x480 VGA.

- **Keyboard-Only Interaction**  
  Use WASD to move, ENTER to draw, and number/letter keys to switch modes and toggle inputs.

- **NAND-Only Foundation**  
  All logic is based on NAND gates; users can build AND, OR, XOR, etc. from NAND.

- **Custom Gate Saving & Reuse**  
  Save circuits into reusable custom components (via keys G–L) and place them later (keys 6–0).

- **Up to 3 Inputs/Outputs Per Gate**  
  Simplified gate design to support manageable simulation and truth table resolution.

- **Real-Time Signal Propagation**  
  Wires update dynamically as inputs are toggled, with color-coded rendering of logic states.

---

## 🎹 Controls

| Key        | Function                                |
|------------|-----------------------------------------|
| `W/A/S/D`  | Move cursor                             |
| `ENTER`    | Draw/place (press twice for wires)      |
| `1`        | Switch to wire drawing mode             |
| `2`        | Switch to NAND gate placement           |
| `Z/X/C`    | Toggle Input Signals 1/2/3              |
| `G/H/J/K/L`| Save custom gate to memory              |
| `6/7/8/9/0`| Switch to custom gate placement         |

---

## 🛠 Technical Overview

- **Platform**: DE1-SoC FPGA running a NIOS V softcore processor
- **Language**: C (bare-metal, no OS)
- **Display**: VGA (memory-mapped framebuffer)
- **Input**: PS/2 Keyboard

---

## 📽 Demo Video

[Watch on Google Drive](https://drive.google.com/file/d/1QGutFc5El03w8KqDNv_r5puh34M03dql/view?usp=drive_link)
[Live Demo](https://drive.google.com/file/d/1FOw0IOvm2CIUKd45J4uPqPxgiUIi615q/view?usp=drive_link)




