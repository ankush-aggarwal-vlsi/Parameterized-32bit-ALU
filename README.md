# Parameterized 32-bit ALU

## Overview

This project implements a parameterized 32-bit Arithmetic Logic Unit (ALU) in Verilog HDL. The design is scalable through parameterization, allowing the data width to be changed easily without modifying the core logic. The project covers RTL design, functional verification, synthesis, static timing analysis (STA), and ASIC implementation using open-source EDA tools.

## Parameter

| Parameter | Description | Default |
|-----------|-------------|---------|
| WIDTH | Data bus width | 32 |

## Inputs

| Signal | Description |
|---------|-------------|
| A | First operand |
| B | Second operand |
| Opcode | Selects the ALU operation |

## Outputs

| Signal | Description |
|---------|-------------|
| Result | ALU output |
| Zero | High when Result equals zero |
| Carry | Carry-out from arithmetic operations |
| Overflow | Signed arithmetic overflow flag |
| Negative | High when the most significant bit of Result is 1 |

## Planned Operations

- Addition (ADD)
- Subtraction (SUB)
- Bitwise AND
- Bitwise OR
- Bitwise XOR
- Bitwise NOT
- Bitwise NAND
- Bitwise NOR
- Bitwise XNOR
- Set Less Than (SLT)
- Logical Left Shift (SLL)
- Logical Right Shift (SRL)
- Arithmetic Right Shift (SRA)

## Tools

- Verilog HDL
- Icarus Verilog
- GTKWave
- Yosys
- OpenSTA
- OpenROAD
- Git
- GitHub

## Project Status

🚧 **Work in Progress – Day 1**

---

### Author

**Ankush**
