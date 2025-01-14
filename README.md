# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.


**PROGRAM**
![WhatsApp Image 2024-12-15 at 10 01 40_9a5614c3](https://github.com/user-attachments/assets/183abde4-e577-4d5c-80ad-4105e3ec1473)


Developed by: A Chandhna
RegisterNumber:24900265

*/

**RTL LOGIC FOR SISO Shift Register**

![10 rtl](https://github.com/user-attachments/assets/e33fe39b-fe9b-444a-a41d-e7defbafda5b)



**TIMING DIGRAMS FOR SISO Shift Register**


![10 td](https://github.com/user-attachments/assets/3e12866e-86d3-4428-b325-649778defe77)



**RESULTS**
Hence a serial in serial out shift register is implemented successfully.
