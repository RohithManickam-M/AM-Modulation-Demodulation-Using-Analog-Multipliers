# Amplitude Modulation and Demodulation Using Analog Multipliers

## Overview

This project implements an Amplitude Modulation (AM) and Demodulation system using Analog Multipliers. The objective is to generate an AM signal, recover the original message signal through coherent detection, and analyze the advantages of multiplier-based demodulation over conventional envelope detectors.

## Objectives

* Design an AM modulation circuit using analog multipliers.
* Implement coherent demodulation using product detection.
* Recover the original message signal using a low-pass filter.
* Compare performance with traditional envelope detector circuits.

## Working Principle

### Modulation

The message signal is multiplied with a carrier signal using an analog multiplier. A carrier component is added to generate the final AM waveform.

### Demodulation

The received AM signal is multiplied with a synchronized carrier signal. The resulting output contains both low-frequency and high-frequency components. A low-pass filter removes the high-frequency component and recovers the original message signal.

## Components Used

* BJT Differential Amplifiers
* Operational Amplifiers
* Analog Multiplier Circuit
* Low-Pass Filter
* Signal Generator
* Oscilloscope

## Results

* Successfully generated amplitude-modulated signals.
* Recovered the original message signal using coherent detection.
* Achieved lower distortion compared to conventional envelope detector methods.
* Demonstrated practical applications of analog multipliers in communication systems.

## Applications

* RF Communication Systems
* Frequency Mixers
* Phase-Locked Loops (PLLs)
* True RMS Measurement
* Power Measurement Systems

## Future Improvements

* Implement a Gilbert Cell based multiplier.
* Improve bandwidth and linearity.
* Reduce noise and distortion.
* Integrate precision multiplier ICs such as AD534 or AD633.

## Technologies

Analog Electronics, Communication Systems, Operational Amplifiers, Differential Amplifiers, Analog Multipliers, Signal Processing

