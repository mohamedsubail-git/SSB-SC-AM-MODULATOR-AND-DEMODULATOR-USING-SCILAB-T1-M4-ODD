# Experiment 3
# SSB-SC-AM MODULATOR AND DEMODULATOR

## AIM

To write a program to perform SSBSC modulation and demodulation using SCI LAB and study its spectral characteristics.

---

## EQUIPMENTS REQUIRED

* Computer with i3 Processor
* SCI LAB

> **Note:** Keep all the switch faults in off position.

---

## ALGORITHM

### 1. Define Parameters:

* **Fs:** Sampling frequency.
* **T:** Duration of the signal.
* **Fc:** Carrier frequency.
* **Fm:** Frequency of the message signal.
* **Amplitude:** Maximum amplitude of the message signal.

### 2. Generate Signals:

* **Message Signal:** The baseband signal that will be modulated.
* **Carrier Signal:** A high-frequency signal used for modulation.
* **Analytic Signal:** Constructed using the Hilbert transform to get the in-phase and quadrature components.

### 3. SSBSC Modulation:

* **Modulated Signal:** Create the SSBSC signal using the in-phase and quadrature components, modulated by the carrier.

### 4. SSBSC Demodulation:

* **Mixing:** Multiply the SSBSC signal with the carrier to retrieve the message signal.
* **Low-pass Filtering:** Apply a low-pass filter to remove high-frequency components and recover the original message signal.

### 5. Visualization:

Plot the message signal, carrier signal, SSBSC modulated signal, and the recovered signal after demodulation.

---

## PROCEDURE

* Refer Algorithms and write code for the experiment.
* Open SCILAB in System.
* Type your code in New Editor.
* Save the file.
* Execute the code.
* If any Error, correct it in code and execute again.
* Verify the generated waveform using Tabulation and Model Waveform.

## PROGRAM
am=6.9;

fm=431;

ac=13.8;

fc=4310;

fs=43100;

t=0:1/fs:2/fm;

em1=amcos(23.14fmt);

subplot(4,1,1);

plot(t,em1);

em2=amsin(23.14fmt);

ec1=accos(23.14fct);

ec2=acsin(23.14fct);

subplot(4,1,2);

plot(t,ec1);

eam1=ac*(1+(em1/ac)).cos(23.14fct);

eam2=ac*(1-(em1/ac)).cos(23.14fct);

edsbsc1=eam1-eam2;

eam3=ac*(1+(em2/ac)).sin(23.14fct);

eam4=ac*(1-(em2/ac)).sin(23.14fct);

edsbsc2=eam3-eam4;

elsb=edsbsc1+edsbsc2;

subplot(4,1,3);

plot(t,elsb);

eusb=edsbsc1-edsbsc2;

subplot(4,1,4);

plot(t,eusb);

---

## TABULATION
<img width="1600" height="881" alt="image" src="https://github.com/user-attachments/assets/7d43bba8-e2c6-4d39-88e2-7e7408bdc3d4" />




---

## MODEL GRAPH

## output 
<img width="1071" height="634" alt="image" src="https://github.com/user-attachments/assets/1233d9fc-7833-45cf-96e5-0bae79cde9b5" />

## Results 
 Successfully performed SSBSC modulation and demodulation using SCI LAB
