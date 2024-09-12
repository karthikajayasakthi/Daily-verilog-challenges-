DEFINITION :

A Ripple Carry Adder (RCA) is a type of digital adder used to add two binary numbers. It consists of a series of full adders, where the carry
output from each full adder is passed as the carry input to the next most significant full adder in the sequence. The process "ripples" the 
carry from the least significant bit (LSB) to the most significant bit (MSB), hence the name.

EPRESSION :

sum = a ^ b ^ cin
carry = (a & b) | (b & cin) | (a & cin)

DIAGRAM :

![image](https://github.com/user-attachments/assets/5898ea45-9aaf-40fa-9ee5-ddb6357c55db)

 
