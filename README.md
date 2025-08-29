<img width="2354" height="180" alt="image" src="https://github.com/user-attachments/assets/fe9d2ba2-c3cc-4e1c-8893-0cbe10fbd344" />## Delay-Locked-Loop

# Abstract
This project focuses on the design and implementation of a Delay Locked Loop (DLL), a crucial component in modern digital communication and high-speed integrated circuits. Delay-Locked Loops (DLLs) are negative feedback circuits that achieve phase alignment of an output signal to an input reference signal ensuring robust synchronization in systems such as clock distribution networks and clock-data recovery circuits without requiring an oscillator.

# Introduction
A Delay-Locked Loop(DLL) is a negative-feedback based circuit whose function is to synchronize the phase of two signals, which includes an input reference clock and the DLL output signal. In this project, we have implemented an all-digital DLL. The operation of a DLL relies on several critical components: the Phase Frequency Detector (PFD), the Up-Down Counter and the Delay Line, each playing a vital role in accurately receiving and sampling signals to achieve effective phase lock, even at certain high frequencies.

# Objectives
- To design and implement a Delay-Locked Loop and simulate it on Cadence Virtuoso and verify its functionality.

- To analyze the locked phase difference and determine its lock-in time using the defined specifications.

# Motivation
To explore the basic design of Delay-Locked Loop, which has applications in generating multiple phases of clock signals, to enhance the clock rise-to-data output valid timing characteristics of integrated circuits and in clock and data recovery (CDR) in SerDes.

# Tools Used
- Cadence Virtuoso Design Environment
- UMC 65nm PDK Technology node
- XCircuit

# Specifications
# Counter-type DLL

- UMC 65nm PDK
  
- Supply Voltage = 1.8V

- Steady state current consumption = 6.909mA
  
- Power consumption = 12.438mW

- Fmax = 2GHz

- Total no. of MOSFETs = 950

- Min. delay per stage = 13.26ps

- Max. delay due to delay line = 411ps

# Successive Approximation Register type DLL

- UMC 65nm PDK
  
- Supply Voltage = 1.8V

- Steady state current consumption = 5.947mA

  
- Power consumption = 10.703 mW

- Fmax = 2GHz

- Total no. of MOSFETs = 1197

- Min. delay per stage = 13.26ps

- Max. delay due to delay line = 411ps














