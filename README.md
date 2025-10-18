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

![image](https://github.com/user-attachments/assets/3b1c3a82-75cd-4045-88fb-29f775b45520)


Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/user-attachments/assets/7cb43259-2411-4424-ba2e-d194969667bc)


Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

![halfadder prog](https://github.com/user-attachments/assets/6c726225-ae01-455d-acc2-df86392b77d6)

![halfsubtractor prog](https://github.com/user-attachments/assets/2e626b3c-918c-4073-8150-5877fc4ebc55)



###Name:RAHA PRIYA DHARSHINI M
###RegisterNumber:24901069

**RTL Schematic**
![halfadder rtl](https://github.com/user-attachments/assets/a0e5a0d2-3d3c-4fc7-9426-cb8d2a6c233d)

![half subtractor rtl](https://github.com/user-attachments/assets/82072b8f-a72a-466e-a114-c0d8c3c2818a)

**Output/TIMING Waveform**
![waveform halfadder](https://github.com/user-attachments/assets/1c118fb8-4b45-4e28-8a20-06b58dc64656)

![halfsub waveform](https://github.com/user-attachments/assets/5d04dd38-dc59-4653-a68b-bcb0800a828b)


**Result:**
Thus a half adder and a full adder circuit is designed and its  truth table is verified in Quartus using Verilog programming.
