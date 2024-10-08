# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

FULL ADDER 
![EX 4 TRUTH TABLE](https://github.com/user-attachments/assets/c0173d62-fe89-4b76-8936-21f0d8a38288)

FULL SUBTRACTOR 
![EX 4 1B TRUTH TABLE ](https://github.com/user-attachments/assets/58ce1173-75cc-4958-9ff2-29c41799ad5c)


 Developed by: P.THIRUMALAI 
 
 RegisterNumber: 24900297 

 
 **Program: 1(A)**

![EX 4 PROGRAM ](https://github.com/user-attachments/assets/9bfdfd0c-f081-41a8-986e-be3e043f54d8)

**RTL Schematic**

![EX 4 RTL ](https://github.com/user-attachments/assets/8acb5dce-3b57-44ec-9b4b-8dd1cf9c1d47)

**Output Timing Waveform**

![EX 4 OUTPUT ](https://github.com/user-attachments/assets/f5797839-7745-4139-b4dd-ad19551df59b)

 **Program: 1(B)**

 ![EX 4 1B PROGRAM ](https://github.com/user-attachments/assets/94eff8fa-356f-449c-8460-ce4a56f6381f)

**RTL Schematic**

![EX 4 1B RTL](https://github.com/user-attachments/assets/7dc3085d-ef28-493f-96f3-c566534aee2f)

**Output Timing Waveform**

![EX 4 1B OUTPUT](https://github.com/user-attachments/assets/dbb2f1d7-b9ff-4c33-b579-47e6736d30fb)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



