KiCad design for a minimal PyBoard
--
Like a PyBoard, but sacks off everything unnecessary, like:

* SD card
* Accelerometer
* Second crystal for the RTC
* User button
* Lots of pin headers
* Most of the LEDs

Wait, so what /is/ included?
--

The bare essentials:

* Microcontroller (STM32F405RGT6)
* USB connector
* 3.3v voltage regulator
* Many caps for power supply conditioning
* Reset button
* 8MHz crystal
* An LED for status

Dependencies
--

Some of the parts used are available from [this KiCad part library](https://github.com/derpston/derplib-kicad) and you'll probably need that to make sense of the schematic or make any changes to it.

