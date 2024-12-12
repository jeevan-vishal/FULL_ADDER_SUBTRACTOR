### NAME:JEEVAN VISHAL GD
### REG NO:24900595
### EXPERIMENT:4:FULL ADDER SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

### AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

### EQUIPMENTS REQUIRED:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

### FULL ADDER:

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)


### FULL SUBTRACTOR:
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin


### PROCEDURE:
1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.

### PROGRAM:


### RTL REALIZATION OUTPUT:
![7937d7f7-df38-440c-a2c2-fccd5b7dd02d](https://github.com/user-attachments/assets/178071b1-a90a-487a-a141-c9c5b52b6450)

### TRUTHTABLE:

FULL ADDER:
![834d4f07-5e16-47a5-9a2c-83520b44b601](https://github.com/user-attachments/assets/4fdcd37d-be5c-45ea-b5cc-acd8314791e2)

FULL SUBTRACTOR:
![0ed620d1-4887-4b87-92df-78334f3233b1](https://github.com/user-attachments/assets/080293f5-4905-472c-9394-c0e7142fc51e)


### TIMING DIAGRAM:
![2b0482a1-e91c-47d0-880a-cc94547bed52](https://github.com/user-attachments/assets/efee2742-9f5e-43f2-af72-162167d7296b)

### RESULT:
Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



