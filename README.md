# 4-Bit-R2R-Resistor-Ladder-DAC
This 4-Bit R2R Resistor Ladder DAC Converter creates a circuit where you can create a analog signal using 4 digital outputs. Using a 5 volt system the maximum output voltage is 4.6875 V. This circuit uses multiple resistor voltage dividers to create "in-between" signals not possibly achieved by a digital output from a microcontroller. This particular circuit uses 1k ohm resistors.

The accompanying arduino IDE code creates a blocked triangle wave at approximately 490Hz. Using a 0.1uF capacitor, the signal is smoothed out into a smooth triangle wave. Using a 1uF capacitor, the wave is further smoothed out to represent a sine wave, however the maximum voltage is reduced to approximately 3 volts and the minimum voltage to approximately 1.8 volts.
