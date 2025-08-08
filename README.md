# Optical_Encoder_Signal_Conditioning_Circuit_Design

Designed and simulated an analog front-end circuit to convert raw optical encoder signals into clean, digital quadrature outputs suitable for microcontroller or FPGA decoding.

The circuit simulates a reflective optical encoder using a photodiode model, amplifies the weak signal with an op-amp, filters out high-frequency noise, and shapes the edges using a Schmitt trigger comparator.

Key features:
Photodiode sensor modelling (time-varying current source)
Op-amp amplifier design (non-inverting gain stage)
Low-pass noise filtering (RC filter tuned for signal bandwidth)
Edge detection with comparator/Schmitt trigger
Optional: Digital signal decoding via Verilog on FPGA

Tools:
LTspice for analog simulation
Verilog & Vivado for FPGA interfacing
GitHub for documentation and waveforms

