# ATtiny multiboard

A board hosting an ATtiny85 MCU and two potentiometers, typically used as a minimal sound generator.

![ATtiny multiboard](Images/ATtiny_multiboard.jpg)

In this repository you can find the schematic and the production files.

![ATtiny multiboard](Images/ATtiny_GerberView.jpg)

The building is straightforward, the LED will light up accordingly to the output signal.

Since I'm using a PWM output, depending on the board application, a passive low pass filter can be customized by choosing
the values for R and C components,  i.e. a 1K resistor and a 100nF capacitor will lead to a cutoff frequency of 1591.54Hz.

Enjoy.
