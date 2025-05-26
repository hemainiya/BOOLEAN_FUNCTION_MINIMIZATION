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
'''
module funct1(a,b,c,d,f1); 
input a,b,c,d; 
output f1; 
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
endmodule
'''

'''
module funct2(w,x,y,z,f2); 
input w,x,y,z; 
output f2; 
assign f2=((~y & z)|( w & y )|(x & y)); 
endmodule
'''


/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Hema sree.s RegisterNumber:212224040112*/


**RTL realization**
![Screenshot 2025-05-26 223716](https://github.com/user-attachments/assets/6455ea1a-bba2-4342-8d0a-56594921258b)
![Screenshot 2025-05-26 225632](https://github.com/user-attachments/assets/9aa16082-e07e-4845-ab46-db5fc1f9915e)

**Output:**Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

**RTL**
![Screenshot 2025-05-26 223906](https://github.com/user-attachments/assets/f5680ef5-4ad4-482d-b57c-cb512db65cac)
![Screenshot 2025-05-26 225928](https://github.com/user-attachments/assets/a9c39e9d-382e-4ec4-8a4b-7b3b11718b1d)

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

