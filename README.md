
# FUNCTION GENERATOR 

In this project , we delve into the design, operation, and 
applications of a frequency generator, highlighting its significance in modern-day engineering and 
scientific endeavors.


## Introduction  
Introduction 
A frequency generator is a crucial device in the field of electronics and signal processing, serving 
as a versatile tool for generating precise and controlled frequencies. With its ability to produce a 
wide range of waveforms, the frequency generator finds applications in various industries, 
including telecommunications, research laboratories, and engineering. This article provides an 
in-depth exploration of frequency generators, highlighting their design, functionality, and 
applications.
## Features
- phase modulation (PM)
- frequency modulation (FM)
- amplitude modulation (AM)
## Block Diagram 
This frequence generator produces three types of waves depending on the input.
- sinusoidal wave
- triangular wave
- square wave
  
![Screenshot 2023-09-12 230406](https://github.com/Ismaeel53/Function_Generator-/assets/127503048/9cf192a8-daf0-448a-b1fa-98d46fce9b84)

## Dual polarity Source:
### Components:

- 7815 regulator IC 
- 7915 regulators IC 
- 2200 uF capacitor 
- 0.1uF capacitor 
- bridge rectifier (using 1n4007)
## AC Source detail 
To generate the required AC voltage for the regulators, the circuit incorporates a bridge rectifier 
and a center-tapped transformer. The bridge rectifier converts the incoming AC voltage from the 
transformer into pulsating DC voltage. This rectification process ensures that both the positive 
and negative halves of the AC waveform are utilized. The center-tapped transformer facilitates 
the dual polarity output by providing two separate windings, one for each regulator, with a 
common center tap. This arrangement allows for the generation of both positive and negative 
voltages simultaneously.
## AC Source Simulation:
![Screenshot 2023-09-12 231803](https://github.com/Ismaeel53/Function_Generator-/assets/127503048/07a174fc-8e18-4702-bddd-f340a030c735)
## Components for function generator:
Following components were used in making the Frequency Generator: 
- 100k Resistor X 10 
- 5.1K resistor X 10 
- LM741 OP AMP X 5 
- 100K potentiometer 
- 1uF Capacitor X 5 
- Diode 1n4732A X 4 
- 1.8K resistor 
- 3.15K resistor 
- 10K resistor  
- 1n4007G diode X 8 
- 10K potentiometer 
- 1k resistor 
- 1k resistor 
- 1n4007 Diode X 4 
- Capacitor 0.1uF X3 
- regulator 7815 
- regulator 7915
## Function Generator Simulation:

![Screenshot 2023-09-12 232454](https://github.com/Ismaeel53/Function_Generator-/assets/127503048/38eba6da-73d7-4abf-8da2-4315f07f7007)
## waves display:

![Screenshot 2023-09-12 232636](https://github.com/Ismaeel53/Function_Generator-/assets/127503048/3bea7b81-0afe-4072-983f-d731855ef237)

![Screenshot 2023-09-12 232650](https://github.com/Ismaeel53/Function_Generator-/assets/127503048/67a6a287-c5d3-45ec-b81c-7d77dbd388a5)

![Screenshot 2023-09-12 232714](https://github.com/Ismaeel53/Function_Generator-/assets/127503048/6b6f29e9-327c-4870-800a-d4c2b78de8e1)

## Final Product:

![Screenshot 2023-09-12 232946](https://github.com/Ismaeel53/Function_Generator-/assets/127503048/e5fcf60e-93ac-48cb-9313-9376f7ac1da6)

