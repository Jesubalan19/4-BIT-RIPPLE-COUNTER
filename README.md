### EX-12 <p align="center"><b>4-BIT-RIPPLE-COUNTER</b>

## NAME: Jesubalan A
## REG NO: 212223240060

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

1.	Type the program in Quartus software.
2.	Compile and run the program.
3.	Generate the RTL schematic and save the logic diagram.
4.	Create nodes for inputs and outputs to generate the timing diagram.
5.	For different input combinations generate the timing diagram.


**PROGRAM**

![330798396-49fcd884-f660-4977-b4d0-ccc55531c07c](https://github.com/Aditaayan/4-BIT-RIPPLE-COUNTER/assets/147473394/0f531252-4f28-464b-bb73-023b5d5ca011)


**RTL LOGIC FOR 4 Bit Ripple Counter**

![330798479-28d220b5-ca1d-4480-809b-780cd6a2badb](https://github.com/Aditaayan/4-BIT-RIPPLE-COUNTER/assets/147473394/fe44861a-e451-4a5a-a7a5-8796cdcfaaf3)


**TIMING DIGRAMS FOR 4 Bit Ripple Counter**

![330798547-5a83e6c5-8098-40cd-8b37-3893bf3e6bdd](https://github.com/Aditaayan/4-BIT-RIPPLE-COUNTER/assets/147473394/ebb9cf55-4083-4ae0-aaec-48ff8ec565d9)


**RESULTS**

The 4-bit ripple counter implemented in Verilog has been successfully completed. Its functionality has been validated through simulation and comparison with the expected values from the functional tables

