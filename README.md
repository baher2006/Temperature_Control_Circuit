# Temperature Control Circuit

A temperature control circuit designed and simulated using NI Multisim.

![Temperature Control Circuit](temperature%20control%20circuit.png)

## Project Overview

This project demonstrates a simple temperature-controlled system that detects changes in temperature using an NTC thermistor and controls an output accordingly.

The circuit uses an LM358 operational amplifier as a comparator to compare the temperature-dependent voltage from the NTC thermistor with an adjustable reference voltage.

## Components

- 12V DC Power Supply
- NTC Thermistor
- LM358 Operational Amplifier
- Potentiometer
- MOSFET
- LED
- Resistors

## How It Works

1. The NTC thermistor changes its resistance as the temperature changes.
2. This resistance change produces a change in voltage.
3. The LM358 compares the sensor voltage with a reference voltage set by the potentiometer.
4. When the temperature reaches the selected threshold, the comparator output changes state.
5. The MOSFET controls the output load, while the LED provides a visual indication of the circuit state.

## Simulation

The circuit was designed and tested using NI Multisim.

The temperature behavior of the NTC thermistor was tested at different temperature values to verify the operation of the control circuit.

## Software

- NI Multisim
