#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
**DATE:**12/08/2025  
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
| 6 | Resistors | 20k 10k 3k 1.5k | 2 |
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
<img width="624" height="269" alt="image" src="https://github.com/user-attachments/assets/635c9837-d5f5-4d6f-acc9-8a47a4368230" />

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![WhatsApp Image 2025-11-24 at 17 19 17_e985eea8](https://github.com/user-attachments/assets/26a7371f-ad89-4c83-9359-a4a23733c699)

MODEL GRAPH 

<img width="543" height="357" alt="image" src="https://github.com/user-attachments/assets/1836d120-768e-454f-bfe4-682ce70ea7a1" />



DESIGN:

Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

![WhatsApp Image 2025-11-24 at 17 19 58_2fa558ae](https://github.com/user-attachments/assets/1f6b6e77-aad4-4c70-ab3d-2968417af9aa)


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

![WhatsApp Image 2025-11-24 at 17 27 29_6d4c2fdc](https://github.com/user-attachments/assets/217487a6-2fd1-4ab2-ba7b-da1c57b30487)

 


---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-24 at 17 20 30_2bba7084](https://github.com/user-attachments/assets/9621c8a2-b27e-4172-b26a-69302b8c4a3e)
![WhatsApp Image 2025-11-24 at 17 27 46_c1542b1b](https://github.com/user-attachments/assets/ccab6d86-87e2-4afa-9616-caa27c3096ec)

---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM


![WhatsApp Image 2025-11-24 at 17 19 32_396b1530](https://github.com/user-attachments/assets/7ae8130e-8f2a-4327-b8cc-3ed1641afe5a)

DESIGN

![WhatsApp Image 2025-11-24 at 17 20 03_01c995de](https://github.com/user-attachments/assets/9478e321-68e4-4d53-8fce-a1113940728b)

---

## MODEL GRAPH

<img width="456" height="340" alt="image" src="https://github.com/user-attachments/assets/00c7aaec-b4d8-414e-afa3-e985eb3dd902" />

---
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

![WhatsApp Image 2025-11-26 at 20 31 17_b530bdba](https://github.com/user-attachments/assets/e6479391-197c-4d8e-a99a-d594a4fcc6f2)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-24 at 17 20 39_f11a3063](https://github.com/user-attachments/assets/04eb9330-7fdd-4c35-872b-4ffd8de6e566)

![WhatsApp Image 2025-11-24 at 17 27 46_2dbcf299](https://github.com/user-attachments/assets/50605cc7-d7b5-48b3-ac61-916481207408)

---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-24 at 17 32 20_054697e5](https://github.com/user-attachments/assets/d6d92e0f-a2dc-4328-b8f6-bc7e5e17e73e)

## MODEL GRAPH
<img width="678" height="334" alt="image" src="https://github.com/user-attachments/assets/6aa1b9dd-b112-4be1-a37a-d5ee19607b1d" />

---

## DESIGN
![WhatsApp Image 2025-11-24 at 17 20 15_7ca3b4c9](https://github.com/user-attachments/assets/c8878848-3b16-4d33-848a-82e67f7d025d)


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

![WhatsApp Image 2025-11-26 at 20 31 38_0587c743](https://github.com/user-attachments/assets/63cfdd7d-dd6f-4b68-9316-14a6044080ba)

---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-24 at 17 21 00_ebfba25f](https://github.com/user-attachments/assets/8f067d85-1744-49c9-b1b7-1b27159cda72)

![WhatsApp Image 2025-11-24 at 17 27 53_91644e97](https://github.com/user-attachments/assets/92950d98-db8c-4f97-bfae-305726c9b156)


---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER


![WhatsApp Image 2025-11-24 at 17 19 50_d4f8b507](https://github.com/user-attachments/assets/a45068e9-52bf-40f1-a9a8-9a4eaa3e6d46)

DESIGN

![WhatsApp Image 2025-11-24 at 17 20 20_2f7824d7](https://github.com/user-attachments/assets/59abdbb7-ad0d-4587-9d74-191743bc6eb9)

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

![WhatsApp Image 2025-11-26 at 20 31 52_46b5f497](https://github.com/user-attachments/assets/db754f28-08f5-4d95-a846-0b7a80ac10f8)

---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-24 at 17 21 00_a9436a17](https://github.com/user-attachments/assets/63879c2c-09b3-48f4-b2bf-baf31fef65d6)

![WhatsApp Image 2025-11-24 at 17 27 53_5d6c823b](https://github.com/user-attachments/assets/6d9d8d03-563f-4973-a892-e770f2adf2f7)

---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
