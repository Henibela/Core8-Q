# Core8-Q
An 8-bit computer system engineered in Quartus Prime.

## Technical Specifications

* **Architecture:** 8-bit logic with a shared internal bus.
* **Memory Interface:** External memory bus for unified instruction and data transfers via **MAR** and **MBR**.
* **Register Suite:**
    * **General Purpose:** A, B, C, D.
    * **Architectural:** Program Counter (PC), Instruction Register (IR), Memory Address Register (MAR), Memory Buffer Register (MBR).
    * **Control:** Tri-state buffer isolation for synchronized bus access.
* **ALU Capabilities:** * **Operations:** ADD, SUB, AND, OR, NOT, Logical Shifts.
    * **Status Flags:** Zero, Negative, Overflow.
    * **Data Path:** Multiplexer-based operand selection.
* **Control Unit:** Structured signal sequences for register transfers, ALU execution, and PC updates.
* **Platform:** Developed and synthesized using **Quartus Prime** for FPGA deployment.
