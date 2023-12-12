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
module logicgates(a,b,y1,y2,y3,y4,y5,y6,y7);
input a,b;
output y1,y2,y3,y4,y5,y6,y7;
and(y1,a,b);
or(y2,a,b);
not(y3,a) ;
xor(y4,a,b);
nand(y5,a,b);
nor(y6,a,b);
xnor(y7,a,b);
endmodule
```
## RTL realization
 ![WhatsApp Image 2023-12-11 at 15 26 16_65351aed](https://github.com/vibinrex/Experiment--02-Implementation-of-combinational-logic-/assets/152167280/8f26a65d-8b69-48ff-9269-40828b48be16)


## Truth Table
![WhatsApp Image 2023-12-11 at 15 26 16_a9c09085](https://github.com/vibinrex/Experiment--02-Implementation-of-combinational-logic-/assets/152167280/f3ec318c-2aa8-489f-8bac-b279b6ab8d91)

## Timing Diagram
![WhatsApp Image 2023-12-11 at 15 26 15_f08848fb](https://github.com/vibinrex/Experiment--02-Implementation-of-combinational-logic-/assets/152167280/50ea01f8-087e-4d0c-8cf9-26c45265b15b)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
