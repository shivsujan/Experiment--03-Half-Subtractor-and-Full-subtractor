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

Developed by: S R SHIV SUJAN

RegisterNumber:  23004611

Code:

Half Subtractor:

![Exp4 hs code](https://github.com/shivsujan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145633245/c0a03315-b438-437a-93fc-8716762c5a02)

Full Subtractor:

![Exp4 fs code](https://github.com/shivsujan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145633245/1ace6df4-dbe5-4d8e-ac6f-0334ee64ab09)


Truth Table:

Half Subtractor:

![Exp4 truthtable hs](https://github.com/shivsujan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145633245/f4a101dd-038b-43ce-96fc-3460a64fcdde)

Full Subtractor:

![Exp4 truthtable fs](https://github.com/shivsujan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145633245/f6c3987f-5224-4b10-b45e-8360261c0c0f)

RTL Diagram:

Half Subtractor:

![Exp4 hs RTL diagram](https://github.com/shivsujan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145633245/be48a0f0-2a16-4996-bae1-0c895b1ca8e6)

Full Subtractor;

![Exp4 fs RTL diagram](https://github.com/shivsujan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145633245/2ece1d3f-e715-49fb-9602-5ea8f83330a9)

## Output:

Half Subtractor:

![Exp3 hs wave](https://github.com/shivsujan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145633245/e9ddd290-2aa3-49fa-8e13-15c8dbc95eb2)

Full Subtractor:

![Exp3 fs wave](https://github.com/shivsujan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145633245/575831d4-c90a-47f6-9c54-536978f85d47)






## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
