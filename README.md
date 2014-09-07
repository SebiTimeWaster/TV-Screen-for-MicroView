# TV Screen for MicroView

## Description
This sketch shows a "random data" animation on the MicroView display so it looks like an old TV screen disconnected from the antenna:
![TV-Screen for MicroView example](https://github.com/SebiTimeWaster/TV-Screen-for-MicroView/blob/master/snow_example.jpg)

## Required Libraries
[MicroView Library](https://github.com/geekammo/MicroView-Arduino-Library/)

## Installation
Open your console and do:

```git clone https://github.com/SebiTimeWaster/TV-Screen-for-MicroView.git```

Now simply open "TV-Screen-for-MicroView.ino" in the Arduino IDE and click upload.

## Create new random data
The random data shown on the display is predefined in PROGMEM (Line 7 in the sketch).

If you want to generate new random data open "create_random_data.html" in your browser, copy everything you see on the website and replace the existing random data in the sketch with your new one. Be aware of the semicolon at the end!
