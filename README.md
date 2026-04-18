
Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Objective
Download and install OptiPerformer software on your computer and run a sample file.

---

## Overview

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

In this exercise, you will:
- Download and install OptiPerformer on your PC/laptop.
- Use your license to load and run OptiSystem simulations prepared for this course.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Instructions

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.

---

## Report

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---

## Tabulation

**Transmission Analysis Across Fiber Lengths**

| S.No | Fiber Length (km) | Optical Power (Watts) | Optical Power (dBm) | Max Q Factor | Min BER | Eye Height | Decision Instant (Max Q / Min BER) |
|------|-------------------|------------------------|----------------------|--------------|---------|-------------|-------------------------------------|
|      |                   |                        |                      |              |         |             |                                     |
|      |                   |                        |                      |              |         |             |                                     |
|      |                   |                        |                      |              |         |             |                                     |
|      |                   |                        |                      |              |         |             |                                     |
|      |                   |                        |                      |              |         |             |                                     |

<img width="1326" height="924" alt="WhatsApp Image 2026-04-18 at 14 14 32" src="https://github.com/user-attachments/assets/e80fbba6-ead1-484d-90bc-f5f1d76bd45b" />

---

## Graphs

<img width="1015" height="912" alt="image" src="https://github.com/user-attachments/assets/60514140-7f0a-48e3-b985-aa25cc94c0d8" />
<br/>
<img width="999" height="949" alt="image" src="https://github.com/user-attachments/assets/db1db8ac-ae7d-4825-b830-5a107cfaca7f" />
<br/>
<img width="1065" height="947" alt="image" src="https://github.com/user-attachments/assets/d5a68616-5a67-47f3-bcea-eaab3e000c37" />
<br/>
<img width="1010" height="928" alt="image" src="https://github.com/user-attachments/assets/d6ed1c4e-1658-4294-b10c-e14726d5ffcc" />
<br/>
<img width="1004" height="937" alt="image" src="https://github.com/user-attachments/assets/f25ac754-fd7a-4b6f-beba-452396caa658" />



---

## RESULT

The optical communication system was successfully simulated using OptiPerformer, and the signal transmission through fiber was analyzed.
The received power and BER confirmed reliable communication with acceptable signal quality.
