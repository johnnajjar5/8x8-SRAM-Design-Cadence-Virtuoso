# 8×8 SRAM Memory System |  VLSI Design Project ⚙️🔬

## 📚 Project Overview

This project focuses on the design and implementation of an **8×8 Static Random-Access Memory (SRAM) register file** as part of an 8-bit CMOS Microprocessor Data Path for the *Introduction to VLSI Design (31540)* course at Braude Academic College of Engineering.

The SRAM serves as the register file of the microprocessor data path, providing temporary data storage and supplying operands to the Arithmetic Logic Unit (ALU). The overall data path also includes an ALU and a barrel shifter, designed using CMOS circuitry and Cadence VLSI design tools.

The memory architecture consists of 64 storage bits organized as 8 words × 8 bits, with address decoding and read/write control circuitry.

## 🎯 Key Features

- **8×8 SRAM Architecture:** 64-bit memory array organized into eight 8-bit registers.
- **CMOS 6T SRAM Cells:** Transistor-level memory cell design.
- **Address Decoding:** 3-bit register addressing for selecting memory locations.
- **Read/Write Operations:** Memory access control for reading stored data and writing new data.
- **Multi-Port Register File:** Two 8-bit read data paths and one 8-bit write data path, according to the project specification.
- **Input Data Selection:** Multiplexer-based selection between ALU output and external memory bus data.
- **Enable Control:** Controlled memory access using register-file enable and read/write signals.
- **Hierarchical VLSI Design:** Modular circuit design using schematic, symbol, and layout views.

## 🏗️ SRAM Architecture

The SRAM register file is designed as an 8×8 memory array.

| Parameter | Specification |
|---|---|
| Memory Type | Static Random-Access Memory |
| Architecture | 8×8 |
| Total Capacity | 64 bits |
| Organization | 8 words × 8 bits |
| Memory Cell | 6T SRAM |
| Address Width | 3 bits per register address |
| Supply Voltage | 1.8 V |
| Design Technology | CMOS |

## 🛠️ Design Methodology

1. **CMOS Logic Design** – Design of the required transistor-level logic components.
2. **6T SRAM Cell Design** – Implementation of the fundamental SRAM storage cell.
3. **Address Decoder** – Design of the 3-to-8 decoder for register selection.
4. **Read/Write Control Logic** – Implementation of memory access and enable control.
5. **Data Input Selection** – Integration of the input multiplexer and data latch.
6. **SRAM Array Integration** – Organization of the memory cells into an 8×8 register file.
7. **Schematic and Layout Design** – Hierarchical circuit implementation using Cadence Virtuoso.
8. **Simulation and Verification** – Functional evaluation of the memory operations.

## 🔄 Read/Write Operation

The register file supports memory read and write operations controlled by the address, enable, and read/write signals.

- **Read Operation:** Selects a register address and provides the stored data to the data path.
- **Write Operation:** Stores the selected 8-bit input word in the addressed memory location.
- **Enable Control:** Controls access to the register file and its decoder.
- **Input Selection:** Selects between external memory bus data and ALU output.

## ⏱️ Clocking Scheme

The complete data path uses two non-overlapping clock phases:

- **CLK1:** Controls loading of the register-file input latch.
- **CLK2:** Controls loading of the ALU input latch.

The two-phase clocking scheme coordinates data transfer between the register file and the ALU.

## 💻 Technologies & Tools

- Cadence Virtuoso
- CMOS Transistor-Level Design
- VLSI Circuit Design
- SRAM Architecture
- Custom IC Layout
- Schematic Design
- Circuit Simulation
- Hierarchical Design

## 📸 Project Results

This section will include actual implementation screenshots and results:

- 6T SRAM cell schematic
- SRAM cell transistor-level layout
- Address decoder schematic
- Read/write control circuitry
- Complete 8×8 SRAM register-file schematic
- SRAM layout
- Functional simulation waveforms

## 🎓 Project Objectives

- Understand CMOS-based SRAM architecture and memory operation.
- Apply transistor-level circuit design principles.
- Develop address decoding and memory control circuitry.
- Gain practical experience with Cadence Virtuoso.
- Understand hierarchical schematic and physical layout design.
- Explore the integration of memory components into a microprocessor data path.

## 👨‍💻 Author

**John Najjar** 

**shaker amon**

**Wajdi Abo-Rees**

**Mohamed Sawaed**

Electrical & Electronics Engineering Graduate  
Braude Academic College of Engineering
