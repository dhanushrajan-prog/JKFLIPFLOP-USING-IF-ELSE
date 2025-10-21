# JKFLIPFLOP-USING-IF-ELSE

**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**JK Flip-Flop**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/a649c30b-232b-4558-b188-fd6c09845180)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/c4360742-e8a8-4937-b089-c46c0433f9a3)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/6c275261-a6d5-4c37-a3a7-1e88ca11c4cd)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

**Procedure**

/* write all the steps invloved */

**PROGRAM**
![Screenshot_2025-10-21-17-48-12-22_40deb401b9ffe8e1df2f1cc5ba480b12](https://github.com/user-attachments/assets/a4ea0ba0-f741-4580-9cb0-96feb9e7540c)

/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL LOGIC FOR FLIPFLOPS**
![Screenshot_2025-10-21-17-48-29-73_40deb401b9ffe8e1df2f1cc5ba480b12](https://github.com/user-attachments/assets/5a2d15fb-7fd4-420d-8bc9-086cd6dcc678)

**TIMING DIGRAMS FOR FLIP FLOPS**
![Screenshot_2025-10-21-17-48-44-38_40deb401b9ffe8e1df2f1cc5ba480b12](https://github.com/user-attachments/assets/fda25204-ee99-4eca-9193-6a7a2c8b7e77)

**RESULTS**
Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.
