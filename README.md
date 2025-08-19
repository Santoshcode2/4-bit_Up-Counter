4-Bit Up Counter – RTL to GDSII Flow
📌 Project Overview

This project demonstrates the end-to-end VLSI design flow for a 4-bit up counter, starting from Verilog RTL coding to generating the final GDSII file. The flow covers functional verification, logical synthesis, physical design, and layout generation using industry-standard EDA tools.

The project was executed under the guidance of Dr. Hemanta Kumar Mondal.

🛠️ Tools & Methodology
1. RTL Design & Verification

Language Used: Verilog HDL

Steps:

Implemented Verilog RTL code for a 4-bit up counter.

Developed a testbench for functional verification.

Performed elaboration, compilation, and simulation.

Verified design correctness through waveform generation.

Tools Used:

Simulation & Verification: Cadence Xcelium (or ModelSim, Icarus Verilog, etc.)

2. Logical Synthesis

Tool Used: Cadence Genus

Steps:

Synthesized the RTL design into a gate-level netlist.

Applied timing, area, and power constraints.

Ensured design met functional equivalence post-synthesis.

3. Physical Design

Tool Used: Cadence Innovus

Steps:

Floorplanning – Defined chip dimensions, I/O placement, and block arrangement.

Power Planning – Implemented power rings, straps, and distribution network.

Placement – Placed standard cells while optimizing for area and timing.

Clock Tree Synthesis (CTS) – Built a balanced clock distribution network.

Routing – Connected all cells and I/O pins with optimized interconnects.

Timing Analysis – Ensured timing closure across all paths.

4. Signoff & Layout

Steps:

Performed Design Rule Checks (DRC) and Layout vs Schematic (LVS) verification.

Generated the final GDSII file for tape-out.

Imported GDSII into Cadence Virtuoso to obtain the final layout view.

🎯 Achievements

Successfully executed end-to-end RTL-to-GDSII flow for a custom digital block.

Gained hands-on expertise in:

RTL coding and testbench design

Simulation and waveform analysis

Logical synthesis with Cadence Genus

Physical design with Cadence Innovus (floorplanning, power planning, placement, CTS, routing)

Signoff and GDSII generation

Achieved optimized layouts that met timing, area, and power constraints.
