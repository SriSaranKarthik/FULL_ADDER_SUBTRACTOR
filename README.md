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

![image](https://github.com/user-attachments/assets/b66c8481-39f2-4588-a0e4-35de3bfcf700)

![image](https://github.com/user-attachments/assets/c8068d60-34b0-4482-b103-ab098a498c93)

**Procedure**
Write the detailed procedure here
1 Type the program in Quartus software. 2 Compile
and run the program. 3 Generate the RTL schematic and save the logic diagram. 4
Create nodes for inputs and outputs to generate the timing diagram. 5 For different
input combinations generate the timing diagram.

**Program:**

![image](https://github.com/user-attachments/assets/288bd99a-fdf2-436c-a5cf-5f9d92f49463)

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by:K.SriSaran Karthik RegisterNumber:24007192
*/

**RTL Schematic**

![image](https://github.com/user-attachments/assets/b3c91bde-2712-41be-91b6-937058ab9627)


**Output Timing Waveform**

![image](https://github.com/user-attachments/assets/d0211bef-5f1c-4ff4-8b54-ad3233d8e26c)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



