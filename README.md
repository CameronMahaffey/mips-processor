# 32-bit MIPS Processor in Logisim
## Overview
This project is a fully functional 32-bit MIPS processor designed and simulated in Logisim Evolution. The processor is capable of executing a subset of the MIPS instruction set, implementing fundamental components like ALU, registers, memory, and control logic.

## Features
- 32-bit architecture: Supports 32-bit registers and data paths.
- Instruction Set: Implements a subset of MIPS instructions, including:
  - Arithmetic: ADD, SUB, AND, OR, SLT, ADDI
  - Memory Access: LW, SW
  - Control Flow: BEQ
- Memory Components: Separate instruction and data memory.
- Control Unit: Handles instruction decoding and control signal generation.
- Registers: Implements a 32-register file with read/write capabilities.

## Project Files
TBD

## Getting Started
### Requirements
- Logisim Evolution (Recommended for better compatibility and performance)

### Running the Processor
1. Open xyz.circ in Logisim.
2. Load test programs into the instruction memory.
3. Start the clock and observe execution via registers and memory.

### Example Instructions
#### Arithmetic Example
ADD $t0, $t1, $t2 

SUB $t3, $t0, $t1 

#### Memory Access Example
LW $t0, 0($t1)  

SW $t2, 4($t3)  

#### Future Enhancements
- Implement additional MIPS instructions (e.g., SLT, SLL, SRL).
- Add 5-stage pipeline, pipeline hazard detection and forwarding.
- Improve performance with branch prediction.

## References
- MIPS Green Sheet
- Logisim Evolution

## License
This project is licensed under the MIT License. Feel free to use and modify it!

Developed by: Cameron Mahaffey
