
# Smart Dustbin

## Abstract
  

The main objective of the project is to design a smart dustbin that will help in keeping our environment clean and also eco-friendly. We are inspired by Swaach Bharat Mission. Nowadays, technologies are getting smarter day-by-day so, to clean the environment we are designing a smart dustbin by using Arduino. This smart dustbin the management system is built on the microcontroller-based system having ultrasonic sensors on the dustbin. If dustbin is not maintained then these can cause an unhealthy environment and can cause pollute that affect our health. In this proposed technology we have designed a smart dustbin using **ARDUINO UNO**, along with ultrasonic sensor, servo motor, and battery jumper wire.

## Components Required

### Hardware :

1. ARDUINO UNO
2. ULTRASONIC SENSOR
3. SERVO MOTOR
4. 9V BATTERY
5. DUSTBIN 
6. JUMPER WIRES 

### Software :

1. ARDUINO IDE 

## 

![Circuit diagram](https://github.com/DevanshuAnand/Smart-Dustbin/blob/master/images/arduino.PNG?raw=true)

##
![Circuit diagram](https://github.com/DevanshuAnand/Smart-Dustbin/blob/master/images/sensor%202.png?raw=true)







## Circuit diagram

![Circuit diagram](https://github.com/DevanshuAnand/Smart-Dustbin/blob/master/images/Copy%20of%20Circuit%20Diagram.PNG?raw=true)



## Working 

After wiring and attaching all the devices and
setting up to the Smart Dustbin, now observe all
the important setup whether they are well
connected or something missed.
After connection set up now next step is to
submit/upload code in Arduino and supply power
to the circuit.
When system is powered ON, Arduino keeps
monitoring for any things that come near the
sensor at give range.
When Ultrasonic sensor detect any object for
example like hand or others, here Arduino
calculates its distance and if it less than a certain
predefines value than servo motor get activate
first and with the support of the extended arm of
the lid.
Lid will open for a given time than it will
automatically close. 

##

![sensor working](https://github.com/DevanshuAnand/Smart-Dustbin/blob/master/images/ultrasonic%20sensor.png?raw=true)






 
  

## Demo

Insert gif or link to demo

https://drive.google.com/file/d/1cHc8EHGjwGDnRLkrbzFHchEN80jYxQ51/view?usp=sharing
## Impact 

1. A reduction in the number of waste
collections needed by up to 80%,
resulting in less manpower, emissions,
fuel use and traffic congestion.
2. A reduction in the number of waste
bins needed.

3. Maintain environment hygiene (i.e. no
overflowing of waste and less
unpleasant odor).

4. It will help in bringing evolution by
technology in term of cleanliness.

## FAQ

#### Question : 1 What is the power source used ?

Answer : A 9 Volt battery can be used a power source.

#### Question 2 : Can we control the distance to which the sensor is sensitive to ?

Answer 2 : The distance can be controlled by changing the dist variable

  