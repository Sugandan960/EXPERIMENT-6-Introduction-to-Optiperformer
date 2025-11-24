<img width="623" height="346" alt="image" src="https://github.com/user-attachments/assets/a9bdc7c1-cdfe-4ade-9d5e-0225bd73c387" /><img width="623" height="346" alt="image" src="https://github.com/user-attachments/assets/ab3ba6d9-cd87-47bf-8979-75d860f2994e" />N.Sugandan 
212222060260
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

![17639580038799048865401384102905](https://github.com/user-attachments/assets/b4389347-2cad-431f-827e-baa01e183846)


---

## graphs:

<img width="623" height="346" alt="17639582461552439478337976438512" src="https://github.com/user-attachments/assets/74f417aa-dbec-4c12-b14d-8ae35d4df9cd" />



<img width="624" height="361" alt="1763958351496270671383424412732" src="https://github.com/user-attachments/assets/0067c741-c563-462e-bbac-1278a1d41736" />


<img width="625" height="358" alt="176395892102851744674721689211" src="https://github.com/user-attachments/assets/ceaf968d-5a04-4501-b06e-233adc840423" />


![Uploading 17639589750134527120855616278396.png…]()





## RESULT

Hence the graphs are verified using optiperformer.
