# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
### Half Adder Circuit:-

![Screenshot 2023-12-16 183208](https://github.com/tharunkumaran2006/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151625188/80158c90-be0a-4eb5-a00c-0b5d7b66161a)

### Full Adder Circut:-

![Screenshot 2023-12-16 183133](https://github.com/tharunkumaran2006/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151625188/2cb08117-a57e-4a86-973e-89dd078c5a7a)

### Developed by: Tharun V K
### RegisterNumber: 23003686 
*/
Logic symbol & Truthtable
RTL realization

### Output:
### RTL
### Half Adder Circuit:

![Screenshot 2023-12-16 165612](https://github.com/tharunkumaran2006/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151625188/9853c94a-2312-4919-9533-e354764ba0d2)

### Full Adder Circuit:

![Screenshot 2023-12-16 170836](https://github.com/tharunkumaran2006/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151625188/7ed749ce-bae4-45cb-9cdb-b66a2b718260)

### TIMING DIAGRAM
### Half Adder Circuit:-

![Screenshot 2023-12-16 170010](https://github.com/tharunkumaran2006/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151625188/cc396d2f-d686-47f4-85f7-4b3c8d28cb3e)

### Full Adder Circuit:-

![Screenshot 2023-12-16 171729](https://github.com/tharunkumaran2006/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151625188/2c41957e-15cb-44b2-845c-437725cf643b)


### TRUTH TABLE


### Result:
