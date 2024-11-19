# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

PROGRAM CODES

PART 1

module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule


PART 2

module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule


Developed by: RegisterNumber:24009014


**RTL realization**

**Output:**

PART 1

**RTL**

![Screenshot 2024-11-12 045818](https://github.com/user-attachments/assets/6ab20e0b-a9f2-4779-a695-2d50a6998d8d)

**Timing Diagram**

![Screenshot 2024-11-12 050250](https://github.com/user-attachments/assets/8bab3a50-bcd0-4d89-b558-d46416ba50ab)


PART 2

**RTL**

![Screenshot 2024-11-19 034234](https://github.com/user-attachments/assets/99362b1b-b47b-4828-a355-6520d033fcd7)

**Timing Diagram**

![Screenshot 2024-11-19 034407](https://github.com/user-attachments/assets/f202051a-8966-40ed-a62f-e294de3f1274)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

