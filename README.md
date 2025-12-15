# ripple_counter
AIM:

To implement 4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

SOFTWARE REQUIRED:

Quartus prime

THEORY

4 Bit Ripple Counter

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

<img width="715" height="395" alt="Screenshot 2025-12-15 180545" src="https://github.com/user-attachments/assets/885afda6-de32-49e7-9d80-16c73dc13e67" />



In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

<img width="530" height="617" alt="Screenshot 2025-12-15 180558" src="https://github.com/user-attachments/assets/65dcdc6e-2c40-4d74-b91c-3b8eacc0fd3b" />


Procedure

/* write all the steps invloved */

PROGRAM

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

Developed by:YUVASREE S
RegisterNumber:25014102 */

RTL LOGIC FOR 4 Bit Ripple Counter

TIMING DIGRAMS FOR 4 Bit Ripple Counter

RESULTS:
Thus the 4 Bit Ripple Counter using verilog and validating their functionality using their functional tables is verified.
