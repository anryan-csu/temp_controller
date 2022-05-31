# temp_controller

Pump controller for anything driven by temperature, for arduino uno, supports visual feeeback via RBG LEDs.  Red indicates increasing temperature, blue indicates decreasing.  Cycling RGBs indicate relay active and external unit is operational.  Designed to utilize a relay, but if the external device is low power enough it can be driven from the board directly.

Requires LiquidCrystal.h and EEPROM.h libraries

Pinout is basic (RGB optional)

Relay trigger - A1

Blue - D6

Green - D5

Red - D3

Thermistor - A0

LCD (A1602) - D[7,8,9,10,11,12]

Up Button - D2

Down Button - D4
