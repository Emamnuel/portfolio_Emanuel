# Full Bridge Inverter

## Objective

Design and validation of a full bridge inverter for AC output generation.

---

## Hardware

Main components:

- STM32 microcontroller
- MOSFET full bridge
- Gate driver
- LC output filter

### PCB

![PCB](../images/inverter/pcb.jpg)

---

## Firmware

Implemented features:

- PWM generation
- dead-time insertion
- protection routines
- startup sequence

---

## Test Setup

Bench setup used for validation.

![Test setup](../images/inverter/testbench.jpg)

---

## Results

Measured results:

- Output voltage: 220 Vrms
- Switching frequency: 20 kHz
- Stable operation

Oscilloscope waveform:

![Waveform](../images/inverter/waveform.jpg)
