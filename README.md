# FIRE-ALARM-SYSTEM-USING-NTC-THERMISTOR-AND-LED-INDICATOR
My first Electronics Project

This project demonstrates a simple and low-cost fire alarm system using an NTC (Negative Temperature Coefficient) thermistor and an LM358 operational amplifier. The system is capable of detecting sudden increases in temperature (like from a fire) and provides an immediate audio-visual alert using a buzzer and an LED.
Overview

The system uses a voltage divider with an NTC thermistor to detect temperature changes. An LM358 op-amp is configured as a comparator to compare the thermistor voltage against a preset threshold set via a potentiometer. When the thermistor senses high temperature, the comparator triggers a buzzer and LED to alert nearby individuals.

Features

    Temperature-based fire detection using NTC thermistor

    Simple analog comparator circuit using LM358

    Audio-visual alert via buzzer and LED

    Adjustable sensitivity via preset potentiometer

    Powered by a 9V battery

Components Used

        NTC Thermistor (10k) :	Temperature sensor
        LM358 :	Dual operational amplifier IC
        Potentiometer (10k) :	For reference voltage adjustment
        Resistors (10k, 220Ω) :	Voltage divider and LED current limiting
        Red LED :	Visual indicator
        Buzzer :	Audio alert
        9V Battery :	Power supply
        Breadboard and wires :	Prototyping hardware

Working Principle

    The NTC thermistor and a fixed resistor form a voltage divider.

    The voltage from this divider is input to the inverting terminal of the LM358 op-amp.

    A reference voltage is set at the non-inverting terminal using a potentiometer.

    When the thermistor detects heat (i.e., resistance drops), the divider voltage decreases.

    Once this voltage drops below the reference, the LM358 output goes high.

    This turns on the buzzer and LED to alert about possible fire.

Physics Behind the Circuit

    NTC Thermistor: Resistance decreases with rising temperature.

    Voltage Divider Rule:
    Vout = Vin × (R2 / (R1 + R2))

    Comparator Logic (LM358):
    If V+ > V−, output = High; else, output = Low.

Future Enhancements

    Use a microcontroller for better control and logic

    Add a GSM module to send SMS alerts

    Integrate with IoT platforms for real-time monitoring

    

My Team Members

We are proud to present this project as part of our team collaboration.

    Muhammad Tarique Saand https://github.com/tarique376
    Mokash Kumar https://github.com/mokashkumar1
    Naveed Narain https://github.com/naveednarain
    Dileep Kumar

