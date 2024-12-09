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

Developed by:Harish D RegisterNumber:*/24008988

i)module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

ii)module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule



**RTL realization**

![Screenshot (6)](https://github.com/user-attachments/assets/3a4d0986-251b-4e31-9021-157d661aa4e8)

![Screenshot (8)](https://github.com/user-attachments/assets/e6ebf41e-a6a4-47e0-bffc-5bcc598dfae1)


**RTL**

![Screenshot (4)](https://github.com/user-attachments/assets/02968454-2d32-4a8d-b50e-dc40c5076df9)

![Screenshot (7)](https://github.com/user-attachments/assets/0c661417-152c-42a6-8484-4fc84810bc53)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

