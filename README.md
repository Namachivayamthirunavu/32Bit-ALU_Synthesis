# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :
![Screenshot 2025-05-19 170559](https://github.com/user-attachments/assets/d58325a4-2cd4-47d1-b91a-618785d13d76)

#### Area report:
![Screenshot 2025-05-19 170629](https://github.com/user-attachments/assets/1d8a3abf-4400-4055-b1bd-eed875ca93d2)

#### Power Report:
![Screenshot 2025-05-19 170713](https://github.com/user-attachments/assets/6e5aff30-d011-4d21-9370-fc41c1d44661)
#### Timing report
![Screenshot 2025-05-19 170859](https://github.com/user-attachments/assets/5dc3a402-6d67-4723-bd32-3569df062cbc)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
