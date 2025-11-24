# Intel → Xilinx Migration Guide (HW/SW)
# A technical documentation project by Menyar Hees

This repository contains a complete, structured technical guide that documents the transition from Intel/Altera FPGA workflows (Quartus, Platform Designer, Nios II) to AMD/Xilinx toolchains (Vivado, IP Integrator, MicroBlaze-V, Vitis).
The material is designed as a practical reference for engineers moving between these ecosystems.

📘 What This Project Covers

This guide is not a simple comparison — it is a hands-on walkthrough showing how to rebuild the same embedded design concepts using Xilinx tools.

The documentation includes:

# 1️⃣ Toolchain Transition

Quartus → Vivado

Platform Designer → IP Integrator

Qsys interconnect → AXI interconnect

Nios II → MicroBlaze-V soft processor

ModelsSim → Vivado Simulator

# 2️⃣ Hardware Architecture Topics

Soft-core CPU design

MicroBlaze-V features vs. Nios II

Internal BRAM and external DDR memory integration

AXI buses (Lite, Full, Stream)

AXI Timer with interrupt handling

Block design creation in Vivado

Pin planning and board adaptation

# 3️⃣ Software Development (Vitis)

BSP generation

Linker scripts

Embedded C application structure

Using interrupts with AXI timer

Debugging with Vivado ILA & VIO

Bare-metal development

# 4️⃣ Simulation & Debugging

Vivado simulation setup

Hierarchy, waves, and testbench flow

Using TCL to automate synthesis, simulation, or block creation

Hardware debugging using Integrated Logic Analyzer (ILA)

Runtime probing with VIO

# 📂 Repository Contents

Your repository should contain the following PDF guides
📁 Intel-to-Xilinx-Migration-Guide
│
├── introduction.pdf
├── Comparison Between MicroBlaze-V and Nios II.pdf
├── IP Integrator vs Platform Designer.pdf
├── Internal and External RAM in IP Integrator.pdf
├── MicroBlaze V.pdf
│
├── Simulation in Vivado.pdf
├── Using Tcl in Vivado.pdf
├── Implementation in Vivado.pdf
├── Vivado Debug tools (ILA & VIO).pdf
│
└── README

