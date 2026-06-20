# 4-bit ALU Design

A Verilog-based 4-bit Arithmetic Logic Unit (ALU) supporting eight operations, including AND, OR, XOR, NOT, Addition, Subtraction, Increment, and Decrement. The design was implemented using a modular and hierarchical architecture, starting with a gate-level Full Adder built from primitive logic gates and extending it into reusable arithmetic submodules integrated within the top-level ALU.

The ALU includes complete status flag generation (Carry, Negative, Zero, and Overflow) with proper overflow detection for arithmetic operations. Functionality was verified through simulation and testing in Multisim Workbench using probes and 7-segment displays across multiple input combinations. The project demonstrates practical experience with hierarchical digital design, hardware abstraction levels, and Verilog-based hardware development.
