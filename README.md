# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus primE


## Theory
 

## Logic Diagram
logic diagram is used in their method
## Procedure
## Program:
/*
module cs(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
wire a1,a2,a3,a4,a5,b1,b2,b3,b4,b5;
assign a1=(~a&(~b)&(~c)&(~d));
assign a2=(a&c&(~d));
assign a3=((~b)&c&(~d));
assign a4=(~a&b&c&d);
assign a5=(b&(~c)&d);
assign f1=a1|a2|a3|a4|a5;
assign b1=(x&(~y)&z);
assign b2=(~x&(~y)&z);
assign b3=(~w&x&y);
assign b4=(w&(~x)&y);
assign b5=(w&y&z);
assign f2=b1|b2|b3|b4|b5;
endmodule
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: PREM KUMAR
RegisterNumber: 23013598 
*/
## RTL realization

## Output:![output](![cs output](https://github.com/premsuryas/Experiment--02-Implementation-of-combinational-logic-/assets/147473858/5de5cc2a-c748-440a-9096-72d84a424050)

## RTL:![output](![combinational circuit rtl](https://github.com/premsuryas/Experiment--02-Implementation-of-combinational-logic-/assets/147473858/1171978b-476f-49ee-8bec-168ab0d1327e)

## Timing Diagram
## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
