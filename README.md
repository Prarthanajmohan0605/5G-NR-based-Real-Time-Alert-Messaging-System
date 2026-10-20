5G NR Based Real-Time Alert Messaging System

A MATLAB-based simulation of an emergency alert messaging system inspired by 5G New Radio (NR) communication techniques.

Overview

The project explores the transmission and reception of emergency alert messages over a simulated wireless communication channel. It demonstrates how digital modulation and Orthogonal Frequency Division Multiplexing (OFDM) can be used to transmit information and recover the original message at the receiver.

An example emergency message used in the simulation is:

"Earthquake Detected - Evacuate!"

The system models the transmission process, introduces Additive White Gaussian Noise (AWGN), and evaluates communication performance through signal visualizations and Bit Error Rate (BER) analysis.

The project also explores MIMO-OFDM using the Alamouti scheme and a simplified OTFS comparison to study different wireless communication approaches.

Objectives

- Develop a MATLAB simulation for emergency alert message transmission.
- Implement OFDM-based digital communication.
- Explore 16-QAM modulation for downlink transmission and QPSK modulation for uplink acknowledgment.
- Simulate wireless channel noise using AWGN.
- Recover transmitted messages at the receiver.
- Analyze signal characteristics using constellation diagrams and waveform plots.
- Evaluate BER performance for MIMO-OFDM communication.
- Explore a simplified OTFS-based comparison.
- Develop a MATLAB GUI with adjustable SNR for interactive simulation.

System Architecture

The simulation follows a transmitter-channel-receiver architecture.

1. Message Generation: An emergency alert message is converted into a binary bitstream.
2. Digital Modulation: The bitstream is mapped to modulation symbols using 16-QAM for downlink transmission and QPSK for uplink acknowledgment.
3. OFDM Transmission: The modulated symbols are processed using an inverse Fast Fourier Transform (IFFT), and a cyclic prefix is added.
4. Channel Simulation: AWGN is introduced to simulate noise in the communication channel.
5. OFDM Reception: The receiver removes the cyclic prefix and applies the Fast Fourier Transform (FFT).
6. Demodulation: The received symbols are demodulated to recover the transmitted bits.
7. Message Recovery: The recovered bitstream is converted back into the original message.

Key Features

1. Emergency Alert Messaging

Simulates the transmission and recovery of emergency alert messages over a wireless communication channel.

2. OFDM-Based Communication

Uses OFDM modulation with configurable simulation parameters.

- FFT size: 64
- Cyclic prefix length: 16

3. Digital Modulation

Explores two digital modulation schemes:

- 16-QAM: Used for the simulated downlink alert transmission.
- QPSK: Used for the simulated uplink acknowledgment.

4. AWGN Channel Simulation

Introduces additive white Gaussian noise to investigate the effect of channel noise on received signals and message recovery.

5. Signal Visualization

The simulation includes visualizations such as:

- IFFT output waveform
- Cyclic-prefix waveform
- Ideal and received constellation diagrams
- Received signal samples

6. MIMO-OFDM and BER Analysis

Explores a 2×2 Alamouti MIMO-OFDM simulation and evaluates Bit Error Rate (BER) performance under different SNR conditions.

7. Simplified OTFS Comparison

Includes a simplified OTFS simulation for exploring an alternative modulation approach used in wireless communication research.

8. MATLAB GUI

Provides an interactive interface with adjustable SNR settings to explore communication performance under different noise conditions.

Simulation Parameters

Parameter| Value
Simulation environment| MATLAB
OFDM FFT size| 64
Cyclic prefix length| 16
Downlink modulation| 16-QAM
Uplink modulation| QPSK
Channel model| AWGN
MIMO configuration| 2×2 Alamouti MIMO-OFDM
SNR example| 20 dB

Technologies and Concepts

- MATLAB
- 5G NR-inspired wireless communication
- Orthogonal Frequency Division Multiplexing (OFDM)
- 16-QAM and QPSK modulation
- IFFT and FFT processing
- AWGN channel modeling
- MIMO-OFDM
- Alamouti space-time block coding
- Bit Error Rate (BER) analysis
- Simplified OTFS comparison
- MATLAB GUI development



Scope and Limitations

This project is a MATLAB simulation inspired by selected 5G NR communication concepts. It is not a complete implementation of the standardized 5G NR physical layer, and it does not demonstrate deployment on a live cellular network.

The simulation uses simplified channel and signal-processing models for educational exploration. Performance depends on the selected parameters and implementation.

Future Scope

- Incorporate more realistic wireless channel models.
- Extend the simulation to include additional 5G NR physical-layer procedures.
- Compare BER performance across modulation schemes.
- Explore the impact of channel conditions on emergency message recovery.
- Extend the GUI to support additional simulation parameters.
- Investigate latency and reliability requirements for emergency communication.



Prarthana J Mohan

Electronics and Communication Engineering

Project area : Wireless Communications, Digital Signal Processing, Communication Systems, and VLSI Design.
