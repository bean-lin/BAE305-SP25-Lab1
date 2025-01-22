# Lab report 1: Knowing Your Instruments

* Benjamin Lin
* Avis Chen

  02/03/2025

I reread the lab instructions, the report needs to be in the wiki, not the readme. I copied everything over for now, I'll put any future work there. -Avis

# Lab Summary
The goal of this lab is to understand how to utilize several electronic testing instruments that will be used in future experiments. In this lab, we tested xyz with abc
# Methods/Tests: 
Engineering documentation necessary to repeat the project. Should include:
Drawings
Pictures
# Results: Data or outcome from the work. 
Should include:
Tables

**1)**

| Color Code  | Expected Resistance (&Omega;) |  Maximum Value (&Omega;) |  Minimum Value (&Omega;) |   Measured Resistance (&Omega;) | 
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Yellow, Violet, Green, Gold  | 4,700,000  | 4935000  | 4465000 |4,758,000  |
| Brown, Green, Black, Gold | 15  | 15.75  | 14.25  | 19.4  |
| Brown, Gray, Brown, Gold  | 180  | 189  | 171  | 185.2  |
| Gray, Red, Red, Gold  | 8,200  | 8,610  | 7,790  | 8,250  |

Calculated the minimum and maximum values by using the following equations 

$$V_{max} = V * (1+tolerance)$$ and $$V_{min} = V * (1-tolerance)$$

**2)**

| Code  | Expected Capacitance |  Maximum Value |  Minimum Value |   Measured Capacitance | 
| ------------- | ------------- | ------------- | ------------- | ------------- |
| 22j | 22.0pF | 23.1pF | 20.9pF | 0.30nf |
| 105Z | 1.00uF | - | - | 1.19uF |
| 102 | 1.00nF | - | - | 1.30nF |
| 470uF | 470uF | - | - | 522uF |

Note: Minimum DMM measurement is 300pF

b. Polarity did **NOT** impact the reading of the electrolytic capacitor becuase it is a passive component.

Drawings
Pictures

**3)**

| Voltage | Minimum Current | Measured Voltage |
| ---- | ---- | ---- |
| 1.5V | 250mA | 1.484V - 1.521V |
| 7V | 250mA | 6.99V - 7.01V |
| 12V | 250mA | 11.98V - 12.01V |
| Aux 3.3VDC | N/A | 3.416V |
| AUX 5.0VDC | N/A | 5.214V |
| AUX 12VDC | N/A | 12.06V |

Note: Auxillary ports use less than 0.1A, so current not measured

**4)**
| Measurement Method | Amplitude | Frequency |
| ---- | ---- | ---- |
| Counting Squares | $$4_{squares} * 5V/_{square} = 20V$$ | $$F = 1/T = 1/(5_{squares} * 100us/_{square} * 10^{-6} us/s) = $$  |
| Cursor | &Delta;V = 20.4 | &Delta;t 484us |
| Measurement | 20.40V | 2.092khz |
| Fluke DMM | 7.16V | 2.092khz |

Multimeter uses RMS, O-Scope measures peak to peak &Delta;T

$$f = 1/T$$

# Discussion: 
What you can learn from the results obtained. Should include:
Answers to proposed questions.

Discussion Question 1: Do the instruments (power supply, DMM) agree with each other? Why?

Discussion Question 2: Do the instruments (osciloscope, DMM) agree? Why?

# Conclusion: 
Most important things derived/learned from the lab and report (one or two paragraphs).
