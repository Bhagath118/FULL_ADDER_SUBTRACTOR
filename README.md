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

**Program:**

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
```
Developed by: BHAGATHKRISHNA.A
RegisterNumber:212223230029
```

**Full Adder:**

![image](https://github.com/Gokhulraj2005/FULL_ADDER_SUBTRACTOR/assets/138849253/a297a7e6-cf3f-44dc-b3a6-26e15d2eac4e)



**Full Subtractor**

![image](https://github.com/Gokhulraj2005/FULL_ADDER_SUBTRACTOR/assets/138849253/5c08e4b6-2ccb-4e62-91a2-384b29e10520)



**RTL Schematic**

**Full Adder:**

![image](https://github.com/Gokhulraj2005/FULL_ADDER_SUBTRACTOR/assets/138849253/5f9c5c4e-14f9-47ad-aa97-825298eb9f4c)

**Full Subtractor**

![image](https://github.com/Gokhulraj2005/FULL_ADDER_SUBTRACTOR/assets/138849253/f5c1c7b6-c5ea-451a-b946-6b0c4b0c3b3c)

**Output Timing Waveform**

**Full Adder:**

![image](https://github.com/Gokhulraj2005/FULL_ADDER_SUBTRACTOR/assets/138849253/44b12040-5bc1-41c7-ad1c-aec71a2ea415)


**Full Subtractor**

![image](https://github.com/Gokhulraj2005/FULL_ADDER_SUBTRACTOR/assets/138849253/668079eb-68f5-49af-8c09-23fbbcc8d30e)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.






