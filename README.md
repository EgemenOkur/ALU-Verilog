ALU is the fundamental building block of the processor, which is responsible for
carrying out the arithmetic and logic functions. 

ALU comprises of combinatorial
logic that implements arithmetic operations such as Addition, Subtraction and
Multiplication,and logic operations such as AND, OR, NOT. The ALU gets
operands from the register file or memory. 


The ALU reads two input operands In A and In B. The operation to perform on
these input operands is selected using the control input ALU_Sel. The ALU
performs the selected operation on the input operands In A and In B and
produces the output, ALU_Out.

ALU is purely combinatorial logic and contains no registers or latches.
Flag: ALU updates the conditional flag, which is used by the processor to
perform other operations like condition checking and branching. In this example
one flag is implemented:

Carry out - If the addition of the two operands gives the carry out this flag
is set 
