# Smart-classroom
## Introduction 
We are going to made a smart classroom by using Arduino. Our project has 2 parts 
1. Smart lights and fans
2. Fingerprint door lock
We are making this system for reducing the consumption of energy and to reduce the disturbance during class. These are motion sensing lights and fans.
#Software and hardware setup: 
The code is written in arduino. Altra sonic sensor will sense the motion and send this message to the Arduino. Arduino will make decision according to the code. The fans will be on until the person is in the room. When the person left the room the lights will be off automatically.
Hardware installation: 
Arduino  Uno
Ultra sonic sensors hc-sr04*2
Jumper wires
1 channel Relay 
Led display 
100R resistor
4.7k resistor
1k resistor
Bulb holder
220v led bulb
5v 2 2Amp power adapter
Working:
First of all connect sensors with Arduino for input:

1. Connect echo and treg pin of 1st sensor to pin A0 and A1 pin of arduino
2. Connect gnd and vcc pin of sensor to arduino
3. Connect echo and treg pin of 2nd sensor to pin A2 and A2 pin of arduino
4. Connect gnd and vcc pin of sensor to arduino. Now going towards output we have to connect LCD with arduino
5. D4 of LCD to 4th digital pin of Arduino
6. D5 of LCD to 5th digital pin of Arduino
7. D6 of LCD to 6th digital pin of Arduino
8. D7 of LCD to 7th digital pin of Arduino
9. E of LCD to 3rd digital pin of Arduino
10. Rs of LCD to 2nd digital pin of Arduino
11. Ground the following pins of the LCD:
12. A). K!
13. B). RS
14. C). Vss
15. Vcc the following pins:
16. A). A
17. B). VDD
18. C). VO
19. Connections of Relay:
20. IN pin of relay to 8th digital pin of Arduino.
21. vcc to 5v
22. GND to GND
23. COMMON PIN to directly light.
24. NORMAL CLOSE to directly 220v

# Automatic Fan System

## Introduction 
We are going to made a smart classroom by using Arduino. Our project has 2 parts 
1. Smart lights and fans
2. Fingerprint door lock
We are making this system for reducing the consumption of energy and to reduce the disturbance during class. These are motion sensing lights and fans.
## Software and hardware setup: 
The code is written in arduino. Altra sonic sensor will sense the motion and send this message to the Arduino. Arduino will make decision according to the code. The fans will be on until the person is in the room. When the person left the room the fans will be off automatically.
## Hardware installation: 
Arduino  Uno
Ultra sonic sensors hc-sr04*2
Jumper wires
1 channel Relay 
Led display 
100R resistor
4.7k resistor
1k resistor
fan
5v 2 2Amp power adapter
## Working:
First of all connect sensors with Arduino for input:

1. Connect echo and treg pin of 1st sensor to pin A0 and A1 pin of arduino
2. Connect gnd and vcc pin of sensor to arduino
3. Connect echo and treg pin of 2nd sensor to pin A2 and A2 pin of arduino
4. Connect gnd and vcc pin of sensor to arduino. Now going towards output we have to connect LCD with arduino
5. D4 of LCD to 4th digital pin of Arduino
6. D5 of LCD to 5th digital pin of Arduino
7. D6 of LCD to 6th digital pin of Arduino
8. D7 of LCD to 7th digital pin of Arduino
9. E of LCD to 3rd digital pin of Arduino
10. Rs of LCD to 2nd digital pin of Arduino
11. Ground the following pins of the LCD:
12. A). K!
13. B). RS
14. C). Vss
15. Vcc the following pins:
16. A). A
17. B). VDD
18. C). VO
19. Connections of Relay:
20. IN pin of relay to 8th digital pin of Arduino.
21. vcc to 5v
22. GND to GND
23. COMMON PIN to directly Fan.
24. NORMAL CLOSE to directly 220v

# Fingerprint lock System

## Introduction(fingerprint)
This part contain a smart door lock with fingerprint interface. This is an Arduino compatible fingerprint module with the high speed DSP processor. This fingerprint module could work alone without any principal computer or any PC software. It could store 1000 fingerprints. Support fingerprint entry, intelligent image processing, finger print comparison and fingerprint search mode. It also has a high sensitivity to both wet and dry fingerprint recognition.

## Working principal
Fingerprint processing includes two process: fingerprint login process and fingerprint matching process. When fingerprint login each enter two times, will two the second entry image is processed, and the composite template is stored in the module. When the fingerprint is matched through the fingerprint sensor the image to be verified entered and processed then matched with the fingerprint template.

## Devices 
For the implementation of this project we will be using a fingerprint sensor, arduino,breadboard,solenoid door lock, LCD 16x2.

![1](https://user-images.githubusercontent.com/126377361/224907792-fce99310-7563-4f17-90fb-5ce3e621cdd9.png)

![2](https://user-images.githubusercontent.com/126377361/224907967-82bfda62-4135-48d3-acaa-6d4d8ae2d046.png)


![3](https://user-images.githubusercontent.com/126377361/224908090-eb98aede-cbba-41df-8d5f-0e44ce53221c.png)



