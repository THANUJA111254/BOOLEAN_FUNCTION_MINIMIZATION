 # BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
mmodule deexp2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
assign f2=((~y & z) | (w & y )|(x & y));
endmodule

/* Program  to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:V.PANGA THANUJA
RegisterNumber: 24900052

```
**RTL realization**
![image](https://github.com/user-attachments/assets/ba1e90a3-8628-4ba7-a0d3-9bb72ddbcdfd)


**RTL**
![image](https://github.com/user-attachments/assets/5d3e912b-ea25-4447-8cea-c1f8d797c752)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

