# Smart Irrigation and Water Management System with GSM Alert

## Project Overview

The Smart Irrigation and Water Management System with GSM Alert is an embedded systems project developed using the ARM7 LPC2129 microcontroller. The system continuously monitors soil moisture conditions and sends SMS notifications to the user through a GSM module. Based on the received alerts, the user can remotely control the irrigation motor using SMS commands.

This system helps optimize water usage, reduce manual intervention, and improve irrigation efficiency in agricultural fields.

## Components Used

### Hardware Components

* ARM7 LPC2129 Microcontroller
* GSM Module (SIM900)
* Soil Moisture Sensor
* DC Water Pump / Motor
* Relay Driver Circuit
* 16x2 LCD Display
* Power Supply Unit

### Software Tools

* Embedded C
* Keil uVision
* Flash Magic

## Features

* Real-time soil moisture monitoring
* GSM-based SMS alerts
* Remote motor control through SMS
* LCD status display
* Water conservation support
* Low-cost agricultural automation

## Working Principle

1. The soil moisture sensor continuously monitors soil conditions.
2. When dry soil is detected, the system sends an SMS alert to the user.
3. The user can send the command **'a'** to start the irrigation motor.
4. The motor pumps water to the field.
5. When the soil becomes wet, the system sends another SMS alert.
6. The user can send the command **'b'** to stop the motor.
7. All system statuses are displayed on the LCD.

## Applications

* Smart Agriculture
* Automated Irrigation Systems
* Water Management Systems
* Greenhouse Monitoring
* Precision Farming

## Future Enhancements

* Automatic motor control without user intervention
* IoT-based cloud monitoring
* Mobile application integration
* Moisture percentage display using ADC
* Solar-powered operation

## Author

Ramya M

Embedded Systems Project
