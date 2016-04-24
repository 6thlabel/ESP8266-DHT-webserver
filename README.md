# ESP8266 DHT11/22 Webserver
A simple temprature and humidity webserver.<br /><br />
Configure your type DHT sensor and wich data pin you are using on the ESP.<br />
-#define DHTPIN 2     // what digital pin we're connected to<br />
-// Uncomment whatever type you're using!<br />
-#define DHTTYPE DHT11   // DHT 11<br />
-//#define DHTTYPE DHT22   // DHT 22 <br />
<br />
Configure your wifi network here:<br />
-const char* ssid     = "Your-ssid"; // Your ssid<br />
-const char* password = "Your-Password"; // Your Password<br /><br />
Connecting the DHT sensor.<br />
Pin 1 vcc<br />
Pin 2 to your DHTPIN on the ESP8266 (in this script pin 2 GPIO2 on the ESP).<br />
Connect pin 1 and pin 2 of the sensor with a 10K resistor.<br />
Pin 3 nothing.<br />
Pin 4 (on the right) of the sensor to GROUND.<br /><br />
Connecting the ESP8266 see below.<br />
Pin 1 GND to GROUND.<br />
Pin 2 GPIO2 to data pin sensor.<br />
Pin 3 GPIO0 program mode connect to GND in program mode.<br />
Pin 4 RXD program mode connect to TXD FTDI USB.<br />
Pin 5 TXD program mode connect to RXD FTDI USB.<br />
Pin 6 CH_PD connect to 3.3volt MAX!!.<br />
Pin 7 Reset not used in this project.<br />
Pin 8 VCC 3.3volt MAX!!.<br /><br />
<img src="http://dblayer.nl/github/images/ESP-DHT-webserver.png" alt="ESP8266"><br />
<img src="http://dblayer.nl/github/images/ESP-DHT.jpg" alt="ESP8266">


