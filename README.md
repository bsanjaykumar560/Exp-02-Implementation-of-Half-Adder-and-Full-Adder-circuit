# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:

HALF ADDER:



![Exp3 ha code](https://github.com/bsanjaykumar560/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145954153/ac5e2479-677d-4c54-9e93-a9d4baf0853e)


FULL HADDER:



![Exp3 fa code](https://github.com/bsanjaykumar560/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145954153/37419597-92be-47d6-ac58-b98f609c2060)


OUTPUT:



/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: B.SANJAY KUMAR
RegisterNumber:  23004077



### RTL



HALF ADDER:


![Exp3 ha RTL diagram](https://github.com/bsanjaykumar560/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145954153/ca588c59-4d39-4834-9317-6b5855cb8ceb)



FULL ADDER:



![Exp3 fa RTL diagram](https://github.com/bsanjaykumar560/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145954153/36d38722-cb42-4c15-be95-67a742bf8dc5)




### TIMING DIAGRAM


HALF ADDER:


![exp3 ha wave](https://github.com/bsanjaykumar560/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145954153/817ecc6a-fd08-4a8f-b958-116963de1a15)



FULL ADDER:


![exp3 ha wave](https://github.com/bsanjaykumar560/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145954153/12d4a318-b26a-458d-9c17-04ace22a1887)





### TRUTH TABLE 
HALF ADDAER:


![Exp3 truthtable (ha)](https://github.com/bsanjaykumar560/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145954153/38171564-456c-4090-a7a0-1f1a1a24f987)

FULL HADDER:



![Exp3 truthtable (fa)](https://github.com/bsanjaykumar560/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145954153/f9dff54e-cb75-4db8-b6ed-635d969ccd9d)


### Result:
