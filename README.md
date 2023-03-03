# Hatch2023Trophy

Overview of the trophies created for the HATCH 2023 Winners

Thanks for visiting this page to learn more about your HATCH trophy!

View my YouTube video for a quick overview and demo:  This video was made for the 2022 Trophy, but is nearly identical.  
https://youtu.be/y4QBiJtTjaM

The trophy uses open source code and hardware, so please hack it to make it do what you want. It comes loaded with some demo code to test each of the components.

There may be updates to this page, but if you have any questions or comments, please initiate a "Issue" on github, and I will answer as soon as I can.

With the demo code loaded, the trophy will boot to the 'menu' screen.
Press the main button scroll through the menu.
When you go into the 'Demo Mode' Function, the program will loop forever. To exit the loop, just press the reset button.

The following functions are loaded with the demo software:
Lite Sense (view the analog signal from the light sensor. Minimum is ~888 (dark) and Maximum is ~1000 (very very bright))
Demo Mode (scrolls through all features, sensors, and animations)

The trophies feature the following major components:
ATTINY-85 Microcontroller
128x32 Pixel OLED display
Neopixel (WS2812v3) RGB LEDs
Light Sensor
18650 Battery, along with charging circuit (micro USB)
Pinout for all 8 pins on the microcontroller, so you can program it or add other features.

How to set up Arduino:
https://www.arduino.cc/en/Guide/ArduinoUno

How to Program the trophy (Arduino as ISP):
The trophy contains an ATTINY85 Microcontroller and can be programed unsing an arduino board, like the arduino uno.  
https://create.arduino.cc/projecthub/arjun/programming-attiny85-with-arduino-uno-afb829

Pinout for the ATTINY-85 eight-pin breakout:
-----------
| 1 2 3 4 |
| 5 6 7 8 |
-----------
PINs 1,2,3,5,6,7 are used for uploading code via ISCP to the ATTINY-85

1 - 
2 - 
3 - 
4 - 
5 - 
6 - 
7 - 
8 - 

It may be possible to program the trophy using a micro USB cable and the Micronucleus bootloader.  I have included the circuitry for that, but haven't tried to configure it.  It seems like most modern computers have trouble with it.  But if you want that functionality, give it a try!  For advanced users only.
