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
![IMG20251127112042](https://github.com/user-attachments/assets/0ce87052-77fd-44e3-8232-ce5d88a49ae0)

## HIGH-PASS
![IMG20251127112100](https://github.com/user-attachments/assets/7677fa2b-a37d-4272-8a4c-a84ea10e6b60)

## BAND-PASS
![IMG20251127112117](https://github.com/user-attachments/assets/34a97182-0201-4948-ae04-19ec8fc6fc2b)

## MODEL GRAPH:
## LOW_PASS
![IMG20251127112047](https://github.com/user-attachments/assets/35b1fc81-2f82-432c-ac00-2b078667abe1)

## HIGH-PASS
![IMG20251127112106](https://github.com/user-attachments/assets/5bc8fadc-64d2-4597-90eb-1b37e9ea3515)

## BAND-PASS
![IMG_20251127_112345](https://github.com/user-attachments/assets/47302e2a-4d13-459a-a248-5f8a058e785e)


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
![IMG_20251127_112357](https://github.com/user-attachments/assets/3bc69702-5471-4f25-b1db-5ddf8dbc3f66)

## HIGH-PASS
![IMG20251127112057](https://github.com/user-attachments/assets/515e70ca-c565-4edc-93c7-4bebd829c694)

## BAND-PASS
![IMG_20251127_112332](https://github.com/user-attachments/assets/d78a0ea1-8db8-4e09-b91a-9d5f880e47ac)


## GRAPH:
## LOW_PASS
![IMG20251127112218](https://github.com/user-attachments/assets/74cb1d56-1add-4d2b-8c94-5e263b6fa2ee)

## HIGH-PASS
![IMG20251127112206](https://github.com/user-attachments/assets/b0edca52-79c6-4186-9fcd-12a454b28227)

## BAND-PASS
![IMG20251127112230](https://github.com/user-attachments/assets/ca132232-bd62-4bcc-a1e6-e939fd070987)

 ## RESULTS:
Thus an Active Low pass, High pass and Band Pass Filters are designed and 
tested using op-amp IC 741. 

