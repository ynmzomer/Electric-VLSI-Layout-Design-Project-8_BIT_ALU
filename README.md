
---

# 🧮 8-Bit ALU – Physical VLSI Design Project

![Status](https://img.shields.io/badge/Status-Completed-success)
![Technology](https://img.shields.io/badge/Technology-CMOS-blue)
![Design](https://img.shields.io/badge/Design-Full%20Custom-orange)
![License](https://img.shields.io/badge/License-Academic-lightgrey)

---

## 📌 Project Overview

This repository presents the design and implementation of an **8-bit Arithmetic Logic Unit (ALU)** using **static CMOS technology**.
The project focuses on **full-custom VLSI design**, starting from transistor-level schematics and extending to physical layout implementation.

All functional blocks were designed modularly and then integrated to form a complete ALU system.

---

## ⚙️ Supported Operations

### ➕ Arithmetic Operations

* Addition
* Subtraction
* Multiplication *(partially implemented)*

### 🔢 Logical Operations

* AND
* OR
* XOR
* NAND
* NOR
* NOT

### 🔁 Shift Operations

* Logical Left Shift
* Logical Right Shift
* Arithmetic Left Shift
* Arithmetic Right Shift

### 🔍 Comparison Operations

* Equal
* Greater Than
* Less Than

---

## 🧠 Design Methodology

* Static CMOS logic throughout the design
* Transmission-gate–based multiplexers
* Modular 1-bit building blocks combined into 8-bit architecture
* Custom layout for each functional block
* Two-metal-layer layout constraint
* Schematic vs Layout (NCC) verification
* Buffer insertion for improved signal integrity

---

## 🧩 Implemented Modules

* 8-bit Full Adder
* 8-bit Subtractor (A + B′ + 1)
* Logic Gates (AND, OR, XOR, NAND, NOR)
* Comparator (Equal / Greater / Less)
* Shift Units
* Transmission-Gate Multiplexers

---


## ⚠️ Layout Status & NCC Information

The schematic design of the ALU was fully completed and verified.
However, the **final physical layout contains NCC (Netlist Consistency Check) errors**.

These issues mainly arise from:

* Routing complexity
* Dense interconnections
* Limited time for full layout debugging

Despite this, the **functional correctness of the schematic design is verified**, and the layout represents a near-complete physical implementation suitable for further refinement.

---

## 📌 Notes

* The multiplier unit was partially implemented due to its higher complexity.
* The project emphasizes **correctness, modularity, and physical design awareness** rather than optimization.

---

## 📘 Conclusion

This project demonstrates a complete 8-bit ALU implemented using static CMOS design techniques.
It showcases practical VLSI design skills, including schematic capture, layout design, and verification.
The work provides a strong foundation for future enhancements such as full multiplier implementation, layout optimization, and timing analysis.

---


## INVERTER

<img width="469" height="650" alt="Inverter" src="https://github.com/user-attachments/assets/627c91ad-4602-4c78-8d95-8e04d6afedce" />



---

##  NAND Gate

<img width="488" height="606" alt="NAND Gate" src="https://github.com/user-attachments/assets/d325031e-a0f8-446a-90ac-e3a20396c019" />




---

## NOR Gate

<img width="556" height="647" alt="NOR Gate" src="https://github.com/user-attachments/assets/76f1d918-f3a7-4173-be73-97cfcce53819" />




---

## XOR Gate

<img width="972" height="684" alt="XOR Gate" src="https://github.com/user-attachments/assets/f17bde5f-b2b0-438b-9d9e-a81c00500715" />




---

## HALF ADDER

<img width="948" height="849" alt="Half Adder" src="https://github.com/user-attachments/assets/bfcd2a19-6a73-4e1e-95ed-6830d4de3b8e" />



---
## FULL ADDER


---

## MUX 2x1



---

## 8-bit designs




--

