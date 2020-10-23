# URU Card PCB

[URU Card](https://github.com/uru-card/uru-card) is an Arduino based FIDO2 Authenticator. This repository contains Eagle CAD design files to build the device.

## Schematic

The schematic for the URU Card is presented on the figure below:

![URU Card schematic](/docs/uru-card-schematics.png)

Components requried to build the device

* ESP32 Pico D4 microcontroller
* ATECC508A or ATECC608A
* MPR121 touch keyboard controller
* SSD1306 based OLED display
* AP2112 voltage regulator
* MicroUSB socket
* A bunch of 0603 resistors and capacitors

## Mainboard PCB

The components are mounted on the mainboard. In fact it's the only PCB required to build the device.

![URU Card mainboard](/docs/uru-card-main-board.jpg)

## Authors

* [**Andrey Ovcharov**](https://github.com/snakeye) - project owner

See also the list of [contributors](https://github.com/uru-card/uru-card/contributors) who participated in this project.

## References

* [Information about URU Card project](https://en.ovcharov.me/category/fido2/)
