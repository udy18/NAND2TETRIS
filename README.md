# NAND2TETRIS
Building a 16-bit computer from Nand gates up. 

Course official website:https://www.nand2tetris.org/


## Project 1: Boolean Logic
Implemented 15+ combinational circuits in HDL:
- Basic gates: And, Or, Not, Xor, Nand
- Mux/DMux: 2-way, 4-way, 8-way
- Multi-bit gates: And16, Or16, Not16, Mux16

Key insight: A mux/dmux is just routing logic. sel controls which path data takes. Build in layers—each chip composes from primitives below.

## What's Next
- Project 2: Arithmetic (ALU, adders)

## Running
HDL files compile in the provided hardware simulator. No external dependencies.

