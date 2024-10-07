# Reed Muller code using VHDL

This repository contains the VHDL implementation of the Reed Muller code, including both the encoder and decoder, as part of my final year B.Tech project. The project is focused on designing, simulating, and performing the hardware implementation of these codes on FPGA boards to enhance error detection and correction in communication systems.

# Project Overview
Reed Muller codes are a class of linear block codes known for their simplicity and effectiveness in error correction. This project involves the design of both the encoder and decoder for Reed Muller codes using VHDL. The final objective is to deploy the design onto FPGA hardware and verify its functionality in real-world applications.

The project is divided into two key tasks:

- **VHDL Implementation**: Development of the Reed Muller code encoder and decoder using VHDL, a hardware description language. The encoder takes input data and transforms it into a codeword that contains additional parity information for error correction. The decoder, on the other hand, takes the received codeword and detects/corrects any errors before reconstructing the original data.

- **Hardware Implementation**: The designed encoder and decoder were synthesized and implemented on FPGA boards. This step ensures that the theoretical designs work in a practical hardware environment, providing real-time error correction capabilities.

# Features
- **Generic Reed Muller Encoder**: The encoder generates Reed Muller codewords based on the input data bits and performs necessary matrix operations for error correction.
- **Generic Reed Muller Decoder**: The decoder reconstructs the original data from the received noisy codeword, correcting errors in the process.
- **FPGA Hardware Implementation**: The design has been tested and validated on FPGA boards, ensuring that it is functional in practical environments.
- **Simulation and Testing**: Extensive simulations were performed to validate the encoder and decoder designs before hardware implementation. The testbenches provided can be used to reproduce these tests.

# Tools & Technologies
- **VHDL**: Hardware description language used for the design of encoder and decoder modules.
- **Intel Quartus**: FPGA design tools used for synthesis, simulation, and hardware implementation.
- **FPGA Boards**: The implementation was tested on FPGA development boards like the DE10-Lite.
