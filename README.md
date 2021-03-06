# picstick_25k50
PIC18F25K50 Pinguino compatible USB stick

![Top View](https://github.com/kaza007/picstick_25k50/blob/master/picstick_25k50_v1_top.jpg)

Background
------------

The picstick_25k50 is a small PCB that can be connected directly into a USB connector. It is based on the [LeoStick (Arduino Compatible)](http://www.freetronics.com.au/products/leostick#.VWqnws-qpHw) form factor and the hardware is identical to the [PIC18F45K50 Pinguino](http://wiki.pinguino.cc/index.php/PIC18F45K50_Pinguino) except that the 28pin PIC is used instead of the 40pin.

The picstick_25k50 was created to add to the ever growing choice of PIC alternatives to Arduino. There are no surface mount components, so the picstick_25k50 is easy to build.

Pinout
-------

![Pinout](https://github.com/kaza007/picstick_25k50/blob/master/picstick_25k50_v1_pinout.jpg)

[Construction](https://github.com/kaza007/picstick_25k50/blob/master/construction)
--------------

[Schematic](https://github.com/kaza007/picstick_25k50/blob/master/picstick_25k50_v1.sch.png)
----------

PIC Bootloader
-----------------
The PIC18F25K50 must be programmed with the Pinguino Bootloader as described in the Pinguino [Basics](http://wiki.pinguino.cc/index.php/Basics#Bootloader) page.

This project uses Bootloader_v4.14_18f25k50_INTOSC.hex.

Testing
-------
Blinking led test, blink.pde

##
	void setup()
	{  
		pinMode(USERLED, OUTPUT);
	}
 
	void loop()

	{
		toggle(USERLED);
		delay(500);
	}

Design Software
-----------------
This project was designed with [Eagle](http://www.cadsoftusa.com/) 7.2.0, [Sketchup](http://www.sketchup.com/) 15.3.331 and [EagleUp](http://eagleup.wordpress.com) 4.5.

License
-------
![CC-BY-SA Logo](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](<http://creativecommons.org/licenses/by-sa/4.0/).

Original design by: [Pinguino](http://www.pinguino.cc/).

Modified by: [*https://github.com/kaza007*](https://github.com/kaza007)
