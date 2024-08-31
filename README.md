Binary Adder
This provides an analysis and evaluation of the functionality of a 2-bit binary adder that generates a 3-bit output including a carry-out bit using basic digital logic gates. 
The task requires us to construct a digital circuit capable of adding two 2-bit binary number and generating a 3-bit output, the design utilizes two half adders and OR gates.
The process, the first half adder, which sums the LSB (A0 AND B0), and produces both a sum (S0) and a carry (C0). The second half adder then steps in to handle the more complex task of adding the MSB (A1 AND B1) 
alongside the carry from the first half adder, resulting in a second sum(s1) and another carry(c0)
To finalize the operation, the OR gate combines the carry outputs from both half adders (c0 and c1) to deliver the final carry out.
This methodical ensures that the circuit accurately computes the bunary sum, with S0,S1, and carry out forming the complete 3 bit result. For example, when adding the binary numbers A=11 and B=10, the circuit correctly produces 
an output 101, confirming its effectiveness in handling the addition.


YOUTUBE: https://www.youtube.com/watch?v=mex91usG8Ak

