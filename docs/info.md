<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Basic Two-Stage CMOS Operational Amplifier (Opamp) with Miller Compensation.

### Specifications

- Vdd = 1.8 V
- Closeloop DC Gain = ~20 dB 
- Bandwidth = 60 MHz
- Output Noise = ~250 uV
- Power Consumption = ~3.6729 mW
- Iref = 100uA

## How to test

Test benches are provided to evaluate the design performance:
- Openloop 
- Closeloop
- Step response

## External hardware

It is required to inject the 100uA externally. This is the current reference of the circuit.
