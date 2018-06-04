# WaterTankNotifier
This is a project that has to be developed by Sathyabama Coding Club students.

This is their part of In-house projects, Students are encouraged to contribute to the project.

If you find something is not good, please raise a issue or else you can directly contribute to the project by adding a new feature, please do not hesitate to give a pull request or fork the project for our development purposes.

## COMPONENTS USED:
1.) Arduino Uno

2.) 8266 WiFi module

3.) Ultrasonic sensor Module

4.) Scale

5.) Bread board

6.) 9 volt 250mA power adapter

7.) Connecting wires

## ULTRASONIC SENSOR MODULE:
![sku_416860_1](https://user-images.githubusercontent.com/31897267/40416515-1afb1d02-5e9b-11e8-9969-f8051f1fad6c.jpg)

Ultrasonic sensor HC-SR04 is used here to measure the distance of water from the sensor accurately. 
The sensor module consists of ultrasonic transmitter, receiver and the control circuit. The working principle of ultrasonic sensor is as follows:

1.)High level signal is sent for 10us using Trigger.

2.)The module sends eight 40 KHz signals automatically, and then detects whether pulse is received or not.

3.)If the signal is received, then it is through high level. The time of high duration is the time gap between sending and receiving the signal.

              Distance= (Time x Speed of Sound in Air (340 m/s))/2
              
In this case we measure the distance of the water level from the top of the tank and substract it from the total height of the tank to get the water level. 

                 Water level from bottom= (Height of the tank)-(Water level from the top)
                 
## ESP8266 WiFi MODULE:
![fjvfbrrirlqij1o large](https://user-images.githubusercontent.com/31897267/40416816-e598b6c8-5e9b-11e8-8bc3-914d7e52b41d.jpg)

The ESP8266 is a really useful, cheap WiFi module for controlling devices over the Internet. It can work with a micro-controller like the Arduino or it can be programmed to work on its own. We will be using it to upload the water level data to a IoT database

## CIRCUIT:
![iot-arduino-garbage-monitor-circuit](https://user-images.githubusercontent.com/31897267/40417331-2018eb50-5e9d-11e8-91a0-623c8c1cf98d.png)

## CONNECTION:
The circuit will be connected as shown in the circuit diagram and the tank would be monitored using the BLYNK app(https://www.blynk.cc/).
