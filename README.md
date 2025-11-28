# EX-NO-6-EXPERIMENTAL-VERIFICATION-AND-SIMULATION-OF-ACTIVELPF-HPF-AND-BPF
## 6 DESIGN OF ACTIVE LOW PASS, HIGH PASS AND BAND PASS FILTERS USING OP-AMP

         
---


            
**DATE:**  24/09/2025
         
---

## AIM and obtain the frequency response of

i)	First order Low Pass Filter (LPF)
ii)	First order High Pass Filter (HPF)
iii)	Band pass filter

---

** 6 A :- LOW PASS FILTER**



## THEORY
## LOW PASS FILTER
A LPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.
## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 5k  2.5k  1k  0.01uf | 1 |
| 7 | Connecting wires and probes | As required | — |

---
## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-26 at 22 00 10_64efe43c](https://github.com/user-attachments/assets/ddd93b02-95a2-4ff8-83b9-5e1b02c0411b)

![WhatsApp Image 2025-11-26 at 22 01 40_47c5b4e6](https://github.com/user-attachments/assets/e5c702c9-ac5c-42d6-9e52-6a763d77f058)




## MODEL GRAPH
<img width="913" height="559" alt="image" src="https://github.com/user-attachments/assets/c8d28c41-6f3e-44a6-a9da-2b798cf07346" />

---

## DESIGN

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ

![WhatsApp Image 2025-11-26 at 22 00 25_89806a70](https://github.com/user-attachments/assets/b5a55176-3e27-4563-8bb9-271cfb15ea5b)



## PROCEDURE

PROCEDURE - (LPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency  lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

![WhatsApp Image 2025-11-26 at 22 00 40_17124102](https://github.com/user-attachments/assets/edae87fb-7180-45c5-bfab-25ca27799323)

---

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-26 at 22 01 07_4b8dda38](https://github.com/user-attachments/assets/973c103f-0d5d-4c8f-a3b1-200b9caea5fe)

![WhatsApp Image 2025-11-26 at 22 01 20_e62322d6](https://github.com/user-attachments/assets/bb09b8c2-4724-4014-97a2-31d4f4779508)

![WhatsApp Image 2025-11-26 at 22 01 52_b434f2e8](https://github.com/user-attachments/assets/88168ede-f7be-4e21-aa10-8641ca795b8c)





---
DATE:30/09/2025
 ## 6 B HIGH PASS FILTER

---

## THEORY
HIGH PASS FILTER
A HPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors |5k  2.2k  1k  0.01uf| 1 |
| 7 | Connecting wires and probes | As required | — |


## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-26 at 22 02 07_d900e48a](https://github.com/user-attachments/assets/9cf959ce-5b73-4068-9317-b0ae80ada53b)

![WhatsApp Image 2025-11-26 at 22 03 11_b2ab7f63](https://github.com/user-attachments/assets/d29ea28e-23b5-42cd-a6b7-4471d7b27601)



## MODEL GRAPH

<img width="1005" height="382" alt="image" src="https://github.com/user-attachments/assets/22925efc-4abc-4fad-90d5-94f3348c3c0b" />

---

## DESIGN

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ


![WhatsApp Image 2025-11-26 at 22 02 18_236042e8](https://github.com/user-attachments/assets/be6a0995-2479-48de-98e9-c38e8f9b8424)

## PROCEDURE

PROCEDURE - ( HPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency ( lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

![WhatsApp Image 2025-11-26 at 22 02 29_35cc4a42](https://github.com/user-attachments/assets/ed4fdb13-5aa5-4319-b52a-366150d1e95a)


---

## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-26 at 22 02 50_bf6c63f1](https://github.com/user-attachments/assets/7b7ffca7-c0ed-4878-8fc4-e229bb05133b)

![WhatsApp Image 2025-11-26 at 22 02 58_e2b6eda5](https://github.com/user-attachments/assets/9f5c77b6-0e9f-4cc7-9213-c3abc3af493a)

![IMG-20251126-WA0052 1](https://github.com/user-attachments/assets/4444556c-72f2-41fc-bec9-fe54ce0c04cf)




---
DATE:07/10/2025
 ## 6C Band Pass Filter

---

## THEORY
 ##Band Pass Filter
A BPF allows frequencies in between lower cut of frequency and higher cut of frequency, fH-fL. A band-pass (BP) filter passes frequencies in a band fL_fH and attenuates below fL and above fH.. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors |5k  800ohm  30k 0.01uf| 1 |
| 7 | Connecting ires and probes | As required | — |


## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-26 at 22 03 37_c8c18f68](https://github.com/user-attachments/assets/a8593c05-f2b5-44ab-8e86-b7da11a5a45c)

![WhatsApp Image 2025-11-26 at 22 05 01_fafac1db](https://github.com/user-attachments/assets/1b71bee9-19db-4feb-8096-bf05e56228f8)


## MODEL GRAPH

<img width="1055" height="537" alt="image" src="https://github.com/user-attachments/assets/f5eec55a-c00c-4eaf-a680-81ba95f66490" />


---

## DESIGN

DESIGN: BAND PASS FILTER

Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.
1.	Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency of HPF as fL = 1 KHz.
2.	Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf. Let C = 0.1μf.
3.	Calculate R from the expression. Given: fH = 2KHz = 1/ (2πR1C1) Let C1 = 0.1 µF, R1 = 7.9 KΩ
Given: fL = 400Hz = 1/ (2πR2C2)
Let C2 = 0.1 µF, R2 = 39.8 KΩ
Pass band Gain=4
Now		Ao = 1 + (Rf / R1) 2-1=(Rf / Ri)
Ri = Rf
Let Ri = Rf = 10 KΩ

![WhatsApp Image 2025-11-26 at 22 03 52_8b8b4c18](https://github.com/user-attachments/assets/19365a1d-f3c9-49d9-be97-dd3bbf5c5b1b)



## PROCEDURE

PROCEDURE:BAND PASS FILTER
1.	Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2.	Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3.	Connect the circuit as shown in the circuit diagram.
4.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5.	Tabulate the output voltage Vo with respect to different values of input frequency.
6.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

![WhatsApp Image 2025-11-26 at 22 04 04_48b9d56f](https://github.com/user-attachments/assets/f5e4d13d-092f-42ec-b798-89781510a48d)

---

## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-26 at 22 04 33_d277d658](https://github.com/user-attachments/assets/7c58bf61-6d85-4ab4-8ff0-2a533cf95ab4)

![WhatsApp Image 2025-11-26 at 22 04 45_16a64d3a](https://github.com/user-attachments/assets/d77e6159-24a0-430a-8eb7-aec840b6e906)

![WhatsApp Image 2025-11-26 at 22 05 14_9864cb80](https://github.com/user-attachments/assets/8400d5c3-70d4-4e76-8a9d-bb12dbb0084a)




---
##RESULT:
	Thus an Active Low pass, High pass and Band Pass Filters are designed and
tested using op-amp IC 741.
---

   
