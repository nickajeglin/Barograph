# Barograph

![img](https://i.imgur.com/1cs167Q.jpg)

Portable arduino powered barograph that displays a 48 hr chart of pressure data, pressure change per hour, and an icon to indicate pressure delta. 

# Notes

Verify the pin numbers on your arduino. I used a slightly different version that was distributed through a university eng. supply shop. 
You can use the "pro trinket li-poly backpack" on MC's that aren't an adafruit trinket, just read through the datasheet for it, and you'll figure it out pretty quick. Shoot me a message if you get stuck

![disgustingfritzing](https://i.imgur.com/kJpeg8j.png)
NOTE: there's now a visual warning indicator if the pressure is crashing. Add a LED and appropriate resistor from arduino pin D7 to GND, and it will blink to warn you if pressure is falling faster than 116 Pa/h and will blink rapidly to warn you if it's faster than 200 Pa/h. That way if you have the backlight off to save battery, you'll still get a warning indication if the baromter is plummeting. 
