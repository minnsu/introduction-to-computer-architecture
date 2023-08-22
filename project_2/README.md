# Project 2 - Single-cycle RISC-V CPU Simulator

## Implement the following command
```
add, sub, addi
xor, or, and, xori , ori , andi
slli, srli , srai , sll , srl , sra
slti, slt
auipc, lui
jal, jalr
beq, bne , blt , bge
lw, sw
```

## Program takes 2 or 3 command-line arguments.
- if the program takes 2 arguments, first argument is input file name that has binary instructions. And second argument is number of instructions to execute.
- if the program takes 3 arguments, first argument is same as above. Second argument is input file name of binary data(data memory), and third argument is number of instructions to execute.

## Registers
- Every registers are initialized to 0 and x0 register is fixed to 0
- At the last of program should print registers values.

## Memory
- Address range from 0x10000000 to 0x1000FFFF is used to data memory(total 64KB).
- Therefore, input binary data file is loaded onto 0x10000000~ and remaining bytes are initialized to 0xFF.
