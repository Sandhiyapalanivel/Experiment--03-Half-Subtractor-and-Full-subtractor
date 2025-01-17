# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: SANDHIYA.P

RegisterNumber:  23012555
*/

### HALF SUBTRACTOR PROGRAM:

![image](https://github.com/Sandhiyapalanivel/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145743091/db8cf59c-e9dc-449f-a2e8-f8f3cde15589)

### HALF SUBTRACTOR TRUTH TABLE:

![image](https://github.com/Sandhiyapalanivel/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145743091/03761380-3a15-4096-b549-1afeeeb3d8c8)


### HALF SUBTRACTOR RTL VIEW:

![image](https://github.com/Sandhiyapalanivel/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145743091/bba64dc8-acf5-458e-9b2c-a6fa81d34f27)

### HALF SUBTRACTOR OUTPUT:

![image](https://github.com/Sandhiyapalanivel/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145743091/db0ee482-7d33-4c0f-b622-52051e94d965)

### FULL SUBTRACTOR PROGRAM:

![image](https://github.com/Sandhiyapalanivel/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145743091/446a981c-5a14-45aa-a3c2-84c5f3d1ae47)

### FULL SUBTRACTOR TRUTH TABLE:

![image](https://github.com/Sandhiyapalanivel/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145743091/10e6657c-e869-4b5f-accf-204ce56c3f8b)



### FULL SUBTRACTOR RTL VIEW:


![image](https://github.com/Sandhiyapalanivel/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145743091/6f3daee0-ff82-4bd7-ad3b-d7e1f4e926cb)

### FULL SUBTRACTOR OUTPUT:

![image](https://github.com/Sandhiyapalanivel/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145743091/fa9bc218-0217-4815-9633-39c0d54fca58)




## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
