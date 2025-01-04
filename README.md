# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**

 Type the program in Quartus software.

Compile and run the program.

Generate the RTL schematic and save the logic diagram.

Create nodes for inputs and outputs to generate the timing diagram.

For different input combinations generate the timing diagram PROGRAM

**PROGRAM**

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

 Developed by:omkar varma s RegisterNumber: 24008163
*/
![398009923-2d14edfc-0b23-4cf2-9061-3134284514fc](https://github.com/user-attachments/assets/a5013810-32cc-4bca-85e3-f617f0d815a2)


**RTL LOGIC FOR 4 Bit Ripple Counter**
![398009948-7ce57db5-0e7e-496b-af57-cfed3ee449f4](https://github.com/user-attachments/assets/8da56685-49b5-4265-9eba-bbca310b1ff7)

**TIMING DIGRAMS FOR 4 Bit Ripple Counter**
![398009954-e198cf4b-8ff3-4a1a-aff2-d8eeb8d59b05](https://github.com/user-attachments/assets/f0868c92-13dc-4cd2-a7aa-0013f27d84c3)

**RESULTS**
To implement 4 Bit Ripple Counter using verilog and validating their functionality using their functional tables is verified.
