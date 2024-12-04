# D-FLIPDLOP-NEGEDGE

**AIM:**

To implement  D flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**D Flip-Flop**

D flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, D latch operates with enable signal. That means, the output of D flip-flop is insensitive to the changes in the input, D except for active transition of the clock signal. The circuit diagram of D flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/48c81fe8-bc3f-40e7-95e2-519fc155ad51)

This circuit has single input D and two outputs Qtt & Qtt’. The operation of D flip-flop is similar to D Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of D flip-flop.

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/e5f3fda7-68ec-4a3a-a0a4-cf6f9cc4ab55)

Therefore, D flip-flop always Hold the information, which is available on data input, D of earlier positive transition of clock signal. From the above state table, we can directly write the next state equation as Qt+1t+1 = D

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/8592c0d8-2917-4142-91b9-d6c30dd891d2)

Next state of D flip-flop is always equal to data input, D for every positive transition of the clock signal. Hence, D flip-flops can be used in registers, shift registers and some of the counters.

**Truth Table**

![Screenshot 2024-12-04 181016](https://github.com/user-attachments/assets/fec0c52d-ac6c-4aa4-9b2c-077b25d9fe17)

**Procedure** 
 
 /* 1.Type the program in Quartus software using Verilog to implement the D flip-flop
 with negative edge-triggered clock.
 
 2.Compile and run the program to ensure there are no syntax errors.
 
 3.Generate the RTL schematic and save the logic diagram for documentation.
 
 4.Create nodes for inputs (D, clk) and outputs (Q, Q_bar) in the simulation tool.
 
 5.Simulate the design to generate the timing diagram for different input combinations.
 */
**PROGRAM**

/* Program for flipflops and verify its truth table in quartus using Verilog programming.
Developed by:CH.Dinesh kumar 
RegisterNumber:24000305


![Screenshot 2024-12-04 181815](https://github.com/user-attachments/assets/5da6c74d-69d1-4d42-b911-80684c23a008)


**RTL LOGIC FOR FLIPFLOPS**

![Screenshot 2024-12-04 182416](https://github.com/user-attachments/assets/4a2b5840-1959-4108-aeac-2d0bfafd9124)


**TIMING DIGRAMS FOR FLIP FLOPS**

![Screenshot 2024-12-04 182359](https://github.com/user-attachments/assets/4d5d5371-7502-49d6-9933-7f02fae84048)


**RESULTS Thus the different digital IC's are studied and truth table for different logic gates are verfied
