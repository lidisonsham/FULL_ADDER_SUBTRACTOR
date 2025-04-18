### Name : Lidison Sham
### REG NO : 24007744
# EXP NO : 4

# Implementation of Full Adder and Full subtractor circuit

*AIM:*

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

*Equipments Required:*

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

*Full Adder and Full Subtractor*

*Full Adder*

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

*Figure -1 FULL ADDER*

*Full Subtractor*

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

*Truthtable*

FULL ADDER :

![image](https://github.com/user-attachments/assets/abc113e3-2e6a-466f-839a-472dd3cdb69b)

FULL SUBTRACTOR :

![image](https://github.com/user-attachments/assets/4bbf1d4c-ef91-4d65-a51c-6c287a240575)

*Procedure*





Full Adder : 
1.Open Quartus II and create a new project. 
2.Use schematic design entry to draw the full adder circuit. 
3.The circuit consists of XOR, AND, and OR gates.
4.Compile the design, verify its functionality through simulation. 5.Implement the design on the target device and program it.

Full Subtractor : 
1.Follow the same steps as for the full adder. 
2.Draw the full subtractor circuit using schematic design.
3.The circuit includes XOR, AND, OR gates to perform subtraction. 4.Compile, simulate, implement, and program the design similarly to the full adder.



*Program:*

FULL ADDER :

![Screenshot 2024-12-21 210904](https://github.com/user-attachments/assets/a2aa42a8-2954-4bd4-8abe-eea57866ad4c)

FULL SUBTRACTOR :

![Screenshot 2024-12-21 214528](https://github.com/user-attachments/assets/9b86c759-fbff-4bb6-a01a-a5acba83294c)

*RTL Schematic*

###### FULL ADDER

![Screenshot 2024-12-02 202340](https://github.com/user-attachments/assets/240ef848-554b-4489-971c-f9ce77959af5)

###### FULL SUBTRACTOR

![Screenshot 2024-12-02 202448](https://github.com/user-attachments/assets/eb30ca1c-e9a8-4972-abc2-73697f6944e4)


*Output Timing Waveform*

###### FULL ADDER

![Screenshot 2024-12-02 202352](https://github.com/user-attachments/assets/2cae555e-efd5-4415-aecf-f7f9933e0e13)

###### FULL SUBTRACTOR

![Screenshot 2024-12-02 202403](https://github.com/user-attachments/assets/55c09aad-424a-40de-b2f6-617bbf096053)

*Result:*

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.
