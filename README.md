# NAME : SHREYESHKAR SEKAR
# REFERENCE NUMBER :24900622

# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional table.

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

/* Program for flipflops and verify its truth table in quartus using Verilog programming.*/


![WhatsApp Image 2024-12-09 at 4 07 50 PM](https://github.com/user-attachments/assets/cb9e08e4-00d6-4fa1-b730-d45e9a945460)


**RTL LOGIC FOR SISO Shift Register**

![WhatsApp Image 2024-12-09 at 4 07 26 PM](https://github.com/user-attachments/assets/c7aeb952-c76c-489f-8af0-802181745f3a)



**TIMING DIGRAMS FOR SISO Shift Register**


![WhatsApp Image 2024-12-09 at 4 07 13 PM](https://github.com/user-attachments/assets/62dc2015-a79e-41bd-be89-c926e2552fbb)


**RESULTS**

SISO Shift Register implemented using verilog and validated their functionality using their functional table.

