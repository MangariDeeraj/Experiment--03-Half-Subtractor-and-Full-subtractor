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

![Screenshot 2023-11-27 205247](https://github.com/MangariDeeraj/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365485/59d28858-4804-48b8-a196-910a66e4c13a)

Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 

![Screenshot 2023-11-27 205657](https://github.com/MangariDeeraj/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365485/59f4ae5e-45af-4d10-b599-34b9fbe769ca)

Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure
![Screenshot 2023-11-27 204742](https://github.com/MangariDeeraj/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365485/2d4f235f-db00-448b-b667-908887bcdc5a)


![Screenshot 2023-11-27 205639](https://github.com/MangariDeeraj/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365485/99cf0f33-16b0-4d1a-b7c8-bd68f3a7d96e)

Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/

## Output:

## Truthtable
![WhatsApp Image 2023-11-27 at 20 54 49_f9c1188f](https://github.com/MangariDeeraj/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365485/ff8c6e82-13c7-40c4-ab93-7a93520a271d)

![WhatsApp Image 2023-11-27 at 20 55 26_ed235468](https://github.com/MangariDeeraj/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365485/662f2f2d-2c4b-4c88-86d2-1066a745a0cb)


##  RTL realization


## Timing diagram 
![Screenshot 2023-11-27 205358](https://github.com/MangariDeeraj/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365485/10024065-b7ae-43ee-999f-a879fd035cd4)
![Screenshot 2023-11-27 205818](https://github.com/MangariDeeraj/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365485/6edf68f9-1748-4be9-af33-4f362923ad4e)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
