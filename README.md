# Sound-Level-Meter
A collaborative start to finish design of a sound level meter: Circuit Design, Simulation (LTSpice), PCB (KiCad)

**Overview**
The goal of this project was to design a sound level meter (sonomètre) under the following component constraints:
- EM100T
- JFET and bipolar transistors, and diodes
- Resistors
- LEDs
- 9 V Power supply

To complete this project a theoretical circuit was conceptualised, LTSpice was used to simulate, test and adapt the circuit. A prototype was then developed using a breadboard and lab bench. The final PCB design was then created on KiCad and printed for final testing and results. We achieved accurate sound level for 70dB, 75dB, 80dB and 85dB for our chosen resolution of 5dB.

**Key Concepts**
- Simulations: Modelling and simulating circuit (LTSpice) to test viability of initial design concept
- Measure of Sound Level: Peak/Envelope Detection, Calculation of of level (dB SPL)
- Calibration: Selection of physical components to reach desired output for known source
- Physical Conception: PCB design (KiCad) and printing
- Presentation of Results: Functional diagrams, graphs and simulation captures

---

## PCB

<div align="center">

![PCB back side](doc/images/Sonometre1.png)

**PCB — Component sides**

</div>

<div align="center">

![PCB component side](doc/images/Sonometre2.png)

**PCB — Reverse**

</div>
<div align="center">

![PCB physical board](doc/images/Sonometre_PCB.jpeg)

**PCB — Physical Board**

</div>
---
# Result

</div>
<div align="center">

![LED Thresholds](doc/images/final_result.png)

**LED dB Threshold**

---
# Project Structure
```
Sound-Level-Meter/
├── README.md
├── doc/
│   ├── Final_Report.pdf
│   ├── Components_List.xlsx
│   ├── oral-presentation.pptx
│   └── images/
│       ├── Schematic.png
│       ├── Sonometre1.png
│       ├── Sonometre2.png
│       ├── Sonometre_PCB.jpeg
│       └── final_result.png
├── LTSpice/
│   └── sound_level_meter.asc
├── kicad/
│   ├── sound_level_meter.kicad_pro
│   ├── sound_level_meter.kicad_sch
│   └── sound_level_meter.kicad_pcb

```
---

# Contributors
- Gavin Mac Aonghusa
- Titouan Bocquet
- Bosco de Rauglaudre
