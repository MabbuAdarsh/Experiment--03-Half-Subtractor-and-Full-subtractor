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
![Screenshot 2023-11-26 143908](https://github.com/MabbuAdarsh/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365583/a455671c-24a6-4e51-bb5b-75c6242dfdb6)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![Screenshot 2023-11-26 164129](https://github.com/MabbuAdarsh/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365583/a10488cb-5efa-4078-907c-156b8cfb4ba8)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:
/*![Screenshot 2023-11-26 144204](https://github.com/MabbuAdarsh/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365583/13625a75-6c99-4d0a-a9d8-dc2036125474)

![Screenshot 2023-11-26 163847](https://github.com/MabbuAdarsh/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365583/2d63da33-a5ff-4db3-a883-7e11bd0d1dfb)

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/

## Output:

## Truthtable
![OIP](https://github.com/MabbuAdarsh/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365583/81524d42-f1d0-4508-ab90-bcf6c80a8024)

![OIP](https://github.com/MabbuAdarsh/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365583/cd58b91e-f9c6-48db-a6bd-46c028bdd251)


##  RTL realization


## Timing diagram 

![Screenshot 2023-11-26 150532](https://github.com/MabbuAdarsh/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365583/8069083e-1a76-4f1e-8a06-75e5c4893686)

![Screenshot 2023-11-26 143851](https://github.com/MabbuAdarsh/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365583/18b704b8-7d13-4b83-9398-98ddefcf3ef2)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
