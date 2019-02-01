
# Getting Started with Adafruit IO Arduino

Adafruit IO Python makes it simple to get your Arduino project's data into the best data system in the world - [Adafruit IO](http://io.adafruit.com). 

Using [Adafruit IO Arduino](https://github.com/adafruit/Adafruit_IO_Arduino/) - you can send *any* data from an Arduino sketch to Adafruit IO. You can also retrieve data from Adafruit IO feeds into an Arduino Sketch. 

# Hardware Compatibility 
This library officially supports the following Adafruit hardware:
* [Adafruit Feather Huzzah ESP8266](https://www.adafruit.com/product/3046)
* [Adafruit Feather Huzzah ESP32](https://www.adafruit.com/product/3591)
* [Adafruit Feather M0 WiFi](https://www.adafruit.com/product/3010)
* [Adafruit 32u4 FONA](https://www.adafruit.com/product/3027)
* [Adafruit Ethernet Featherwing](https://www.adafruit.com/product/3201)

# Installing Adafruit IO Arduino

Before we start, you'll need the latest version of the [Arduino IDE](https://arduino.cc) installed and the latest board support packages for your hardware. 

From the Arduino IDE, navigate to the  **Manage Libraries...**  option in the  **Sketch -> Include Library** menu.
![managelibraries](https://cdn-learn.adafruit.com/assets/assets/000/034/832/medium640/adafruit_io_library_menu.png?1471361448)

Adafruit IO Arduino requires three Arduino libraries:
* [Adafruit MQTT Library](https://github.com/adafruit/Adafruit_MQTT_Library)
* [ArduinoHTTPClient](https://github.com/arduino-libraries/ArduinoHttpClient)
* [Adafruit IO Arduino](https://github.com/adafruit/Adafruit_IO_Arduino)

Let's start by installing the Adafruit MQTT Library. Enter  **Adafruit MQTT**  into the search box, and click  **Install**  on the  **Adafruit MQTT**  library option to install version 0.16.1 or higher.
![installmqttlibrary](https://cdn-learn.adafruit.com/assets/assets/000/034/835/medium640/adafruit_io_mqtt_install.png?1471362345)

Enter  **ArduinoHttpClient**  into the search box, and click  **Install**  on the  **ArduinoHttpClient**  library option to install version 0.2.0 or higher.
![installarduinohttp](https://cdn-learn.adafruit.com/assets/assets/000/040/456/medium640/adafruit_io_arduinohttpclient.png?1490653043)

Enter  **Adafruit IO Arduino**  into the search box, and click  **Install**  on the  **Adafruit IO Arduino**  library option to install version 2.7.3 or later.
![installaioarduino](https://cdn-learn.adafruit.com/assets/assets/000/034/834/medium640/adafruit_io_lib_search.png?1471361923)

 
# Your First Adafruit IO Arduino Sketch

## 1) Grab the Adafruit IO Key
Before we begin using Adafruit IO Arduino, we'll need to grab two important things: our **Adafruit IO Username** and our unique **Adafruit IO Key**.

[Navigate to your profile](http://io.adafruit.com) and **click the *View AIO Key* button** to retrieve them. Write them down in a safe place, we'll need them for later.
![aio-key](https://i.imgur.com/BnZZcYM.gif)

## 2) Load the example sketch
From the Arduino IDE, navigate to the  adafruitio_00_publish*  sketch by opening the  **File -> Examples -> Adafruit IO Arduino**  menu and clicking on **adafruitio_00_publish**.
![select-publish-sketch](https://cdn-learn.adafruit.com/assets/assets/000/034/838/medium640/adafruit_io_select_example.png?1471364050)

Click on the  **config.h**  tab, and replace the placeholders with your Adafruit IO credentials and network connection info.
![io-info](https://cdn-learn.adafruit.com/assets/assets/000/070/493/original/adafruit_io_wifi_creds.png?1549054094)

### 3) Upload to the Arduino

Now that everything's set up, save your sketch and upload it (**CTRL/CMD+U**) to the Arduino.

*BUT* - where's our data? [Follow this guide to view your data on the Adafruit IO Website](https://learn.adafruit.com/adafruit-io-basics-esp8266-arduino/example-sketches#viewing-data-on-adafruit-io-6-16).

# More Examples
Need more examples for using Adafruit IO Arduino with a servo, reading data from a sensor, lighting up NeoPixels and more? Head over to the [*Adafruit IO Basics Series* on the Adafruit Learning System](https://learn.adafruit.com/series/adafruit-io-basics). 

 # Learning Guides and Resources
[The Adafruit Learning System has lots of Adafruit IO guides to inspire your next project!](https://learn.adafruit.com/category/adafruit-io)