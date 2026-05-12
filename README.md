# 4x1 Multiplexer (MUX) using Verilog HDL

This project implements a 4x1 Multiplexer using Verilog HDL and verifies its functionality through simulation in Xilinx Vivado.

A multiplexer is a combinational logic circuit that selects one input from multiple inputs and transfers it to a single output based on the select lines.

--------------------------------------------------

## Project Files

mux_4x1.v  
Contains the RTL design of the 4x1 multiplexer.

mux_4x1_tb.v  
Contains the testbench used for simulation and verification.

simulation.png  
Waveform output obtained after simulation.

README.md  
Project documentation.

--------------------------------------------------

## Truth Table

S1  S0   Output

0   0    I0  
0   1    I1  
1   0    I2  
1   1    I3  

--------------------------------------------------

## Working

The design uses:
- Four input lines: I0, I1, I2, I3
- Two select lines: S1 and S0
- One output line: Y

The select lines determine which input is connected to the output.

If:
- S = 00, output becomes I0
- S = 01, output becomes I1
- S = 10, output becomes I2
- S = 11, output becomes I3

--------------------------------------------------

## Tools Used

- Verilog HDL
- Xilinx Vivado
- XSIM Simulator

--------------------------------------------------

## Applications

- Data selection circuits
- Bus routing
- Communication systems
- ALU datapath selection
- Digital system design

--------------------------------------------------

## What I Learned

- Basics of combinational circuit design
- Verilog behavioral modeling
- Writing testbenches
- RTL simulation and debugging in Vivado

--------------------------------------------------

## Author

Harsh  
