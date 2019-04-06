# MicroPython-ST7735

This is a modified version of [BooChow's](https://github.com/boochow/MicroPython-ST7735) ST7735 TFT LCD driver for MicroPython.

This version is for TTGO-TS v1.4.

A font file is necessary for displaying text (some font files are in [GuyCarver's repo](https://github.com/GuyCarver/MicroPython/tree/master/lib)).

tft_test.py is a sample code. I just modified for few lines. 


Pin connections:

LCD |TTGO-TS-v1.4
----|----
RST |IO09
A0  |IO16(DC)
SDA |IO23(MOSI)
SCK |IO05(CLK)
CS  |IO17

[TTGO-TS Pinout](https://github.com/LilyGO/TTGO-TS/blob/master/Image/T10_V1.4.jpg)

[Video](https://www.youtube.com/watch?v=XfCYlbe2Oko)

[Font converter](https://github.com/littlevgl/lv_utils)
[Online Font converter](https://littlevgl.com/ttf-font-to-c-array)

16 pixels height, 1 bit-per-pixel.
I use this Simsun.ttc for building Chinese characters.
