# Major Project 1 - 8-bit ALU Using Verilog

## Description
This project implements an 8-bit Arithmetic Logic Unit (ALU) using Verilog. The ALU performs arithmetic and logical operations based on the control signals.

It is designed using combinational logic and verified through simulation.

## How it Works?
- **ADD** - Addition of two 8-bit numbers
- **SUB** - Subtraction of two 8-bit numbers
- **AND** - Bitwise AND operation
- **OR** - Bitwise OR operation
- **XOR** - Bitwise XOR operation
- **NOT** - Bitwise NOT operation

## Operations
| Sel | Operation |
| --- | --- |
| 000 | ADD |
| 001 | SUB |
| 010 | AND |
| 011 | OR |
| 100 | XOR |
| 101 | NOT |
| 110 | Shift Left |
| 111 | Shift Right |

Operations change based on Opcode:
ADD -> SUB -> AND -> OR -> XOR -> NOT


## Modules
- `design.sv` - 8-bit ALU design
- `testbench.sv` - Testbench for verification
- `waveform(3).png` - Simulation Waveform

## Simulation
- Tool: EDA Playground (Icarus Verilog + GTKWave)
- Inputs and Opcode given, outputs correctly changing
- Waveform verified successfully

## Waveform
![Waveform](waveform(3).png)

## Tools Used
- Verilog HDL
- EDA Playground
- GTKWave

## Author
Muvva Esther Rani

B.Tech - Electronics and Communication
