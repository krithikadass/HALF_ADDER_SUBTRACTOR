# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**


![half adder tt](https://github.com/user-attachments/assets/c6addcea-68e3-4945-a8d1-b83fb6b74c1b)


![half subractor tt](https://github.com/user-attachments/assets/c61d445e-af77-4408-a762-365858683d76)




**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: M.Krithika Lakshmi 
RegisterNumber:24900558



![half adder](https://github.com/user-attachments/assets/04e742a2-e0ee-41db-a8bc-8a1dc4d89a50)



![half subractor](https://github.com/user-attachments/assets/949c4800-ac28-478a-82f7-083ea73d81c9)




**RTL Schematic**


![half adder gate](https://github.com/user-attachments/assets/1f5c267b-837f-4609-b6dc-ae3f33b4304c)


![half subraactor gate](https://github.com/user-attachments/assets/a4e0380b-fd5f-4c17-8489-39b668dd6a16)




**Output/TIMING Waveform**


![half adder wf](https://github.com/user-attachments/assets/c09b28fb-c371-4a7b-ac54-b2f4054fb915)


![half subractor wf](https://github.com/user-attachments/assets/8f19a4bc-83ec-46da-a91c-cfd5b97c9d6b)




**Result:**

Implementation-of-Half-Adder-and-Half Subtractor-circuit is verified
