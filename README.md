# Digital Clock using Verilog HDL

## 📌 Project Description
This project implements a 24-hour digital clock (HH:MM:SS) using Verilog HDL.
The design uses a clock divider to generate a 1 Hz signal from the FPGA system clock,
and modular counters for seconds, minutes, and hours.

## 🧩 Modules
- Clock Divider (100 MHz → 1 Hz)
- Seconds Counter (0–59)
- Minutes Counter (0–59)
- Hours Counter (0–23)
- Top Module to integrate all blocks

## 🧪 Verification
A Verilog testbench is provided to verify the design using behavioral simulation in Vivado.
For faster simulation, the clock divider count was reduced and later restored for FPGA implementation.

## 🛠 Tools Used
- Verilog HDL
- Xilinx Vivado 2023.1

## ▶️ How to Run
1. Create a new RTL project in Vivado
2. Add all files from `src/` as design sources
3. Add `digital_clock_tb.v` from `tb/` as simulation source
4. Run behavioral simulation

## 📄 Author
Susri Rani Rauta
