# Design and Implementation of a Reconfigurable FIR Filter on an FPGA

<p align="center">
<b>Group Members:</b> Amogh Ashok, Prashanth Swaminathan, Umang Tekriwal
</p>

<p align="center">
<b>FPGA:</b> Xilinx ZedBoard Zynq 7000 ARM SoC
</p>

**Abstract**
<br>
<br>
FIR filters are among the most commonly used filters in digital signal processing. In this report, the design and implementation of a FIR filter in an FPGA are discussed.
The implementation in question allows updating the values of the FIR coefficients without having to rewrite the bitstream and, consequently, without having to reprogram the FPGA. The output of the FPGA is in agreement with the output of the Python implementation of the same filter, thus proving the goodness of the FPGA implementation. This repository contains the necessary files to implement a low-pass, high-pass, band-pass, and band-stop FIR filters using a FPGA.

We have listed <br>
2 Memory Files - cos256 and sin256<br>
3 Verilog Files - LPF, HPF, and final_filter<br>
1 Bitstream file and 1 associated LTX file - final_filter<br>
1 Verilog ROM file - ROM Song<br>
1 Constraints file - Constraints<br>

Usage or modification of the code for educational or academic purposes is allowed with proper citation to the source.

<h5 align="center">Department of Electrical and Electronics Engineering<br>Birla Institute of Technology and Science, Pilani, Hyderabad Campus (Academic Year: 2025-26)</h5>
