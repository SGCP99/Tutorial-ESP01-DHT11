# Tutorial-ESP01-DHT11
How to program an ESP8266-01 using a FT323RL and connect to a DHT11 so you can measure temperature and humidity. 
To download the code using an ESP8266-01 and a FT323RL connect the following pins: 
ESP01 - FT323RL
 3V3  -  VCC
 EN   -  VCC
 RX   -  TX
 TX   -  RX 
 GND  -  GND
 GPO0 -  GND
After you upload the code disconnect the GPO0 from the ground and reset the board by connecting the RST pin from esp01 to the ground and then disconnect it.
The final pins connected should be: 
ESP01 - FT323RL
 3V3  -  VCC
 EN   -  VCC
 RX   -  TX
 TX   -  RX 
 GND  -  GND

The program will make the ESP01 to create a hotspot where the user can connect and see the measurements of the sensor by going to 192.168.4.1 (your IP address).

Source: https://lastminuteengineers.com/esp8266-dht11-dht22-web-server-tutorial/


For the MQTT code you must download the two zip files and search in Arduino IDE the DHT library sensor

Source: https://randomnerdtutorials.com/esp8266-nodemcu-mqtt-publish-dht11-dht22-arduino/

