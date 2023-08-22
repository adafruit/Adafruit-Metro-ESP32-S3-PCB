## Adafruit Metro ESP32-S3 with 16 MB Flash 8MB PSRAM PCB

<a href="http://www.adafruit.com/products/5500"><img src="assets/5500.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Metro ESP32-S3 with 16 MB Flash 8MB PSRAM. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5500

### Description

What's Metro-shaped and has an ESP32-S3 WiFi module? What has a STEMMA QT connector for I2C devices and a Lipoly charger circuit? What has your favorite Espressif WiFi microcontroller and lots of memory for your next IoT project?

That's right - it's the new Adafruit Metro ESP32-S3! With native USB and a load of PSRAM, this board is perfect for use with CircuitPython or Arduino to add low-cost WiFi while retaining shield compatibility.

The ESP32-S3 is a highly-integrated, low-power, 2.4 GHz Wi-Fi/BLE System-on-Chip (SoC) solution that has built-in native USB as well as some other interesting new technologies like Time of Flight distance measurements and AI acceleration. With its state-of-the-art power and RF performance, this SoC is an ideal choice for a wide variety of application scenarios relating to the Internet of Things (IoT), wearable electronics, and smart homes.

The Metro ESP32-S3 has a dual-core 240 MHz chip, so it is comparable to ESP32's dual-core. However, there is no Bluetooth Classic support, only Bluetooth LE. This chip is a great step up from the earlier ESP32-S2! This ESP32-S3 mini-module we are using on the Metro comes with massive 16 MB flash and 8 MB PSRAM, as well as lots of 512KB of SRAM so it's perfect for use with CircuitPython support or any time massive buffers are needed: for fast memory access use SRAM, for slower-but-roomier access use PSRAM. It's also great for use in ESP-IDF or with Arduino support.

Features:

* ESP32-S3 Dual Core 240MHz Tensilica processor - the next generation of ESP32-Sx, with native USB so it can act like a keyboard/mouse, MIDI device, disk drive, etc!
* Mini module has FCC/CE certification and comes with 16 MByte of Flash, 8 MByte PSRAM
* Power options - USB type C or Lipoly battery
* Built-in battery charging when powered over USB-C
* LiPoly battery monitor - MAX17048 chip actively monitors your battery for voltage and state of charge / percentage reporting over I2C
* Reset and DFU (BOOT0) buttons to get into the ROM bootloader (which is a USB serial port so you don't need a separate cable!)
* JTAG 2x5 Header for more intense debugging
* Serial debug output pins (optional, for checking the hardware serial debug console)
* STEMMA QT connector for I2C devices, with switchable power, so you can go into low power mode.
* On/Charge/User LEDs + status NeoPixel with pin-controlled power for low power usage
* Low Power friendly! In deep sleep mode we can get down to ~100uA of current draw from the Lipoly connection. Quiescent current is from the power regulator, ESP32-S3 chip, and Lipoly monitor. Turn off the NeoPixel and external I2C power for the lowest quiescent current draw.
* Works with ESP-IDF, Arduino or CircuitPython 

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
