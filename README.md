# PROJECT-RGB-ACTIVATON-USING-SENSORS


## AIM
To blink different colors of RGB sensor by the activation of tilt ,push button and IR sensor using ESP8266


## COMPONENTS
1.	ESP8266 NodeMCU
2.	RGB Sensor
3.	Push Button
4.	IR Sensor
5.	Tilt Sensor
6.	Jumper Wire
7.	USB cable


## CONNECTION

### RGB Sensor Module Pin Diagram

![rgb module](https://github.com/JubyJohn/RGB-PUSH-BUTTON-INTERFACING-ESP8266/assets/81866407/7bae2dd7-9795-493a-9625-d78daa90552b)
 

<br>  - = Ground  ---->  GND
         <br> B   ---->  D2
         <br> G   ---->  D1
         <br> R   ---->  D0

### Push Button Pin Diagram

![push-button-module](https://github.com/JubyJohn/RGB-PUSH-BUTTON-INTERFACING-ESP8266/assets/81866407/b68e81e9-fb72-4a2a-a38b-9a1450fa35b7)

 
<br>  S = Output     ---->  D5
<br>  middle  = power supply  ---->  3V3
<br>  –  = ground          ---->  GND

### IR Sensor Module Pin Diagram

![ir-sensor-module](https://github.com/user-attachments/assets/047e9acc-4dee-4692-9691-8e0eb2309687)


<br>  VCC = power supply  ---->  3V3
<br>  GND = ground          ---->  GND
<br>  OUT = Output     ---->  D6

### Tilt Sensor Module Pin Diagram

![Tilt-Sensor](https://github.com/user-attachments/assets/cad802be-06b5-4788-8649-fd8e6f4cab6d)


<br>  G = ground        ---->  GND
<br>  + = power supply  ---->  3V3
<br>  S = Output     ---->  D7

## PROCEDURE

<br> Step 1 : Interface ESP8266 microcontroller to Arduino IDE using port.
<br> Step 2 : Interface ESP8266 microcontroller with push button and print the digital values on serial monitor.
<br> Step 3 : Interface ESP8266 microcontroller with RGB Sensor to blink red,green,blue light with delay.
<br> Step 4 : Interface ESP8266 microcontroller with IR Sensor to detect the obstruction and print the digital values on serial monitor.
<br> Step 5 : Interface ESP8266 microcontroller with Tilt Sensor to sense tilting and print the digital values on serial monitor.
<br> Step 6 : Interface ESP8266 microcontroller with RGB Sensor, IR Sensor, Tilt Sensor and push button by modifying programs.


## OUTPUT

<br> When push button is pressed, red light turned on 
<br> When obstruct detected by IR sensor, green light turned on
<br> When tilting sensed by tilt sensor, blue light turned on


