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
![019](https://github.com/user-attachments/assets/d1110441-b19c-4322-9537-81b6e064deee)

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![001](https://github.com/user-attachments/assets/e389de27-b6aa-4eb5-8d3b-01184b9fea4f)


MODEL GRAPH 

![002](https://github.com/user-attachments/assets/24eb3134-b1e4-47b9-9f8c-39a326ef17c7)




DESIGN:
![011](https://github.com/user-attachments/assets/fe5f84e8-7153-4973-bf10-4fab5e7602c3)


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

![003](https://github.com/user-attachments/assets/8bfc5f23-9456-4523-86b0-c0e11f172b30)

 


---
## OUT PUT WAVEFORM AND DISCUSSION 

![004](https://github.com/user-attachments/assets/528d9885-3955-4d33-895f-2244eae82b1b)

---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM

![005](https://github.com/user-attachments/assets/321d3e11-a13d-4495-a565-9ad615344240)


---

## MODEL GRAPH
![006](https://github.com/user-attachments/assets/f47e339d-bec2-4da7-a479-17893d1ddc36)

DESIGN:
![012](https://github.com/user-attachments/assets/46fb5abc-f189-4cf2-b011-9afa950381f2)



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

![007](https://github.com/user-attachments/assets/858f6bcd-2f27-4687-a89e-5031149589d2)

---
## OUT PUT WAVEFORM AND DISCUSSION 

![008](https://github.com/user-attachments/assets/f568e226-8289-4916-95d2-10f01f83d75c)

---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![009](https://github.com/user-attachments/assets/7789e503-9034-4440-b708-5b984e02c84e)


## MODEL GRAPH
![010](https://github.com/user-attachments/assets/7f338d3e-fb8c-4ef9-b80d-fe0b766b2023)


---

## DESIGN
![013](https://github.com/user-attachments/assets/d0fd6bac-8847-4ae1-9c11-eea95c4a207e)


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

![014](https://github.com/user-attachments/assets/1fd98c66-b378-4860-b2e0-38ebe285b2ec)

---
## OUT PUT WAVEFORM AND DISCUSSION 

![015](https://github.com/user-attachments/assets/0784824b-dece-41f6-b6d2-8dc69c780184)

---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER
![016](https://github.com/user-attachments/assets/e9ca8df2-073f-44cf-9865-6006ed9753f2)


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
![017](https://github.com/user-attachments/assets/56e992d6-f517-4b23-b19b-dc6bdfc96371)


---
## OUT PUT WAVEFORM AND DISCUSSION 

![018](https://github.com/user-attachments/assets/b3d35d73-9c15-42b9-b05f-6dc41faab270)

---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.
![020](https://github.com/user-attachments/assets/91d87e3d-87e0-4b35-9c79-25a5981cc3fb)
![021](https://github.com/user-attachments/assets/c7f94737-73db-4f68-95b3-1c26607977de)

---
