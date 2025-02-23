# CMOS Half Adder Project

## Overview

This project involves designing, simulating, and analyzing a **CMOS Half Adder** using **Cadence Virtuoso**. The Half Adder is a fundamental combinational circuit used for binary addition, generating a **sum (S)** and a **carry (C)** output.

## Software & Tools Used

- **Cadence Virtuoso** (for schematic capture, layout, and simulation)
- **Assura** (for DRC and LVS verification)
- **Analog Design Environment (ADE)** (for waveform analysis)

## Project Workflow

### Schematic Design

- Designed using **Virtuoso Schematic Editor**.
- Constructed using N**AND, NOR, and NOT gates** from a custom-built library.
- Verified through **Transient analysis**.

### Layout Design

- Created using **Virtuoso Layout Editor**.
- Optimized for **area efficiency** and minimal parasitics.
- Design Rule Check (**DRC**) performed for layout validation.

## Technical Specifications

- **Technology Node**: 90nm (as per design constraints)
- **Supply Voltage (VDD)**: 1V
- **Logic Operation**: Half Adder (S = A ⊕ B, C = A \* B)

## Results & Observations

- **Schematic Simulation**: Verified correct Half-Adder functionality.
- **Layout Optimization**: Ensured minimal area and **DRC compliance**.
- **Post-Layout Simulation**: Observed deviations due to parasitic capacitance and resistance.

## Reference Images

- **Half\_Adder\_Schematic**

  ![Half_Adder_Schematic](https://github.com/user-attachments/assets/65d58650-87bd-41eb-86d2-65dd2f23ebd1)

- **Half\_Adder\_Test**

  ![Half_Adder_Test](https://github.com/user-attachments/assets/10a4e02e-d2fb-4a47-a12f-fe0e6f6c59b9)

- **Half\_Adder\_ADE**

  ![Half_Adder_ADE](https://github.com/user-attachments/assets/73f0a7eb-d2d0-4241-9f57-39cd09529bda)


## Caution

- This project is designed using **custom NAND, NOR, and NOT gates** from a self-built library.
- **Copying this file alone will not work**—users need to **add the NAND, NOR, and NOT gates** to their own library first to use it correctly.

---

*This project belongs to me and is intended for educational and research purposes only. It should not be used directly for other purposes without permission.*

