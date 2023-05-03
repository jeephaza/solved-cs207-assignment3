Download Link: https://assignmentchef.com/product/solved-cs207-assignment3
<br>
Provide answers to the following questions:

<ol>

 <li>Draw the multiple-level nor circuit for the following expression:</li>

</ol>

F = AB(D + C) + (BC’ + DE’) + BD’

<ol start="2">

 <li>Implement the following Boolean function F, using the two-level forms of logic (a) AND-OR, (b) OR-NAND, (c) NOR-OR, (d) NAND-NAND, (e) OR-AND, (f) NOR-NOR, and (g) NAND-AND:</li>

</ol>

F(A, B, C, D) = ∑ (1, 4, 5, 8, 9, 10, 11, 13, 15)

Please note that you only need to write the logic equation, no drawing needed

<ol start="3">

 <li>Derive the circuits for a four-bit parity generator and three-bit parity checker using an odd parity bit. Write the truth table, simplify your logic equation and draw circuit diagram.</li>

 <li>Design a combinational circuit with three inputs, x , y , and z , and three outputs, A, B , and C. When the binary input is 3, 4, 5, 6, or 7, the binary output is one less than the input. When the binary input is 0, 1, or 2, the binary output is two greater than the input. Write the logic formula and draw circuit diagram.</li>

 <li>An ABCD-to-seven-segment decoder is a combinational circuit that converts a decimal digit in BCD to an appropriate code for the selection of segments in an indicator used to display the decimal digit in a familiar form. The seven outputs of the decoder (a, b, c, d, e, f, g) select the corresponding segments in the display, as shown in figure (a). The numeric display chosen to represent the decimal digit is shown in (b). Using a truth table and/or Karnaugh maps, design the BCD-to-seven-segment decoder using a minimum number of gates. All the invalid input should display nothing.</li>

</ol>




Hint: You may use 74LS138 decoder

<ol start="6">

 <li>For a binary multiplier that multiplies two unsigned four-bit numbers : Using AND gates and binary adders, design the circuit. Briefly describe your design and list the logic formulas. Draw the circuit diagram. For adders, you can just use a block diagram with ports to represent them.</li>

 <li>Implement the following Boolean function with a multiplexer.

  <ol>

   <li>F(A, B, C, D) =∑ (0, 2, 5, 8, 10, 14)</li>

   <li>F(A, B, C, D) = ∏(2, 6, 11)</li>

  </ol></li>

 <li>Implement a full subtractor with two 4×1 multiplexers. Write down your process.</li>

 <li>An 8×1 multiplexer has inputs A, B, and C connected to the selection inputs</li>

</ol>

S0, S1, and S2, respectively. The data inputs I0 through I7 are as follows:

I<strong>0 </strong>= I2 = 1; I4 = I7 = 0; I3 = I5 = D’; I1 = I6 = D. Determine the Boolean function that the multiplexer implements. Write your process.

PART 2: DIGITAL DESIGN LAB

<h1>INTRODUCTION</h1>

In this lab, you are required to use Vivado 2017.4 and Minisys/EGO1 Practice platform (xilinx FPGA chip artix 7 inside) to design a combinational logic circuit and test it.

<h1>PREAMBLE</h1>

Before working on the coursework itself, you should master the following material.

1.’CH3-Minimisation-SUSTC-new.ppt’ and ‘CH4-COMBINATIONAL LOGiC-new.ppt’ in Sakai site.

<ol start="2">

 <li>‘Digital design lab8’, ‘Digital design lab9’ in Sakai site.</li>

 <li>Verilog: http://www.verilog.com</li>

</ol>

<h1>EXERCISE SPECIFICATION</h1>

<strong>TASK1:  </strong>

Implement a full subtractor (described on question 8 of Part 1 in this document) with two 4×1 multiplexer. Write a circuit to realize this function and test.

<ul>

 <li>Do the design.</li>

 <li>Write testbench to verify the function of your design.</li>

 <li>Create the constraint file.</li>

 <li>Do the synthetic and implementation, generate the bitstream file and program the device, then test on the Minisys / EGO1 develop board.</li>

</ul>




<strong>TASK2:  </strong>

I Implement an ABCD-to-seven-segment decoder (described on question 5 of Part 1 in this document) with decoders and gates.

<ul>

 <li>Do the design.</li>

 <li>Write testbench to verify the function of your design.</li>

 <li>Create the constraint file</li>

 <li>Do the synthetic and implementation, generate the bitstream file and program the device, then test on Minisys /EGO1 the develop board</li>

</ul>