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
<img width="624" height="269" alt="image" src="https://github.com/user-attachments/assets/635c9837-d5f5-4d6f-acc9-8a47a4368230" />

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
<img width="1072" height="1599" alt="image" src="https://github.com/user-attachments/assets/6c2d4279-3236-4f6a-9944-e5227c2b5c6f" />

MODEL GRAPH 

<img width="1366" height="1600" alt="image" src="https://github.com/user-attachments/assets/feb908bc-ee6d-4a9c-99b4-ff509c6f44f2" />



DESIGN:

Inverting amplifier:

<img width="1071" height="1600" alt="image" src="https://github.com/user-attachments/assets/a6e0ccfc-c6c4-4b2d-b0ea-e8acc6f1861e" />


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

<img width="1130" height="1600" alt="image" src="https://github.com/user-attachments/assets/ae233286-1779-4f76-8d3f-464cf27c5908" />


---
## OUT PUT WAVEFORM AND DISCUSSION 

<img width="1043" height="1600" alt="image" src="https://github.com/user-attachments/assets/e300e8a9-d60e-4587-aa0d-c67b6e0acda7" />

<img width="1140" height="1599" alt="image" src="https://github.com/user-attachments/assets/5f018d98-dfb5-4ce2-a9a3-b409c451425f" />
---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM


<img width="1600" height="1326" alt="image" src="https://github.com/user-attachments/assets/8047231c-b55b-487f-9574-6a91357d3339" />

---

## MODEL GRAPH


<img width="1600" height="1226" alt="image" src="https://github.com/user-attachments/assets/ca0ecada-9ef4-4b7b-84d3-f5f83517853d" />

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


<img width="1600" height="1329" alt="image" src="https://github.com/user-attachments/assets/0725a420-f172-440b-bfb0-25209242af8b" />

---
## OUT PUT WAVEFORM AND DISCUSSION 


<img width="1118" height="1600" alt="image" src="https://github.com/user-attachments/assets/040cd60f-ce8b-4f88-8db9-ffca0716a661" />


<img width="1140" height="1599" alt="image" src="https://github.com/user-attachments/assets/545269c3-d674-4f1e-a46e-fd2e7e62bf9d" />

---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM



## MODEL GRAPH




---

## DESIGN


### **Differential Amplifier**


<img width="1600" height="821" alt="image" src="https://github.com/user-attachments/assets/a6ca2909-29eb-43e4-81ba-75e96a851c7d" />


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


<img width="1600" height="823" alt="image" src="https://github.com/user-attachments/assets/c1e81eeb-d0c4-42fc-8303-e3f214efa066" />

---
## OUT PUT WAVEFORM AND DISCUSSION 

<img width="1261" height="1600" alt="image" src="https://github.com/user-attachments/assets/f2bb49af-4a95-4590-8bb4-c619388f9433" />


<img width="1600" height="1429" alt="image" src="https://github.com/user-attachments/assets/692e2807-877a-4f50-8f67-8ecf9f121d0e" />

---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER




<img width="1600" height="1382" alt="image" src="https://github.com/user-attachments/assets/e686dbe8-5104-459c-9490-ae95d296a88d" />


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


<img width="1600" height="773" alt="image" src="https://github.com/user-attachments/assets/70cff303-21e0-4a24-aa6c-e0738910948c" />


---
## OUT PUT WAVEFORM AND DISCUSSION 


<img width="1312" height="1600" alt="image" src="https://github.com/user-attachments/assets/26b3bf8c-bc8d-4a74-8091-00f3927eb244" />


<img width="1600" height="1373" alt="image" src="https://github.com/user-attachments/assets/f7f72b44-0331-4c4e-8fa6-e6540673604e" />


---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
