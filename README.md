# EX NO:9
<P align='center'> <b>T-FLIPFLOP-POSEDGE</b>

**DATE:**

**AIM:**

To implement  T flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**T Flip-Flop**

T flip-flop is the simplified version of JK flip-flop. It is obtained by connecting the same input ‘T’ to both inputs of JK flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of T flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/T-FLIPFLOP-POSEDGE/assets/154305477/458a68fe-2d08-4a9d-ac4f-7ae0480ce0bd)

 
This circuit has single input T and two outputs Qtt & Qtt’. The operation of T flip-flop is same as that of JK flip-flop. Here, we considered the inputs of JK flip-flop as J = T and K = T in order to utilize the modified JK flip-flop for 2 combinations of inputs. So, we eliminated the other two combinations of J & K, for which those two values are complement to each other in T flip-flop. The following table shows the state table of T flip-flop.

Here, Qtt & Qt+1t+1 are present state & next state respectively. So, T flip-flop can be used for one of these two functions such as Hold, & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of T flip-flop. Inputs Present State Next State

![image](https://github.com/naavaneetha/T-FLIPFLOP-POSEDGE/assets/154305477/cdd7fb32-539f-4b66-bb8d-f305a153c886)

 
From the above characteristic table, we can directly write the next state equation as Q(t+1)=T′Q(t)+TQ(t)′ ⇒Q(t+1)=T⊕Q(t)

**Procedure**
```
Step 1: Open Quartus II in your laptop.

Step 2: Write code to implement SR flipflop using verilog and validating their functionality using their functional tables.

Step 3: Run compilation to check for errors.

Step 4: Open waveform output and load input values.

Step 5: Run simulation to get the output.

Step 6: Open in RTL viewers to get RTL diagram output.

```
**Program for flipflops and verify its truth table in quartus using Verilog programming.**

**Developed by:VISVANTH PS**

**RegisterNumber:212223050061*

**PROGRAM**

![Screenshot 2024-05-07 102256](https://github.com/karuniya2005/T-FLIPFLOP-POSEDGE/assets/161425769/b0ed5ca7-b9c6-487a-8d57-c73268fda691)

**RTL LOGIC FOR FLIPFLOPS**

![Screenshot 2024-05-07 102317](https://github.com/karuniya2005/T-FLIPFLOP-POSEDGE/assets/161425769/36ff37e0-1023-4ffa-962e-a2a104917b27)

**TIMING DIGRAMS FOR FLIP FLOPS**

![Screenshot 2024-05-07 102751](https://github.com/karuniya2005/T-FLIPFLOP-POSEDGE/assets/161425769/9be6aec6-b3f6-40b3-9e0c-956f3b34615c)

**RESULTS**

Hence, T flipflop using verilog and validating their functionality using their functional tables is implemented.
