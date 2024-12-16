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

![Screenshot 2024-12-15 184410](https://github.com/user-attachments/assets/31d037f1-f5c0-446d-a5ea-aff0d8cc35d5)


**Procedure**

Write the detailed procedure here

**Program:**

![Screenshot 2024-12-15 182613](https://github.com/user-attachments/assets/5a50c2d5-fb0b-4c54-87a2-f5f98994528e)
![Screenshot 2024-12-15 183934](https://github.com/user-attachments/assets/2afd839f-18f2-4d8f-a65d-e7c2f87ed3b1)


 Developed by: YOGESH D RegisterNumber:24006488

**RTL Schematic**

![Screenshot 2024-12-15 182637](https://github.com/user-attachments/assets/fdc70126-695d-40dd-bd2c-578685ac32b7)
![Screenshot 2024-12-15 184005](https://github.com/user-attachments/assets/02326b70-7b1c-418a-9f9d-549651720344)


**Output Timing Waveform**
![Screenshot 2024-12-15 182851](https://github.com/user-attachments/assets/42e0b932-a81e-41d7-abfa-27cfa13a4ef1)
![Screenshot 2024-12-15 184148](https://github.com/user-attachments/assets/225e78ff-7799-4f7c-9132-bf7b6fea5be3)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



