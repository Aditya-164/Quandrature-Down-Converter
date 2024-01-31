# Quandrature-Down-Converter
## Authors:
- Aditya Raj Singh (2022102067)
- Prakhar Raj (2022102066)

## Institution:
International Institute of Information Technology, Hyderabad

## Project Overview
This repository contains documentation and findings of the Quadrature Down Converter (QDC) project undertaken as part of the Analog Electronic Circuits (EC2.103) course at IIIT Hyderabad. The QDC is crucial in modern communication systems for converting high-frequency signals to lower frequencies, enhancing efficiency in processing and transmission.

## Project Structure
- **Introduction:**
  - Overview of Frequency-down converters and the role of mixers.
  - Down conversion equations and challenges.
- **Quadrature Oscillator Design:** Detailed discussion on designing a quadrature oscillator using opamps. This oscillator generates two sinusoidal signals with a 90° phase difference at 100 kHz. The section covers topology, calculations for component values, LTSpice simulations, and real-world implementation in the lab with observations.
- **Switch (Mixer) Design:** Exploration of a simple MOSFET-based mixer design. The mixer takes oscillator signals as inputs and produces intermediate frequency (IF) outputs. The section includes LTSpice simulations for various input frequencies and real-world experiments with corresponding component values.
- **Low Pass Filter Design:** Introduction to low pass filters (LPF) and the design of an RC LPF with a -3 dB cut-off frequency of 2 kHz. The section covers calculations for component values, LTSpice simulations for frequency and transient response, and practical implementation in the lab with measurement results.
- **Complete Circuit Prototype Design:** Integration of all building blocks (oscillator, mixer, and LPF) to create the complete Quadrature Down Converter circuit. Transient simulations, FFT plots, and experimental results from the lab are presented, along with a comparison table for simulation and measurement outcomes. (Refer to Project Report)

## How to Use this Repository
1. Navigate to each section's folder for detailed documentation and results.
2. Access the project report PDF for a comprehensive overview of the entire project.

## Note:
- Follow instructions in the project report for LTSpice simulations and lab experiments.
- Ensure correct LTSpice setup using provided model files (TSMC 180nm.txt and UA741.301).

## Acknowledgments
- Gratitude to IIIT Hyderabad for resources and support.
- Special thanks to Prof. Abhishek Srivastava and teaching assistants.

## References
- [1] Design of Analog CMOS integrated Circuits by Behzad Razavi Chapter 2 and Chapter 4. 
- [2] Rahsoft.com - understanding quadrature down conversion. 
- [3] Babak Bastani, Edwin E Bautisa, Geetha Nagaraj and Joe Heck, “A Quadrature Down Converter 
For Direct Conversion Receivers with High 2nd and 3rd Order Intercept” IEEE. 
- [4] Electricaltechnology.org – passive low pass filters. 
- [5] Microelectronic Circuits by Adel S. Sedra, Kenneth C. Smith, Chapter 2 and Chapter 14. 
- [6] Ron Mancini, “Design of op amp Sine Wave Oscillator”. Ralph Holzel, “A Simple Wde-Band Sine Wave Quadrature Oscillator” IEEE Transactions on Instrumentation and Measurement, vol. 42, pp.3, June 1993. 

**Thank You!**
