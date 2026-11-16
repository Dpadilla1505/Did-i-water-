# Did-i-water-
*italics*
**bold**

Did i water? is the project i have created to inspire others to 3d model, set up auto simulated watering functions and conponents.

i used a half of a bread board to make all my components work without being overly bulky to hide within or to design around the size.
i start with a photon 2, breadboard and the basic normal of wire colors ( green, blue, black, red ,yellow and white), i was given oopurtintiies to use all these varies features that talk to each other. 
air quality sensor, bme280, o-led display, relay and 5v water pump.


i had to be sure all my installed libraries are installed and included into the code.
#include "Adafruit_SSD1306.h" -- install and include
#include "Adafruit_GFX.h" -- install and include
#include "Adafruit_BME280.h" -- install and include
#include "IoTClassroom_CNM.h" -- install and include
#include "Air_Quality_Sensor.h" -- install and include


sensors and the pins there were using
AIRQUALPIN = A5;
 SOILSENSEPIN = A2;
 RELAYPIN = D16;
 OLED_RESET = -1;
 BME_ADDRESS = 0x76;
 OLED_ADDRESS = 0x3C;


