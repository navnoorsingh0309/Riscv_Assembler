# Riscv_Assembler

## Overview

We have implemented a simple assembler which assembler **Risc-V Assembly Code** to **Machine Code**. The assembler supports various Risc-V instructions including R-type, I-Type, S-Type, SB-Type, U-Type, UJ-Type.

## Authors

- [@navnoorsingh0309](https://www.github.com/navnoorsingh0309) Navnoor Singh Bal (2022EEB1193)
- [@shravanjindal](https://www.github.com/shravanjindal) Shravan Jindal (2022CSB1124)
- [@Adityachandanshive](https://www.github.com/Adityachandanshive) Aditya Chandanshive (2022CSB1063)

## Key Features:

- Converts assembly code to machine code
- Support various Risc-V instructions
- Support directives like (.data, .text, .word, .half, .byte, .asciiz)
- Support labels

## Usage

1. Write your risc-v instruction in `main.asm` file
2. Run the assembler for an input assembly file

```
g++ main.cpp -o main
```

3. The assembler will generate an output file with machine code as `main.mc`.

