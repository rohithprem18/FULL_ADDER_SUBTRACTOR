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

## Truthtable:

**Full adder:**

![TRUTH table of full adder](https://github.com/rohithprem18/FULL_ADDER_SUBTRACTOR/assets/146315115/bde38b0d-8e08-40aa-b1a8-a7278f412b17)

**Full Subtractor:**

![truth table of full subtractor](https://github.com/rohithprem18/FULL_ADDER_SUBTRACTOR/assets/146315115/dfab5eca-9468-4a29-927b-b731b6ccf590)



**Procedure**

STEP 1: Use module project name(input,output) to start the Verilog programmming.
STEP 2: Assign inputs and outputs using the word input and output respectively.
STEP 3: Use defined keywords like wire,assign and required logic gates to represent the boolean
expression.
STEP 4: Use each output to represnt onre for differnce and the other for borrow.
STEP 5: End the verilog program using keyword endmodule.

**Program:**
```
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
 Developed by:ROHITH PREM S RegisterNumber:212223040172
```
**Full Adder:**

![FULLadder](https://github.com/rohithprem18/FULL_ADDER_SUBTRACTOR/assets/146315115/fb8f195a-0e3e-45be-9748-0e08609a9a9d)

**Full Subtractor**

![code](https://github.com/rohithprem18/FULL_ADDER_SUBTRACTOR/assets/146315115/381abb74-c5d8-413e-9448-8a606a22e2da)

**RTL Schematic**

**Full Adder:**

![fulladder rtl](https://github.com/rohithprem18/FULL_ADDER_SUBTRACTOR/assets/146315115/61a86b98-9cb7-4fdc-8a20-d49748543e71)

**Full Subtractor**

![rtl_subs](https://github.com/rohithprem18/FULL_ADDER_SUBTRACTOR/assets/146315115/a107911d-fc97-4c79-b259-6b03a0eeb5c4)

**Output Timing Waveform**

**Full Adder:**

![fulladder](https://github.com/rohithprem18/FULL_ADDER_SUBTRACTOR/assets/146315115/84392dc4-b546-4552-80d2-be43f87ce199)


**Full Subtractor**

![timing](https://github.com/rohithprem18/FULL_ADDER_SUBTRACTOR/assets/146315115/4e1fd63a-d0b4-4679-84ca-da3c7d3875f1)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



