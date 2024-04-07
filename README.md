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
### FULL ADDER
![image](https://github.com/Narasimhan05/FULL_ADDER_SUBTRACTOR/assets/132819871/d2809c66-6ede-4f5b-9200-f18cf9f44a93)

### FULL SUBSTRACTER
![image](https://github.com/Narasimhan05/FULL_ADDER_SUBTRACTOR/assets/132819871/b5eb7816-2ee2-40d0-b9c1-662834d48b58)

**Procedure**
```
STEP 1: Use module project name(input,output) to start the Verilog programmming.
  STEP 2: Assign inputs and outputs using the word input and output respectively. 
  STEP 3: Use defined keywords like wire,assign and required logic gates to represent the boolean expression. 
  STEP 4: Use each output to represnt onre for differnce and the other for borrow. STEP 5: End the verilog program using keyword endmodule.
```
**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
### FULL ADDER;
![image](https://github.com/Narasimhan05/FULL_ADDER_SUBTRACTOR/assets/132819871/1ea09d35-6de4-4bda-ba25-41ebe1f3ecc7)

### FULL SUBSTRACTER:
![image](https://github.com/Narasimhan05/FULL_ADDER_SUBTRACTOR/assets/132819871/201f125a-2070-4e2f-a7ae-f5774003f99d)

Developed by: NARASIMHAN S
RegisterNumber: 212223230133
*/

## RTL Schematic;
![image](https://github.com/Narasimhan05/FULL_ADDER_SUBTRACTOR/assets/132819871/9bd4ea0d-c56e-4c57-9a74-f7883c29caee)

## Output Timing Waveform:
![image](https://github.com/Narasimhan05/FULL_ADDER_SUBTRACTOR/assets/132819871/2bf62fe0-6147-4d96-88db-416de95f742f)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



