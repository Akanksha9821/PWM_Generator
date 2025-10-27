# PWM Generator using CD40106 and Operational Amplifiers

## Overview
This project presents the design and simulation of a Pulse Width Modulation (PWM) Generator using a Schmitt Trigger Oscillator (CD40106) and Operational Amplifiers.  
The system efficiently generates PWM signals with adjustable duty cycles, suitable for use in motor control, communication systems, and power regulation.

The design and validation were performed in **eSim** using the **IHP SG13G2 PDK**, ensuring compatibility with open-source EDA workflows.

---

## Abstract
Pulse Width Modulation (PWM) is a fundamental technique in electronics, enabling efficient control of power, signal modulation, and communication.  
This project implements a PWM generator circuit in which:

- The **CD40106 Schmitt Trigger** produces a stable sawtooth waveform.  
- The waveform is **buffered by an operational amplifier** for stability.  
- A **comparator stage** compares the sawtooth with a control voltage (CV input) to produce a PWM signal with an adjustable duty cycle.

The circuit was designed and simulated in **eSim** using the **IHP SG13G2 PDK**, demonstrating cost-effective and reliable PWM generation.

---

## Components Used
- CD40106 Schmitt Trigger IC  
- Operational Amplifiers (Op-Amps)  
- Resistors and Capacitors for timing and signal conditioning  
- Variable Control Voltage Source (CV)  
- eSim (Open-source EDA tool)  
- IHP SG13G2 PDK  

---

## Circuit Design

### Schematic
![PWM Generator Schematic](./PWM%20Generator%20Schematic.pdf)

The design consists of:
1. A **Schmitt Trigger Oscillator** using CD40106 to produce a sawtooth waveform.  
2. **Buffering op-amp** to stabilize the signal.  
3. **Comparator stage** that generates the PWM output by comparing the sawtooth waveform and the control voltage.

---

## Simulation Results
*(Add waveform plots or screenshots here once available.)*

**Expected Outputs:**
- Sawtooth waveform at the oscillator stage.  
- PWM waveform with a variable duty cycle depending on the CV input.

---

## Applications
- DC motor speed control  
- Signal modulation and demodulation  
- Power regulation circuits  
- Audio amplifiers and LED dimming systems  

---

## References
1. B. K. Bose, *Power Electronics and Motor Drives: Advances and Trends*, Academic Press, 2006.  
2. A. Sedra and K. Smith, *Microelectronic Circuits*, 7th Edition, Oxford University Press, 2015.  

---

## Tools and Environment
- Software: eSim (Open Source EDA)  
- PDK: IHP SG13G2  
- Design Type: Analog Circuit Design  

---

## Author
**Akanksha**  
Department of EECE  
Gandhi Institute of Technology and Management (GITAM)  
Email: [aakanksh@gitam.in](mailto:aakanksh@gitam.in)
# PWM_Generator
