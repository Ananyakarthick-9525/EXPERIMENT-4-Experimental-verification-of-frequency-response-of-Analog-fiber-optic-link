
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable 

---

## THEORY
Fiber optic links can be used for transmission of digital as well as analog signals.  Basically a 
fiber optic link contains three main elements, a transmitter, an optical fiber and a receiver. The 
transmitter module takes the input signal in electrical form and then transforms it into optical 
(light) energy containing the same information. The optical fiber is the medium which takes 
the energy to the receiver. At the receiver light is converted back into electrical form with the 
same pattern as originally fed to the transmitter. 

**TRANSMITTER:**

Fiber Optic transmitters are typically composed of a buffer, driver and Optical Source. The 
buffer electronics provides both an electrical connection and isolation between the transmitter 
and the electrical system supplying the data. The driver electronics provides electrical power to 
the Optical source in a fashion that duplicates the pattern of data being fed to the transmitter. 
Finally the optical source (LED) converts the electrical current to light energy with the same 
pattern. The LED SFH450V (950nm) supplied with this kit operates outside the visible light 
spectrum. Its Optical output is centered at near infrared wavelength of 950nm. The LED 
SFH756V (660nm) supplied with this kit operates at the visible light spectrum. Its Optical output 
is centered at wavelength of 660nm. 

**RECEIVER:** 

The function of the receiver is to convert the optical energy into electrical form, which is then 
conditioned to reproduce the transmitted electrical signal in it's original form. The detector 
SFH350V (Photo Transistor Detector) used in the kit has a transistor type output. The parameters 
usually considered in the case of detector are it's responsivity at peak wavelength and response 
time. SFH350V (Photo Transistor Detector) has responsivity of about 0.8mA/10uW at 660nm. 
But its response time is quite large and thus has lower bandwidth of about 300 KHz. When 
optical signal falls on the base of the transistor detector, proportional 
current flows through its emitter generating the voltage across the resistance connected between emitter 
and ground. This voltage is the duplication of the transmitted electrical signal, which can be amplified. 




---

## PROCEDURE

▪ Refer to the block diagram & carry out the following connections and settings.

▪ Connect the power supply with proper polarity to the kit link-B and switch it on. 

▪ Keep all Switch Faults in OFF position. 

▪ Keep switch SW8 towards TX position. 

▪ Keep switch SW9 towards TX1 position. 

▪ Keep Jumper JP5 towards +12V position. 


<img width="685" height="292" alt="image" src="https://github.com/user-attachments/assets/deeb13f1-8e37-4986-822b-559132f14281" />

 
-	Connect the output post OUT of Analog Buffer to the post TX IN of Transmitter.
-	Slightly unscrew the cap of SFH756V (660nm). Do not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by screwing it back.
-	Connect the other end of the Fiber to detector SFH350V (Photo Transistor Detector) very carefully.
-	Observe the detected signal at post ANALOG OUT on oscilloscope. Adjust Intensity control pot P2 Optical Power control potentiometer so that you receive signal of 2Vpp amplitude.

<img width="743" height="301" alt="image" src="https://github.com/user-attachments/assets/1ee120f9-92c5-4e97-ac32-f6520bf30d78" />


-	To measure the analog bandwidths of the phototransistor vary the input signal frequency and observe the detected signal at various frequencies.
-	Plot the detected signal against applied signal frequency and from the plot determine the 3dB down frequency.
-	Keep switch SW9 towards TX2 position.
-	Keep Jumper JP7 towards +12V position.
-	Remove fiber cable from SFH756V (660nm) and slightly unscrew the cap of SFH450V (950nm). Do not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by screwing it back.
-	Observe the detected signal at post ANALOG OUT on oscilloscope.

<img width="721" height="292" alt="image" src="https://github.com/user-attachments/assets/599d4fcc-b1e2-45fb-a98d-5f833cade038" />


---

## BLOCK DIAGRAM

<img width="527" height="222" alt="515235141-d2248f07-ce55-40c0-8d09-39470fb07e51" src="https://github.com/user-attachments/assets/48e89094-081d-475e-a66f-5cdb5e77b889" />


---
## CONNECTION DIAGRAM  
**Setting up an Analog Link**

<img width="571" height="122" alt="515235312-6cbd9ecb-c2bc-43bb-8ddb-031a9a7d81f2" src="https://github.com/user-attachments/assets/f71e2739-f6b7-4851-878f-10d7d811cf7b" />



## TABULATION  
**Transmission through Analog Link**
![IMG_20251124_222022](https://github.com/user-attachments/assets/e15b2859-1e0e-4abd-b49c-dc6f0922ee18)

![518014589-8b35a7e5-781b-4929-8312-9804fd5d6159](https://github.com/user-attachments/assets/daccf5b1-9599-453c-8262-5568a9f9e437)










---

## RESULT
The transmitted and received waveforms for the 660 nm fiber link matched closely, confirming faithful analog and digital signal transfer.
Output amplitude decreased with increasing frequency, showing the fiber link’s frequency-dependent response.
The calculated –3 dB point confirms the bandwidth of the 660 nm analog/digital fiber optic link.

