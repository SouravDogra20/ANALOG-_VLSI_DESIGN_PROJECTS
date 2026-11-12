# Two-Stage CMOS Operational Amplifier Design

## 1. Project Overview

This project focuses on the design, implementation, and simulation of a Two-Stage CMOS Operational Amplifier using Cadence Virtuoso. The design is implemented using the GPDK180 technology library (180 nm CMOS process).

The primary objective is to design and evaluate a two-stage operational amplifier with high voltage gain, adequate bandwidth, stable frequency response, and low power consumption.

The project includes transistor-level circuit design, biasing, frequency response analysis, transient response, stability evaluation, CMRR, noise, and power analysis.

## 2. Technology and Design Specifications

| Parameter | Specification |
|---|---|
| Circuit | Two-Stage CMOS Op-Amp |
| Technology Node | 180 nm |
| Technology Library | GPDK180 |
| Design Tool | Cadence Virtuoso IC6.1.8 |
| Simulator | Spectre |
| Supply Voltage | 1.8 V |
| Load Capacitance | 2 pF |
| Compensation | Miller Compensation |

## 3. Circuit Architecture

The operational amplifier consists of:

- Differential input stage using NMOS transistors.
- PMOS active load and current mirror.
- Bias current generation circuit.
- Second gain stage.
- Miller compensation capacitor.
- Output stage.

The differential input stage amplifies the difference between the two input signals, while the second stage provides additional voltage gain. Frequency compensation is used to improve closed-loop stability.

## 4. Simulation and Analysis

### 4.1 Schematic Design
Transistor-level implementation of the two-stage CMOS operational amplifier using Cadence Virtuoso and GPDK180 technology.

### 4.2 DC Operating Point Analysis
Evaluation of transistor operating regions, bias currents, node voltages, and MOSFET operating conditions.

### 4.3 AC Analysis
Evaluation of:
- Open-loop voltage gain.
- Frequency response.
- Gain-bandwidth characteristics.
- Unity-gain frequency.

### 4.4 Transient Analysis
Time-domain simulation to evaluate the amplifier's response to applied input signals.

### 4.5 Stability Analysis
Evaluation of feedback-loop stability using Spectre Stability Analysis.

Measured simulation results:
- Phase Margin: 65.3649°
- Phase Margin Frequency: 21.3537 MHz
- Gain Margin: 17.3348 dB
- Gain Margin Frequency: 99.9843 MHz

### 4.6 CMRR Analysis
Common-Mode Rejection Ratio evaluation using differential-mode and common-mode gain measurements.

### 4.7 Noise Analysis
Evaluation of amplifier noise performance and frequency-dependent noise response.

### 4.8 Power Analysis
Evaluation of power consumption and supply-related power dissipation.

### 4.9 Slew Rate Analysis
Evaluation of the maximum output voltage transition rate during large-signal operation.

## 5. Design Objectives

- Achieve high open-loop voltage gain.
- Maintain adequate gain-bandwidth product.
- Achieve a phase margin close to 60°.
- Improve common-mode rejection.
- Minimize power consumption.
- Evaluate noise and transient performance.
- Maintain stable operation under capacitive loading.

## 6. Software and Tools

- Cadence Virtuoso IC6.1.8
- Spectre Circuit Simulator
- GPDK180 Technology Library

## 7. Repository Contents

- Circuit schematic
- Design calculations
- DC operating point results
- AC frequency response
- Transient simulation waveforms
- Stability analysis
- CMRR analysis
- Noise analysis
- Power analysis
- Slew rate evaluation

## 8. Author

Sourav Kumar Dogra

Electronics and Communication Engineering

**Project Domain:** Analog VLSI Design and CMOS Analog Circuit Design
