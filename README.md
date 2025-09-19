# EXP1---Multiplexer-Github
verilog-exp1-mux/
├── README.md
├── gate_level/
│   ├── mux4_1.v
│   └── mux4_1_tb.v
├── dataflow/
│   ├── mux4_1.v
│   └── mux4_1_tb.v
├── behavioral/
│   ├── mux4_1.v
│   └── mux4_1_tb.v
├── structural/
│   ├── mux2to1.v
│   ├── mux4to1.v
│   └── mux4to1_tb.v
git init
git add .
git commit -m "Initial commit: Verilog MUX experiment"
# Verilog Experiment 1: 4:1 Multiplexer (MUX)

This repository contains four modeling styles of a 4:1 multiplexer using Verilog HDL:

- **Gate Level Modeling**
- **Dataflow Modeling**
- **Behavioral Modeling**
- **Structural Modeling**

Each folder includes the Verilog source file and its corresponding testbench.

## 🧪 Simulation

To simulate, use any Verilog simulator like:
- Vivado
- ModelSim
- EDA Playground (online)

## 📁 Folder Structure

- `gate_level/`: Uses basic gates (`and`, `or`, `not`)
- `dataflow/`: Uses `assign` statements
- `behavioral/`: Uses `always` block with `case`
- `structural/`: Builds MUX using smaller modules (2:1 MUX)

## 👨‍💻 Author

Mohan Ram P  
Roll No: 212223060164
