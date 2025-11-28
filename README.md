#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
**DATE:**  
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM
![WhatsApp Image 2025-11-28 at 10 21 59_e3131396](https://github.com/user-attachments/assets/1f996668-0db8-44b7-9627-32ec7ad3c794)


CIRCUIT DIAGRAM: INVERTING AMPLIFIER:

![WhatsApp Image 2025-11-28 at 10 21 59_246db89c](https://github.com/user-attachments/assets/450e23a0-9e65-4a9e-9247-ffe6749bf100)


MODEL GRAPH 

![WhatsApp Image 2025-11-28 at 10 22 00_d3a5095f](https://github.com/user-attachments/assets/63a65417-f427-4f66-8eba-febc8c41863c)




DESIGN:

Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION
![WhatsApp Image 2025-11-28 at 10 22 00_f441583f](https://github.com/user-attachments/assets/8ed45d8c-6659-4652-aa70-3721c1f9e14e)
---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-28 at 10 22 01_80177c2f](https://github.com/user-attachments/assets/77345f92-74f8-4a7a-a8e9-c2a220aa4a2e)


---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-28 at 10 28 44_8d282c89](https://github.com/user-attachments/assets/2d999fc1-2a37-4161-bb01-69ffec966f96)


## MODEL GRAPH
![WhatsApp Image 2025-11-28 at 10 28 44_06dd6fdf](https://github.com/user-attachments/assets/2e0492d1-a65d-4d02-a17a-dec6233fd1dd)

PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION
![WhatsApp Image 2025-11-28 at 10 28 45_dfca9478](https://github.com/user-attachments/assets/97f88600-f9e7-479b-b3f4-6b2fc59a587a)



## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-28 at 10 28 45_afa4bb11](https://github.com/user-attachments/assets/cede140b-5071-4e4f-8c99-1a897dc37fa8)

---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-28 at 10 33 48_a2ebc58c](https://github.com/user-attachments/assets/accdd49d-0141-419e-826d-f949180f24f7)

## MODEL GRAPH:
![WhatsApp Image 2025-11-28 at 10 33 49_ea54258c](https://github.com/user-attachments/assets/c068ebc1-2774-486a-9152-4b0af2e523e0)

## DESIGN

### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  R1 = 1kOhm, Rf = 10kOhm

---



## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)

![WhatsApp Image 2025-11-28 at 10 33 48_f629095b](https://github.com/user-attachments/assets/b5f9e89e-6cd2-4dc9-b5a6-30468330411c)

---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-28 at 10 33 49_cf7dc1fc](https://github.com/user-attachments/assets/aa27b5f6-3932-4ad8-9761-49078f870786)


## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

<img width="1006" height="1087" alt="image" src="https://github.com/user-attachments/assets/636c08f9-7940-470e-a89e-4891d57a9ac7" />

PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)

![WhatsApp Image 2025-11-28 at 10 40 16_37062999](https://github.com/user-attachments/assets/95e0eb38-4f6c-4b39-a614-78f5f08f95df)

---
## OUT PUT WAVEFORM AND DISCUSSION

![WhatsApp Image 2025-11-28 at 10 40 16_0813d738](https://github.com/user-attachments/assets/9cdb7f06-aece-478c-a0e0-cd28f9ad8c5d)

---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
