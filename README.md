# arduino-garage-sensor
Distance sensor with LCD Monitor and green/red LEDs

this project was realized with the following modules:

* Arduino Uno R3
* 2 x 220 Ω resistors
* 1 x green LED
* 1 x red LED
* 1 x 10K Potentiometer
* 1 x LCD Monitor
* ∞ M-M and M-F wires :)

The project is used to carry out a parking maneuver within a limited space. There is a minimum and a maximum distance from the sensor, within this distance the car is parked perfectly.
When the car arrives inside the allowed area, the green light turns on while when you get too close to the sensor, the red light turns on.
Connected to the Arduino there is an LCD monitor that prints the distance value in centimeters.

The project required two libraries:
* ![LiquidCrystal](https://github.com/tatoru1983/arduino-garage-sensor/raw/main/LiquidCrystal.zip) - Managing LCD Monitor
* ![HC-SR04](https://github.com/tatoru1983/arduino-garage-sensor/raw/main/HC-SR04.zip) - Managing Ultrasonic Sensor Module

![Image of the circuit](https://github.com/tatoru1983/arduino-garage-sensor/blob/main/Sensore%20distanza%20garage.png?raw=true)
