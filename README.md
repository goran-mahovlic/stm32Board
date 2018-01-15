#Mini fabrikator v2 pcb

This printer is also know as Malyan M100
This is board schematics from printer I have at home.

You can read more about it at this link:
http://www.lemilica.com/reversing-mini-fabrikator-v2-malyan-m100-3d-printer/

On bluepill I have tested connection to ESP8266 and all is working.
All sensors when not connected shows about 100 degrees, that is probably OK.
I have connected SD card to it, and with original bootloader 
I can flash some code on bluepill.
I can send GCODE to SD card.

I can now compile Marlin firmware for M200

I did solve serial issue and working serial branch is now here

https://github.com/marvin-sinister/Marlin/tree/radiona-2.0.x

I did not try this code on priter, so be carefull ...

One problem still remains, fox Z axis M100 uses ULN2003 so fot Z you need write some step direction function.

If you realy think you need bootloader, you can contact me over email

goran.mahovlic@gmail.com
