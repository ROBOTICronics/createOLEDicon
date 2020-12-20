IoT Icon set 16x16 bi color

Description: 
This icon set with icons of 16x16 pixels was especialy created for low
resolution display which are often used in display enabled IoT projects.
It supports LCD's or OLED Displays.

Each icon will use 32 bytes of microcontroller flash. If you dont want
to waste you programm space, just delete or comment unused icons.

Tested on:	
Used Library: Adafruit_SSD1306

How to use:

#include <Adafruit_GFX.h>

#include <Adafruit_SSD1306.h>

#include "#include "iot_iconset_16x16.h"


// Drawing an icon
display.drawBitmap(0, 34, arrow_down_icon16x16 =, 16, 16, 1);
