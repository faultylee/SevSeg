Fork
----
I'm forking this from https://github.com/sparkfun/SevSeg to add an additional bargraph to be displayed as the 5th Digit. This is to be used by a group of ITB students in their project. Feel free to use the code if you find it useful

Original
--------

This library allows an Arduino to easily display numbers and characters on a 4 digit 7-segment display without a separate 7-segment display controller.
It works for any digital pin arrangement, common anode and common cathode displays. It also has character support including letters A-F and many symbols. 

Hardware Setup
--------------
4 digit 7 segment displays use 12 digital pins. You may need more pins if your display has colons or apostrophes.

There are 4 digit pins and 8 segment pins. Digit pins are connected to the cathodes for common cathode displays, or anodes for common anode displays. 8 pins control the individual segments (seven segments plus the decimal point). 

Connect the four digit pins with four limiting resistors in series to any digital or analog pins. Connect the eight segment pins to any digital or analog pins (no limiting resistors needed). See the SevSeg example for more connection information.

Repository Contents
-------------------

* **/Libraries** - All Arduino libraries and board examples

License Information
-------------------
Original Library by Dean Reading (deanreading@hotmail.com: http://arduino.cc/playground/Main/SevenSegmentLibrary), 2012

Improvements by Nathan Seidle, 2012

All code is open source so please feel free to do anything you want with it; you buy me a beer if you use this and we meet someday ([Beerware license](http://en.wikipedia.org/wiki/Beerware)).
