# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

![WhatsApp Image 2025-03-17 at 14 16 06_930ccbdf](https://github.com/user-attachments/assets/0dba7295-a42a-4c66-bfb4-760a90370a67)

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.*/
```
module Exp2(a,b,c,d,F1,w,x,y,z,F2);
input a,b,c,d,w,x,y,z;
output F1,F2;
assign F1=((~a&b&d)|(~b&~d)|(a&b&~c));
assign F2=((~y&z)|(x&y)|(w&y));
endmodule
```

Developed by: Jones Benedict A P

RegisterNumber:212224040142



**RTL realization**

**Output:**

**RTL**
![Logic Diagram](https://github.com/user-attachments/assets/fcafc314-7a28-4d99-8d95-580254120369)


**Timing Diagram**
![Timing Diagram](https://github.com/user-attachments/assets/bedb09ce-ffd5-4331-a14c-e221c3032bd5)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

