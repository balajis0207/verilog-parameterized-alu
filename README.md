# verilog-parameterized-alu

# Parameterized ALU in Verilog HDL

## 📌 Overview
This project implements a fully synthesizable, parameterized Arithmetic Logic Unit (ALU) using Verilog HDL.  
The ALU supports configurable data width and multiple arithmetic and logical operations, verified through simulation and synthesis in Vivado.

## ✨ Features
- Parameterized data width (4/8/16-bit)
- Opcode-based operation selection
- Arithmetic: ADD, SUB, INC, DEC
- Logical: AND, OR, XOR, NOT
- Status flags: Zero, Carry, Overflow, Negative, Parity
- Pure combinational RTL (no latches, no FFs)

## 🛠 Tools Used
- Verilog HDL
- Xilinx Vivado (Simulation & Synthesis)
- GTKWave (optional)

## 🧩 ALU Architecture
![RTL Schematic](docs/rtl_schematic.png)

## 🔬 Simulation Results
![Waveform](docs/waveform.png)

## 📁 Project Structure

## 🚀 How to Run
1. Open Vivado
2. Create a new project
3. Add `rtl/alu.v` and `tb/alu_tb.v`
4. Run Behavioral Simulation
5. View waveform and RTL schematic

## 📈 Learning Outcomes
- Hands-on RTL design using Verilog
- Understanding opcode-based datapath design
- Parameterization for scalable hardware
- Synthesis-aware coding practices

## 📜 License
MIT License
