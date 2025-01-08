## Reg.no: 24901022
## Name: KATHIRESH M
## Experiment 5: IMPLEMENTATION OF JK FLIP FLOP 

*AIM:* 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

*SOFTWARE REQUIRED:*

Quartus prime

*THEORY*

*JK Flip-Flop*

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/a649c30b-232b-4558-b188-fd6c09845180)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/c4360742-e8a8-4937-b089-c46c0433f9a3)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/6c275261-a6d5-4c37-a3a7-1e88ca11c4cd)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

*Procedure*

1. Type the program in Quartus software.
2. Compile and run the program.
3. Generate the RTL schematic and save the logic diagram.
4. Create nodes for inputs and outputs to generate the timing diagram.
5. Generate the timing diagram for different input combinations.


*PROGRAM*

![Screenshot 2025-01-08 114955](https://github.com/user-attachments/assets/869daf47-3a70-4c3e-97e1-0ed866906f5c)




*RTL LOGIC FOR FLIPFLOPS*
![WhatsApp Image 2025-01-08 at 11 47 44_fd2dc855](https://github.com/user-attachments/assets/5f9f59da-b547-4a67-8e66-7f73566bdc3c)



*TIMING DIGRAMS FOR FLIP FLOPS*

![Screenshot 2025-01-08 115115](https://github.com/user-attachments/assets/66a9796d-e396-4b1d-9c8e-d54f5502da85)

*RESULTS*

JK flip flop was implemented using Verilog, and its functionality was validated using functional tables.
