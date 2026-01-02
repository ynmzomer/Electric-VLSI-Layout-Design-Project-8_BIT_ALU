
8-Bit ALU Physical VLSI Design Project

This project presents the design and implementation of an 8-bit Arithmetic Logic Unit (ALU) using static CMOS technology. The work focuses on full custom VLSI design, covering the complete flow from logic design to physical layout. The ALU supports a wide range of arithmetic and logical operations controlled by a 4-bit opcode and is implemented using a modular and hierarchical design approach.

Project Overview

The main objective of this project is to design a fully functional 8-bit ALU at the transistor level, emphasizing layout correctness, signal integrity, and modularity. Each functional block was designed individually and later integrated into a complete data path. The project was implemented as part of a Physical VLSI Design course.

Supported Operations

The ALU supports the following operations:

Arithmetic Operations

Addition

Subtraction

Multiplication (partially implemented)

Logical Operations

AND

OR

XOR

NAND

NOR

NOT

Shift Operations

Logical Left Shift

Logical Right Shift

Arithmetic Left Shift

Arithmetic Right Shift

Comparison Operations

Equal

Greater Than

Less Than

All operations are selected using a 4-bit opcode, and the output is either 8-bit or 16-bit depending on the operation.

Design Methodology

Static CMOS logic used throughout the entire design

Transmission-gate–based multiplexers for reduced transistor count and improved performance

Modular design approach (1-bit blocks extended to 8-bit architecture)

Custom layout for all functional blocks

Two-metal-layer layout constraint

Schematic vs. layout verification using NCC

Buffer insertion to improve signal integrity and timing

Key Components Implemented

8-bit Full Adder

8-bit Subtractor (using A + B’ + 1 method)

8-bit Logical Units (AND, OR, XOR, NAND, NOR)

8-bit Comparator (Equal, Greater Than, Less Than)

Shifting Units

Transmission-Gate Based Multiplexers

Tools and Techniques

Static CMOS design methodology

Custom transistor-level design

Layout optimization for performance and reliability

Manual verification of functional correctness

Limitations

The multiplication unit was planned but could not be fully completed due to its higher complexity and time constraints. However, all other components were successfully implemented and verified.

Conclusion

This project demonstrates a complete and functional 8-bit ALU implemented using full-custom VLSI design techniques. It highlights key concepts such as modular design, CMOS logic implementation, and physical layout optimization. The design serves as a strong foundation for future extensions, such as completing the multiplier or optimizing for area and power.

Final Layout and NCC Status

The schematic design of the ALU was completed and verified successfully, and all functional blocks operate correctly at the schematic level. However, the final physical layout contains NCC (Netlist Consistency Check) errors.

These errors are related to mismatches between the schematic and the layout, mainly caused by routing complexity, dense interconnections, and limited time during the physical design phase. Despite these issues, the schematic implementation accurately represents the intended functionality, and all major operations were validated through simulation.
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

