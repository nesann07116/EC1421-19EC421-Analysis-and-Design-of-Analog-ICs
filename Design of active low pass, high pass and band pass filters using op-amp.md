# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
# DESIGN OF ACTIVE LOW PASS,HIGH PASS AND BAND PASS FILTERS USING OP-AMP 

## AIM: 

To design and obtain the frequency response of 
i) First order Low Pass Filter (LPF) 
ii) First order High Pass Filter (HPF) 
iii) Band pass filter
 
## APPARATUS REQUIRED

<img width="625" height="170" alt="image" src="https://github.com/user-attachments/assets/900fc8b3-3a8c-4208-bf52-98cc9e281e21" />

## THEORY
## LOW PASS FILTER 
 A LPF allows frequencies from 0 to higher cut of frequency, fH.  At fH the gain is 0.707 
Amax, and after fH gain decreases at a constant rate with an increase in frequency.  The gain 
decreases 20dB each time the frequency is increased by 10.  Hence the rate at which the gain 
rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in 
frequency.  The frequency f=fH is called the cut off frequency because the gain of the filter at this 
frequency is down by 3 dB from 0 Hz.  Other equivalent terms for cut-off frequency are -3dB 
frequency, break frequency, or corner frequency.
# HIGH PASS FILTER 
The frequency at which the magnitude of the gain is 0.707 times the maximum value of 
gain is called low cut off frequency.  Obviously, all frequencies higher than fL are pass band 
frequencies with the highest frequency determined by the closed –loop band width all of the op
amp. 
# BAND PASS FILTER 
A band pass filter has a pass band between two cutoff frequencies fH and fL such that fH > 
fL.  Any input frequency outside this pass band is attenuated.  There are two types of band-pass 
filters.  Wide band pass and Narrow band pass filters.  We can define a filter as wide band pass if 
its quality factor Q <10.  If Q>10, then we call the filter a narrow band pass filter.  A wide band 
pass filter can be formed by simply cascading high-pass and low-pass sections.  The order of 
band pass filter depends on the order of high pass and low pass sections.

## CIRCUIT DIAGRAM: 
## LOW_PASS
![WhatsApp Image 2025-11-27 at 11 36 17_48533fd9](https://github.com/user-attachments/assets/46421187-bed5-4525-9a1b-67d05ac1bc78)

## HIGH-PASS
![WhatsApp Image 2025-11-27 at 11 36 31_8e1b959f](https://github.com/user-attachments/assets/5ec2f9a6-711c-41e6-9463-134f4b5b7460)

## BAND-PASS
![WhatsApp Image 2025-11-27 at 11 36 50_5c472a9a](https://github.com/user-attachments/assets/61b39baa-aa9d-401b-a5d1-5a27878bea99)


## MODEL GRAPH:
## LOW_PASS
![WhatsApp Image 2025-11-27 at 11 37 08_09132e36](https://github.com/user-attachments/assets/b69fe48a-abcb-4c4a-8785-26f3ff032f92)

## HIGH-PASS
![WhatsApp Image 2025-11-27 at 11 37 24_75b706fe](https://github.com/user-attachments/assets/65284a7c-40a4-4f4c-a1de-eddafee017b2)

## BAND-PASS
![WhatsApp Image 2025-11-27 at 11 37 45_97528ad1](https://github.com/user-attachments/assets/4239d0d3-215a-48cd-99b1-d9af0c7f42e1)


## PROCEDURE - (LPF & HPF): 
1. Connect the circuit as shown in the circuit diagram. 
2. Select the corresponding cut-off frequency (higher or lower) and determine the value of C&R. 
select the value of R1 & Rf depending on desired passband gain Af.. 
3. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
4. Tabulate the output voltage Vo with respect to different values of input frequency. 
5. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to  get approximately the same characteristic as shown in the model graph. 
# PROCEDURE:BAND PASS FILTER 
1. Select the lower and higher cut-off frequency and calculate the value of R & C for the given 
frequencies. 
2. Design for LPF & HPF separately and then combine the circuit by first placing the HPF 
followed by a LPF (i.e) HPF in series with LPF. 
3. Connect the circuit as shown in the circuit diagram. 
4. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
5. Tabulate the output voltage Vo with respect to different values of input frequency. 
6. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to get approximately the same characteristic as shown in the model graph

## DESIGN:LPF & HPF:

<img width="429" height="324" alt="image" src="https://github.com/user-attachments/assets/b0f0ac0a-3006-494c-9096-e91ae2d6e87c" />

# DESIGN: BAND PASS FILTER
Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.  
1. Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency 
of HPF as fL = 1 KHz.  
2. Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf.  
Let C = 0.1μf.  
3. Calculate R from the expression.  
Given: fH = 2KHz  = 1/ (2πR1C1) 
   Let C1 = 0.1 µF, R1 = 7.9 KΩ 
Given: fL = 400Hz  = 1/ (2πR2C2) 
   Let C2 = 0.1 µF, R2 = 39.8 KΩ 
  Pass band Gain=4 
   Now   Ao = 1 + (Rf / R1)  
               2-1=(Rf / Ri) 
                Ri = Rf 
                 Let  Ri = Rf = 10 KΩ
## TABULATION:
## LOW_PASS
![WhatsApp Image 2025-11-27 at 11 38 22_ad33563f](https://github.com/user-attachments/assets/ab69c7bc-2e36-4fe6-820a-c770077a62ea)

## HIGH-PASS
![WhatsApp Image 2025-11-27 at 11 38 41_ee500c03](https://github.com/user-attachments/assets/5f23b29c-0157-49ba-86cc-a398f6aa7f92)

## BAND-PASS
![WhatsApp Image 2025-11-27 at 11 39 02_1ab6af12](https://github.com/user-attachments/assets/d7e95e20-01ed-42c6-a31c-53eca7b94265)

## CALCULATIONS:
## LOW_PASS
## HIGH-PASS
## BAND-PASS
## LOW_PASS
## HIGH-PASS
## BAND-PASS
## GRAPH:
## LOW_PASS
![WhatsApp Image 2025-11-27 at 11 40 39_f2b10f65](https://github.com/user-attachments/assets/2b930054-7819-49e5-9c2a-6a129e00cfff)

## HIGH-PASS
![WhatsApp Image 2025-11-27 at 11 41 27_86aefaee](https://github.com/user-attachments/assets/66ebccb4-bf36-42ec-8b27-6027be47d178)

## BAND-PASS
![WhatsApp Image 2025-11-27 at 11 41 53_7520992f](https://github.com/user-attachments/assets/7d5fdbe0-e14e-4477-b0b9-cd5e18bf63eb)

 ## RESULTS:
Thus an Active Low pass, High pass and Band Pass Filters are designed and 
tested using op-amp IC 741. 

