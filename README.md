# OpenA1200RTC
OpenA1200RTC is an Open Hardware RTC module for the Amiga 1200 by screwbreaker and Sukkopera : https://github.com/screwbreaker/OpenA1200RTC.

This project is a different layout of the board, with almost the same BOM :
- shorter pin header,
- no jumper to disable the board,
- footprint for CR1220 and wired cell in addition to the CR2032.

# Disclaimer
This is a hobbyist project, it comes with no warranty and no support.

I publish this work using the same license as the original project : "Open Hardware. If you make any modifications to the board, please contribute them back".

If you find it useful, please reward the original authors.

# BOM
- 1x RTC62421
- 1x 2x11 2.0mm pin socket
- 1x 2.2uF 0805 capacitor
- 1x 100nF 0805 capacitor
- 1x BAT721C or BAT54C diodes
- 2x 220 ohm 0805 resistor
- 3x 10k ohm 0805 resistor
- 1x battery holder : CR1220, CR2032 or pin header

# Making it
Make sure that the chip is working before soldering it.

If you plan to use a battery holder, make sure that the RTC62421 is not fully inserted and that its leads and your solder joints do not stick out of the holes in PCB. Thanks to this, the holder will be able to lay flat on the PCB.

Check for shorts at least between 5V and GND traces before applying power !

# Using it
- Install the battery,
- Plug on the motherboard,
- Power on the system.
