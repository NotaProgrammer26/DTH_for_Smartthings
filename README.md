# DTH_for_Smartthings
Respository for DTH files for Smartthings

Purchased a Gledopto 2ID GL-C-008  and a Gledopto 1D GL-C-007 for use with my RGBWW 4 in 1  LED strips from BTF-Lighting.  Here's my experiences.

 Installed the Gledopto 2ID GL-C-008 and with any DTH the Warm White LED would always stay on at full brightness and could not be adjusted or turned off.  Utilized several different DTH's and none worked.  Removing the Warm White LED from the controller enabled the RGB to function.  (From other postings, it appears that the only way to get control of the Warm White and access the "2ID" was to purchase a Hue Bridge and control the Gledopto with it.)  Since I won't be purchasing a Hue Bridge the Gledopto 2ID GL-C-008 will be utilized to control regular RGB strips without any Warm White LEDs.

 Installed the Gledopto 1ID GL-C-007 and utilized the " ZigBee RGBW Bulb - 2000" Device Handler.
 

Classic Smartthings application
Power Switch turned the LED Strip on and off.    Dimmer adjusted the light level of either white or color.  "Color Control" utilized RGB and turned off the Warm White LED. Selecting any value on the "Color Temperature" resulted in the RGB going to white and going from Warm White to a Cool White and the Warm White LED turning OFF.   Moving the slider from 2100 to 6500 adjusted the white color created by the RGB LED's.  Moving the slider to exactly "2000" resulted in the RGB LED's turning off and the Warm White LED turning on.  A box next to the "Color Temperature" slider named the temperature from 2000 to 6500 as Soft White, Moon Light, Cool White, Daylight.   A box under the Color Temperature is a "refresh" function.  It may be blank.   There were not any slide buttons for Timer, Power On or Power Off.  In summary, the controller utilized the RGB for colors and Cool White OR utilized only the Warm White LED when set to 2000.   This configuration works and was responsive to the controls.

New Smartthings application
Power Switch turned the LED Strip on and off.    Dimmer adjusted the light level.  Color Control utilized RGB and turned off Warm White LED. Selecting any value on the "Color Temperature" resulted in the RGB turning off and the Warm White LED turning on.   Moving the slider from 0K to 100K had no impact on the color.    Two issues occurred.   Sometimes when adjusting the Dimmer or the Color Temperature, an error message appeared.  "A network or server error occurred.  Try again later.  And/or a blue rotating circle appeared for a while and the changes did not take effect.   A slide button for a "Timer" would bring up a screen with Power on/off, after 10, 30 minutes, 1 hour, Custom.  A slide button for Power On would bring up a screen with Set Time and Repeat Every day or individual days of the week. A slide button for Power Off would bring up a similar screen.


Using Alexa
The "Red" command resulted in the RGB LED's making a Red light and similar results for other colors.  The Warm White LED turned off if it was on previously.
The "Cool White" command resulted in the RGB LED's making a Cool White.
The "Warm White" command resulted in the Warm White LED and the RGB LED's making a Warm White.
To achieve a 100% Warm White without the colored RGB LED's required making a New Smartthings Scene.  In the scene, Turn on the LED Strip, Set the Color Temperature to "2000",  and Set the Dimmer to any value.   Then telling Alexa, "Alexa Turn On (the name of the scene)".  Or telling Alexa, "Alexa Run (the name of the scene)".  In my case I named the scene "Real Warm White".  
 Note that the Classic Smartthings Scene adjusted the color temperature with a slider that only went to a low of 2700K and would not allow a setting of "2000" which is required to turn off the RGB LEDs and turn on only the Warm White LED, while the New Smartthings Scene allowed any value such as "2000" to be typed into the setting.

In summary, the Gledopto 1ID GL-C-007, the Classic Smartthings and the DTH  -  "ZigBee RGBW Bulb - 2000"  provides great colors and an option for 100% Warm White without any RGB colors.  This combination works well with Alexa and Action Tiles.   Many thanks to "
benerkens    From <https://community.smartthings.com/t/gledopto-zigbee-rgb-controller/125394/136>     for his update to the DTH. 




DTH  -  "ZigBee RGBW Bulb - 2000"  
https://github.com/NotaProgrammer26/DTH_for_Smartthings/blob/master/RGB_DTH.txt

BTF-LIGHTING 16.4ft 5M 5050 RGBWW 4 in 1 RGB+Warm Whtie STRI Mixed Color 60leds/m IP30 Non-Waterproof 300LEDs Ribbon Lamps Multi-Colored LED Tape Lights 
by BTF-LIGHTING    From https://www.amazon.com/gp/product/B01D1I50UW/ref=ppx_yo_dt_b_asin_title_o02_s00?ie=UTF8&psc=1> 


