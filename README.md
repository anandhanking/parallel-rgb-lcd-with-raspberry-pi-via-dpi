# parallel-rgb-lcd-with-raspberry-pi-via-dpi /rgb565,rgb565-padhi,rgb888

you can find the best tutorials about the config of parallel rgb lcd to raspberry pi via DPI.
this config files presented here are only works with the same named pinouts.
  example:: rgb565 config file only suits for rgb565 lcd connections.

i have tested the RGB565 and RGB565-padhi with the following lcd displays
  1. tianma-panel-tm070rdh13-40
  2. 4.3inch 480x272 res. display. (i don't have it's name or item number.)

i have tested the RGB888 with the following lcd display
  1. 4.3inch 480x272 res. display. (i don't have it's name or item number.)

all the lcd connections are can be found on lcd_connections folder/lcd_connections.txt file.

also the hsync,vsync parameters given in config files are taken from the lcd's datasheet. 
please refer datasheet of your own lcd and change the values as per datasheet.
because i tried the values on internet, but the display not worked well. the border pixels are cut off.
so use your datasheet values for lcd control configs.
