```
name:Vibin rex.A
reference no:23012635
```
# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
   Hardware – PCs, Cyclone II , USB flasher
   Software – Quartus prime


## Theory
 


## Procedure
## Program:
```
module CombinationalLogic (A, B, C, D, F1):
input A,B,C,D:
output F1:
wize Abar, Bbar, Cbar, Dbar, v,w,x,y,z:
assign Abar-A
assign Bbar-8;
assign Cbar--C;
assign Dbar-D:
assign v-Abar&Bbar&Cbar&Dbaz:
assign w-A&Cbar&Dbar:
assign x Bbar&C&Dbar:
assign y-Abar&B4C4D;
assign z-B6Cbar6D;
assign Fl-v|w|x|y|z;
endmodule
```
## RTL realization

 ![ex-2 RTL](https://github.com/vibinrex/Experiment--02-Implementation-of-combinational-logic-/assets/152167280/e4e1bdec-8c27-4f75-a67a-256a4e53ecbe)


## Truth Table

![ex-2 table](https://github.com/vibinrex/Experiment--02-Implementation-of-combinational-logic-/assets/152167280/9ffe709e-ab4e-485e-8e36-d1688b13b7d8)

## Timing Diagram

![ex-2 diagram](https://github.com/vibinrex/Experiment--02-Implementation-of-combinational-logic-/assets/152167280/cdd8ea87-b19a-4391-83b7-08d4b52e16d4)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
