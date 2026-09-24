# DSB-SC-AM-MODULATOR-AND-DEMODULATOR-USING-SCILAB-T1-M4-ODD
# DSB-SC-AM MODULATOR AND DEMODULATOR

## AIM

To write a program to perform DSBSC modulation and demodulation using SCI LAB and study its spectral characteristics.

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

* **Message Signal:** A sinusoidal signal that will be modulated.
* **Carrier Signal:** A high-frequency sinusoidal signal used for modulation.

### 3. DSBSC Modulation:

* **Modulated Signal:** Multiply the message signal by the carrier signal to produce the DSBSC signal.

### 4. DSBSC Demodulation:

* **Multiplication:** Multiply the modulated signal by the carrier signal to get the product of the message signal with itself (i.e., the original message signal plus high-frequency components).
* **Low-pass Filtering:** Apply a Butterworth low-pass filter to remove the high-frequency components and recover the original message signal.

### 5. Visualization:

Plot the message signal, carrier signal, DSBSC modulated signal, and the recovered signal after demodulation.

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
am=6.6;

fm=414;

ac=13.2;

fc=4140;

fs=41400;

t=0:1/fs:3/fm;

em=amcos(23.14fmt);

subplot(3,1,1);

plot(t,em);

ec=accos(23.14fct);

subplot(3,1,2);

plot(t,ec);

eam1=ac*(1+(em/ac)).cos(23.14fct);

eam2=ac*(1-(em/ac)).cos(23.14fct);

edsbsc=eam1-eam2;

subplot(3,1,3);

plot(t,edsbsc);

---

## TABULATION
<img width="945" height="1600" alt="WhatsApp Image 2026-09-23 at 12 48 09 PM" src="https://github.com/user-attachments/assets/47512fee-f161-44b5-9cda-89abb8943f7c" />


---

## OUTPUT GRAPH
<img width="1600" height="1320" alt="WhatsApp Image 2026-09-23 at 12 48 10 PM" src="https://github.com/user-attachments/assets/e5ba4f92-b3a9-40ea-b3d8-0098ed045cbe" />

Result

Thus the DSB-SC-AM Modulation and Demodulation is generated.

---
