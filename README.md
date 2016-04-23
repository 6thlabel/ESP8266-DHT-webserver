# ESP8266 DHT11/22 Webserver
A simple temprature and humidity webserver.<br /><br />
Connecting the DHT sensor.<br />
Pin 1 vcc<br />
Pin 2 to your DHTPIN on the ESP8266 (in this script pin 2).<br />
Connect pin 1 and pin 2 of the sensor with a 10K resistor.<br />
Pin 3 nothing.<br />
Pin 4 (on the right) of the sensor to GROUND.<br /><br />
Connecting the ESP8266 see below.<br />
Pin 1 to GROUND GND.<br />
Pin 2 GPIO2 to data pin sensor.<br />
Pin 3 Program mode connect to GND in program mode (GPOI0).<br />
Pin 4 Program mode connect to TXD FTDI USB.<br />
Pin 5 Program mode connect to RXD FTDI USB.<br />
Pin 6 CH_PD connect to 3.3volt MAX!!.<br />
Pin 7 Reset not used in this project.<br />
Pin 8 VCC 3.3volt MAX!!.<br /><br />
<img src="http://dblayer.nl/github/ESP-DHT11-webserver/images/ESP-DHT-webserver_bb.png" alt="ESP8266"><br />
<img src="http://dblayer.nl/github/ESP-DHT11-webserver/images/ESP-DHT.jpg" alt="ESP8266">


