# SSB-SC-AM-MODULATOR-AND-DEMODULATOR-USING-SCILAB-T1-M4-ODD
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

---

## TABULATION
<img width="1599" height="899" alt="image" src="https://github.com/user-attachments/assets/ee6b092b-2350-4ea0-9df6-e297bcf360b9" />


## CALCULATION:

<img width="1599" height="899" alt="image" src="https://github.com/user-attachments/assets/b9b18fa7-2963-413e-b21f-329867748153" />

## GRAPH:

<img width="1599" height="899" alt="image" src="https://github.com/user-attachments/assets/da513351-2420-46dc-abf6-efd23745f355" />

##RESULT: Thus, the SSB-SC-AM Modulation and Demodulation is experimentally done and the output is verified.




