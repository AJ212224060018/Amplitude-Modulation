# EXP NO: 1 GENERATION AND DETECTION OF AM

### Aim:

To generate and detect the amplitude modulation and demodulation u s i n g S C I L A B and to calculate modulation index of AM.

### EQUIPMENTS REQUIRED:

• Computer with i3 Processor

• SCI LAB

### THEORY:

Modulation can be defined as the process by which the characteristics of carrier wave are varied in accordance with the modulating wave (signal). Modulation is performed in a transmitter by a circuit called a modulator. Need for modulation is as follows: • Avoid mixing of signals • Reduction in antenna height • long distance communication • Multiplexing • Improve the quality of reception • Ease of radiation. Amplitude Modulation is the process of changing the amplitude of a relatively high frequency carrier signal in proportion with the instantaneous value of the modulating signal. The output waveform contains all the frequencies that make up the AM signal and is used to transport the information through the system. Therefore the shape of the modulated wave is called the AM envelope. With no modulating signal the output waveform is simply the carrier signal. Coefficient of modulation is a term used to describe the amount of amplitude change present in an AM waveform. There are three degrees of modulation available based on value of modulation index.

Under modulation : m<1, Em < Ec
Critical modulation: m-1, Em = Ec
Over modulation: m>1, Em > Ec
Note: Keep all the switch faults in off position

### Algorithm:

Define Parameters First, define the parameters for your signals: • Carrier frequency (fc) • Modulating signal frequency (fm) • Sampling frequency (Fs) • Duration of the signal (T)

Create a time vector based on the sampling frequency and duration.

Create Modulating Signal Define the modulating signal (message signal).

Create Carrier Signal Define the carrier signal.

Perform Amplitude Modulation Multiply the carrier signal by the modulating signal plus 1 (to ensure the modulation depth).

Plot the Signals Visualize the modulating, carrier, and modulated signals.

Demodulate the AM Signal To demodulate, you can use envelope detection. One way is to rectify the signal and then apply a low-pass filter.

Plot the Demodulated Signal Visualize the demodulated signal.

Compare Signals Compare the original modulating signal with the demodulated signal. PROCEDURE • Refer Algorithms and write code for the experiment. • Open SCILAB in System • Type your code in New Editor • Save the file • Execute the code • If any Error, correct it in code and execute again • Verify the generated waveform using Tabulation and Model Waveform

### Program:

~~~
~~~

### Output Waveform:
### Tabulation:
### Calculation:

### . ma (Theory) = am/ac = 0.5
### . ma(Practical) = (Emax-Emin)/(Emax+Emin) = 0.5048

### Model Graph:

### Result:
Thus the amplitude modulation and demodulation is experimentally done and the output is verified.
####
