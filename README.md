# ESP8266-4channel-PWM-receiver
A WiFi receiver used to control quadcopters. It currently is coded for 4 channel output but can go to 8 or even beyond. This receiver was tested on YMFC AL Arduino Uno quadcopter as a replacement for a Fly Sky receiver. Code requires Arduino IDE ESP8266 core to be added.

Enter https://arduino.esp8266.com/stable/package_esp8266com_index.json into the File>Preferences>Additional Boards Manager URLs field of the Arduino IDE. You can add multiple URLs, separating them with commas.

Tested on ESP8266 12f, 12e , and Nodemcu development board.

the project is based on WifiPPM project and changed to give PWM signals- https://www.instructables.com/Wifi-PPM-no-App-Needed/

*Access point details* :-

SSID: WifiPPM

password: Wifi_PPM

*PWM Channel Mapping*:-

ch1 -> D4 - GPIO 2

ch2 -> D3 - GPIO 0

ch3 -> D1 - GPIO 5

ch4 -> D2 - GPIO 4

Access Point first test WiFi PWM receiver using smart phone - https://youtu.be/eeE180ZjaME  
Tested on YMFC AL Arduino Uno quadcopter - https://youtu.be/MMIb9IrTuvA
