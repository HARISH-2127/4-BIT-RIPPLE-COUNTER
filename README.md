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

/* write all the steps invloved */

**PROGRAM**
![Screenshot 2024-12-26 120418](https://github.com/user-attachments/assets/7dcdfc84-2dc0-47c1-b461-1911f08ab583)



/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

 Developed by: RegisterNumber:
*/

**RTL LOGIC FOR 4 Bit Ripple Counter**

![Screenshot 2024-12-26 120245](https://github.com/user-attachments/assets/214f53e4-4bfe-4bb3-a1c0-d4185b9543d6)


**TIMING DIGRAMS FOR 4 Bit Ripple Counter**
![Screenshot 2024-12-26 120311](https://github.com/user-attachments/assets/0e386eb0-e76d-4432-ba01-4a3b1a52b6ce)



**RESULTS**

Thus 4-bit-ripple-counter has been executed successfully
