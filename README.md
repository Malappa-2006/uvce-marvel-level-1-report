# Task 1 - LTspice and KiCad

## Objective
To design and simulate a **555 timer-based astable multivibrator** using LTspice and create a **PCB layout** for an LED blinking circuit using KiCad.  

---

## Tools Used
- **LTspice** – for simulation and waveform observation.  
- **KiCad** – for schematic creation and PCB layout design.

---

## Circuit Description
A **555 timer IC** is configured in **astable mode** to generate continuous square wave pulses.  
These pulses drive an **LED**, causing it to blink at a frequency determined by two resistors (R1, R2) and a capacitor (C1).

**Key Components:**
- IC 555 Timer  
- Resistors: R1, R2  
- Capacitor: C1  
- LED and Current limiting resistor  

---

## Simulation in LTspice
1. Constructed the 555 astable circuit using basic components.  
2. Simulated the waveform output at pin 3 (OUT).  
3. Observed the **frequency** and **pulse width** variation with changes in R1, R2, and C1.  

**Output:** Square wave signal showing ON and OFF periods corresponding to LED blinking.

### LTspice Simulation Screenshot
![LTspice Simulation Result](https://github.com/Malappa-2006/uvce-marvel-level-1-report/blob/main/ltspice.jpeg?raw=true)

---

## Schematic and PCB Design in KiCad
1. Created the schematic of the LED blinking circuit.  

### KiCad PCB Layout Screenshot
![KiCad PCB Layout](https://example.com/kicad-pcb-layout.png)

---

## Results
- Successfully simulated the 555 timer-based astable multivibrator in LTspice.  
- Designed a working PCB layout in KiCad.  
- Verified the output waveform and LED blinking frequency.  

---

## Outcome
- Understood **SPICE-based circuit simulation** using LTspice.  
- Learned **EDA workflows**, including schematic creation, layout design, and output file generation.

---

## Conclusion
The experiment demonstrated the working of a 555 timer in astable mode and introduced essential **simulation and PCB design fundamentals** using LTspice and KiCad.


