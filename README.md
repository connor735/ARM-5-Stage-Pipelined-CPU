# ARM 5-Stage Pipelined CPU

Designed in SystemVerilog for EE 469 (Computer Architecture) 
at the University of Washington.

## Overview
A fully functional 5-stage pipelined CPU implementing a subset 
of the ARM instruction set, built entirely in SystemVerilog 
and validated through simulation testbenches in ModelSim.

## Pipeline Stages
1. **Fetch** — retrieve instruction from memory
2. **Decode** — interpret instruction and read registers
3. **Execute** — ALU operations
4. **Memory** — read/write data memory
5. **Writeback** — write results back to registers

## Key Features
- **Hazard detection** — identifies data and control hazards 
  before they cause incorrect execution
- **Data forwarding** — resolves data hazards without stalling 
  the pipeline
- **Accelerated branch logic** — reduces branch penalty cycles 
  for improved performance

## Tech Stack
- **Language:** SystemVerilog
- **Simulation:** ModelSim
- **Tools:** Quartus

## Source Code
Source code is kept private per course academic integrity 
policies.

To request access for recruiting purposes, click below:

[📬 Request Access](mailto:connor7@uw.edu?subject=Code%20Access%20Request%20-%20ARM%205%20Stage%20Pipelined%20CPU&body=Hi%20Connor%2C%0A%0AI%20would%20like%20to%20view%20the%20source%20code%20for%20your%20ARM%205%20Stage%20Pipelined%20CPU%20project.%0A%0AThanks)
