# Basic-Computer-Implementation

This project simulates a basic computer system consisting of a memory unit, arithmetic/logic unit (ALU), and a group of registers, all interconnected through a common bus. The implementation focuses on creating a simulation for the memory system and key registers, with a control unit to execute specific program instructions.

## Features

- **Memory (RAM)**:
  - 128 addresses (words), each word is 16 bits.
  - Supports read and write operations.
  - Connected to the common bus via input and output lines.

- **Registers**:
  - **Address Register (AR)**: Linked to the memory address lines.
  - **Data Register (DR)**
  - **Temporary Register (TR)**
  - **Accumulator Register (AC)**
  - **Program Counter (PC)**: Implemented using a counter instead of a regular register.
  - **Instruction Register (IR)**

- **Control Unit**:
  - Includes decoders, sequence counters, and logic gates.
  - Manages control signals for registers, bus signals, and ALU operations.

- **Bus System**:
  - 3 control select lines: S2, S1, and S0 to manage data flow.

## Project Requirements

1. **Simulation of the Memory System**:
   - Implement a memory with 128 addresses, each containing 16-bit words.
   - The memory should support reading and writing through the bus system.
   
2. **Registers and Control Logic**:
   - AR output is connected to the memory's address lines.
   - Modify the basic computer by implementing the PC register as a counter.
   - Add a control unit with necessary components to execute a specific program, ensuring unused control signals are zero for stability.


## Contact

For any questions or feedback, please contact [roger.elias669@gmail.com](mailto:roger.elias669@gmail.com).

