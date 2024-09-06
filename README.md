I decided to play a bit with LG R100 VR glasses before throwing them in garbage. Especially I was interested in STM32F411 from inside.
What I did without any modifications: I could see Samsund Dex on this glasses but I it's only one DP line so lot of artefacts also I used them for some time as second screen for normal work it's ok otherwise lot of lagging.

I even could run Arduino code on internal STM32F411 tries to pull UP all the pins hoping I can activate Video chip or at least turn on backlight but I think
most of the communication is done maybe through i2c not simply pulling up the pin, I was hoping they will die after my experiments but they survived. 

So if someone has more experience in STM and has this glasses maybe we can make small fw that will simply turn on this glasses without need of any usb connection to pc. 

Update 
Some chips that are used: 
Audio max98091
Video TC358870
Backlight SM5306

So everyhing is digital was no sense playing with pins
