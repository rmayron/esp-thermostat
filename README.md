This is a ESPHome based thermostat for Home Assistant using: 
 - Arduino D1-Mini
 - BME280 temperature sensor
 - HW-040 encoder module
 - SSD1306 mini display

the thermostat controls an existing switch you should already have configured in Home Assistant and that controls a heater.   You can add a relay to the Arduino if you want an all in one solution.

please note that you may need to reverse the polarity of the encoder module for this work.  I needed to, and this could be due to how the pullup resistors work (or not) in the D1-mini.

Also included are STL files for a box to put it all together.  use glue or tape to mound the components in the box, and drill holes in the box to screw the lead to the box.

Good luck
