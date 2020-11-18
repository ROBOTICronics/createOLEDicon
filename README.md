## image2cpp ##

Use this tool online at https://www.3agv2004.info/OLEDicons/
This is a simple tool to change images into byte arrays (or your array back into an image) for use with (monochrome) displays suchs as OLEDs, like those from Adafruit or Sparkfun. While searching for a way to generate these arrays, I mostly found links to a piece of Windows software. Both the flakey results and the hassle of having to boot a virtual machine just to convert an image lead to me writing this pure html + javascript solution.

Alternatively you can also enter a byte array as input to turn it back into an image. This might be useful for debugging, or when you want to write the byte array yourself. I don't know.

### Running the tool ###
You don't need any special dependencies / internet connection; all the necessary parts sit in a single .html file. So just open this link page in a (recent) browser to run the tool.

### Example Arduino code ###
You can find a simple Arduino example sketch in the repository.

### Screen types ###
The code works with 128x64 pixel monochrome OLED display, but it should work with most similar displays. You might need to change some export settings; those are explained in the tool.
<!--
### Credit ###
Initial code by [javl](https://github.com/javl), with aditional code by (in alphabetical order) [davidalim](https://github.com/davidalim), [hurricaneJoef](https://github.com/hurricaneJoef), [jochenderwae](https://github.com/jochenderwae), [whoisnian](https://github.com/whoisnian) and [wiredolphin](https://github.com/wiredolphin).
The example sketch is based on code by [Adafruit](https://github.com/adafruit).
-->
