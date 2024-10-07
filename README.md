# NAND-Gate

A **NAND gate** (short for "Not AND") is a fundamental digital logic gate that outputs a logic "0" (low) only when all its inputs are logic "1" (high); in all other cases, it outputs a logic "1" (high). Essentially, the NAND gate is the inverse of the AND gate.

### Truth Table for 2-input NAND Gate:
| Input A | Input B | Output Y (A NAND B) |
|---------|---------|---------------------|
|    0    |    0    |          1          |
|    0    |    1    |          1          |
|    1    |    0    |          1          |
|    1    |    1    |          0          |

### Key Characteristics:
- **Symbol**: A NAND gate is typically represented as an AND gate symbol with a small circle (denoting negation) at the output.
- **Boolean Expression**: The output \( Y \) of a 2-input NAND gate is expressed as:  
  \[ Y = \overline{A \cdot B} \]  
  Where \( \cdot \) represents the AND operation and \( \overline{} \) represents the NOT operation.

### Applications:
- **Universal Gate**: The NAND gate is called a "universal gate" because any other logic gate (AND, OR, NOT, XOR, etc.) can be constructed using only NAND gates.
- **Memory**: It is commonly used in the design of memory circuits like flip-flops and registers.
- **Digital Circuits**: NAND gates are fundamental building blocks in various combinational and sequential circuits.
