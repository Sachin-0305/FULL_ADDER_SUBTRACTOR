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

**Procedure**

Write the detailed procedure here
**FULL ADDEER:**
**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: SACHIN M  RegisterNumber:212223040177
*/
V![Screenshot 2024-05-08 090407](https://github.com/Sachin-0305/FULL_ADDER_SUBTRACTOR/assets/149985717/0b890d7c-d126-4cc4-8db9-2c85db148282)

**RTL Schematic**
![Screenshot 2024-05-08 090415](https://github.com/Sachin-0305/FULL_ADDER_SUBTRACTOR/assets/149985717/689802ea-53f2-4322-be34-8cae4974cba7)


**TRUTH TABLE**

![Screenshot 2024-05-08 090421](https://github.com/Sachin-0305/FULL_ADDER_SUBTRACTOR/assets/149985717/01128dfd-09a0-489c-89b5-189671d00441)

**Output Timing Waveform**
![Screenshot 2024-05-08 090430](https://github.com/Sachin-0305/FULL_ADDER_SUBTRACTOR/assets/149985717/fd1c6952-ef75-46a5-83e7-49db5916e825)


**HALF SUBTRACTOR**
**Program:**
![Screenshot 2024-05-08 090436](https://github.com/Sachin-0305/FULL_ADDER_SUBTRACTOR/assets/149985717/ea14177d-75fd-4c01-aad4-0a6099800e07)

**RTL Schematic**
![Screenshot 2024-05-08 090442](https://github.com/Sachin-0305/FULL_ADDER_SUBTRACTOR/assets/149985717/0081d15a-7ebb-4f1b-bc04-3ee3d73a9656)

**TRUTH TABLE**
![Screenshot 2024-05-08 090448](https://github.com/Sachin-0305/FULL_ADDER_SUBTRACTOR/assets/149985717/b1d1a44e-f926-4c7f-a88d-9f6b89b6f9ef)


**Output Timing Waveform**
![Screenshot 2024-05-08 090455](https://github.com/Sachin-0305/FULL_ADDER_SUBTRACTOR/assets/149985717/6e2d15b4-1168-415e-8a66-ad36d830e4c6)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



