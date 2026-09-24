# Experiment 4
# GENERATION-AND-DETECTION-OF-FM---USING---SCILAB---T1---M4---ODD
# FREQUENCY MODULATION AND DEMODULATION

## AIM

To write a program for Frequency Modulation and Demodulation using SCILAB and to observe and measure the frequency deviation and the modulation index of FM.

---

## EQUIPMENTS REQUIRED

* Computer with i3 Processor
* SCI LAB

---

## THEORY

Frequency modulation is a type of modulation in which the frequency of the high frequency (carrier) is varied in accordance with the instantaneous value of the modulating signal.

### FREQUENCY DEVIATION Δf and MODULATION INDEX mf:

The frequency deviation **Δf** represents the maximum shift between the modulated signal frequency, over and under the frequency of the carrier.

We define modulation index **mf** the ratio between **Δf** and the modulating frequency.

$$
m_f = \frac{\Delta f}{f_m}
$$

---

## FREQUENCY MODULATION GENERATION

The circuits used to generate a frequency modulation must vary the frequency of a high frequency signal (carrier) as function of the amplitude of a low frequency signal (modulating signal). In practice there are two main methods used to generate FM.

---

## ALGORITHM

### 1. Define Parameters:

* **Fs:** Sampling frequency.
* **T:** Duration of the signal.
* **Fc:** Carrier frequency.
* **Fm:** Frequency of the modulating signal.
* **Beta:** Modulation index, which controls the extent of frequency deviation.

### 2. Generate Signals:

* **modulating_signal:** Sinusoidal signal used for modulation.
* **carrier_signal:** The high-frequency carrier signal.
* **modulated_signal:** FM modulated signal calculated by varying the carrier frequency according to the modulating signal.

### 3. FM Modulation:

* **Modulated_signal** is obtained by modulating the carrier signal with the modulating signal.

### 4. FM Demodulation:

* **Differentiation:** Computes the derivative of the modulated signal to extract frequency variations.
* **Envelope Detection:** Takes the absolute value to retrieve the envelope of the signal.
* **Low-pass Filtering:** Applies a Butterworth low-pass filter to smooth the envelope and recover the original modulating signal.

### 5. Visualization:

* Plots the modulating signal, carrier signal, FM modulated signal, and demodulated signal for analysis.

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

## MODEL GRAPH

## Tabulation 

<img width="1280" height="826" alt="image" src="https://github.com/user-attachments/assets/a237e528-9d6c-4d71-8b1c-5d50e9e74922" />
## CALCULATION
<img width="1600" height="1200" alt="WhatsApp Image 2026-09-23 at 4 06 28 PM" src="https://github.com/user-attachments/assets/4d19c30a-c04e-480d-b94d-d4eee216fd40" />


## output
<img width="1110" height="634" alt="image" src="https://github.com/user-attachments/assets/3fb22b87-d082-4f92-99cd-46f35c61b681" />


## Results

 Successfully generated frequency Modulation and Demodulation using SCILAB and to observe and measure the frequency deviation and the modulation index of FM.
