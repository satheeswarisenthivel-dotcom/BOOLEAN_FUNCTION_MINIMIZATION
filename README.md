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

Developed by: S.SATHEESWARI
RegisterNumber:25017493

```
module ppt(
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule

```

**RTL realization Output:**


<img width="1520" height="826" alt="Screenshot 2025-11-19 090912" src="https://github.com/user-attachments/assets/85830898-ff89-415a-8dbb-95a63b91c748" />


**RTL**


<img width="741" height="335" alt="Screenshot 2025-11-24 084530" src="https://github.com/user-attachments/assets/501c3afc-e729-4e6c-9f9a-0d3f374e8912" />



**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

