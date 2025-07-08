## Adafruit Simple Soil Moisture Sensor - For micro:bit, and more PCB

<a href="http://www.adafruit.com/products/6362"><img src="assets/6362.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Simple Soil Moisture Sensor - For micro:bit, and more. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6362

### Description

Perfect for educational uses, the Adafruit Simple Soil Moisture Sensor is low cost, and easy to use. This is a simple resistive style moisture sensor, where there's two prongs and the sensor measures the conductivity between the two. We gold-plated the prongs so reduce risk of oxidation - if you see build-up on the prongs, clean them off with a dish-scrubber to keep the sensor going.

While not as advanced as a capacitive or frequency-based sensor, these are really easy to use! We're stocking this sensor for folks who want to use it with a micro:bit or Arduino or other board with an analog input. It won't work with a Raspberry Pi because those don't have analog inputs - [for that use one of our capacitive sensors](https://www.adafruit.com/product/4026).

Getting started is super easy!

* <b>When using with a micro:bit</b> you'll need some [small alligator clips](https://www.adafruit.com/product/4100).  Connect the GND pad from the 'bit to the GND pad on the sensor. Connect the 3V pad to the 3V pad. Then connect the 0 pad on the 'bit to the OUT pad on the sensor (you can also use 1 or 2 pad on the 'bit). Then, on the micro:bit read the analog value. When soil is dry, the reading will be under 100. As the soil gets wetter it will rise to 1000. 
* <b>On an Arduino</b>, connect 3V to the 3V output pin (or 5V if there's no 3V pin) and GND to ground. You can either use [alligator-clips-to-pins](https://www.adafruit.com/product/3255) or a [JST SH to 3-pin cable](https://www.adafruit.com/product/5755). Then connect the OUT to A0 or another analog input. When you use analogRead() you'll see dry soil at < 100 and wet soil > 600.

Either way, no soldering is required!

Please note: This is just the sensor, you'll also need alligator clips or a JST-SH cable to connect to it! 

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
