# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 

## Logic Diagram
## Procedure
## Program:
/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

Developed by: SABARI S
RegisterNumber: 212222240085 




```module exp2(A,B,C,D,F1);
input A,B,C,D;
output F1;
wire x1,x2,x3,x4,x5;
assign x1 = (~A )& (~B) & (~C) & (~D);
assign x2= (A) & (~C) & (~D);
assign x3= (~B) & (C) & (~D);
assign x4= (~A) & (B) & (C) & (D);
assign x5= (B) & (~C) & (D);
assign F1 = x1 | x2 | x3 | x4 | x5;
endmodule
```


*/
## RTL realization
![Screenshot 2023-08-25 093258](https://github.com/SABARI005/Experiment--02-Implementation-of-combinational-logic-/assets/118660461/7f1ec5c7-b2a1-45a9-869d-da5753f8c6cd)

## Output:
![Screenshot (40)](https://github.com/SABARI005/Experiment--02-Implementation-of-combinational-logic-/assets/118660461/0e0a539d-c7ca-47cb-ab74-18f517a3b8c8)


## RTL
## Timing Diagram
## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
