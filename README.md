## Adafruit ESP32-C6 Feather - STEMMA QT PCB

<a href="http://www.adafruit.com/products/5933"><img src="assets/5933.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit ESP32-C6 Feather - STEMMA QT. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5933

### Description

The ESP32-C6 is Espressif’s first Wi-Fi 6 SoC integrating 2.4 GHz Wi-Fi 6, Bluetooth 5 (LE) and the 802.15.4 protocol. It brings the goodness you know from the low-cost C3 series and improves it with Zigbee/802.15.4 at 2.4Ghz. That means it could make for great Matter development hardware!

We took our Feather ESP32-S2 and swapped out the 'S2 for a C6. Plus some re-routing and here's what we've got: a C6 Feather with lots of GPIO, lipoly charging and monitoring with the MAX17048, NeoPixel, I2C Stemma QT port, and a second low-quiescent LDO for disabling the I2C and NeoPixel when we want ultra-low power usage - as low as 17uA in deep sleep.

One thing to watch for is that, like the C3, the C6 does not have native USB. It does have a 'built in' USB Serial core that can be used for debugging, but it cannot act like a mouse, keyboard, or disk drive. That means if you are running CircuitPython you will need to use WiFi, Bluetooth or WebSerial for transferring files back and forth rather than drag-and-dropping to a drive. Ditto for the bootloader side, this chip cannot run UF2.

Another thing to be aware of, is  the ESP32-C6 does not have as many GPIO as the ESP32-S2 or ESP32-S3, so A2 is the same GPIO pin as IO6 and A3 is the same pin as IO5. However, this gives it the most compatibility with our existing FeatherWings.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
