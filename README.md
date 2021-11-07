# Anarchist FAQ earrings!

This project was made by me in about 10 hours (using a modified ESP8266WebServer template), feel free to make your own! (it will probably take 0.5h-2h to make)

Some files didn't fit into the 3MB of flash, so if you know how to fit them in - a PR would be awesome! Oh and if you have any suggestions or improvements, don't hesitate to open an issue or a PR as well!

## Requirements

You'll require a NodeMCU (or some other ESP8266-based thing), a way to power it, Arduino IDE set up for the ESP8266 thing, and [this](https://github.com/earlephilhower/arduino-esp8266littlefs-plugin) LittleFS plugin installed.

## Making instructions

1. In ```Arduino IDE>Tools>Flash Size``` choose the 3MB flash size option.
2. Compile and flash the sketch onto your board.
3. Run ```Arduino IDE>Tools>ESP8266 LittleFS Data Upload``` to upload the contents of the data folder to the flash.

Now the code part should be good to go.

4. Verify that everything works as you want it to.
5. Unplug the cable from your board.
6. Connect your board to the external battery (I just soldered two AAA batteries in series to the VIN and GND of my NodeMCU)
7. You're done!~ Now put it on a hook and wear it with style!
