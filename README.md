# Adafruits_glcdfont_chars
Adafruit's glcdfont.c characters
Printing all characters of Adafruit's GFX library (https://github.com/adafruit/Adafruit-GFX-Library/blob/master/glcdfont.c)
using this code:
for(byte x=0; x<255; x++) {
    tft.print((char)x);
  }

![](/IMG_20200222_053426.jpg)

note that char #10 is "\n" or newline character.
and char #13 is "\r" or carriage return. which both of them do not print anything but should counted.
now for example if you want to print up-arrow symbol:

tft.print((char)24);
