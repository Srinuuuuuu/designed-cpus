# Designed CPUs

Custom 8-bit CPU designs built to execute simple C programs, created as part of a microprocessors course assignment.

## Projects

### [logisim-evolution-cpu](./logisim-evolution-cpu/)
An 8-bit CPU designed in **Logisim Evolution**. Includes the circuit, ROM program in hex, and initial RAM contents.

### [logisim-cpu](./logisim-cpu/)
An 8-bit CPU designed in **Logisim** (classic). Features a 4-register architecture with a 256B RAM, 256B ROM, ALU, instruction decoder, and an 8-bit program counter — capable of running simple compiled C programs.

## Architecture Overview

Both CPUs share a similar 8-bit architecture:

| Component | Description |
|-----------|-------------|
| Registers | R0, R1, R2, R3 (8-bit general purpose) |
| RAM | 256 bytes |
| ROM | 256 bytes (program storage) |
| ALU | Arithmetic + logic ops (add, subtract, AND, OR, XOR, shift) |
| Program Counter | 8-bit, increments or jumps per instruction |
| Instruction Decoder | Decodes opcode and drives control signals |

## Tools

- [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution) — for `.circ` files in `logisim-evolution-cpu/`
- [Logisim](http://www.cburch.com/logisim/) — for `.circ` files in `logisim-cpu/`
