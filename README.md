# Lutron RadioRA 
Hubitat Lutron RadioRa Integration

There are three Hubitat Drivers that you need to installed.
- Lutron Shield 
- Lutron RA Switch
- Lutron RA Dimmer
  
These need to be added to your Hubitat Hub's Drivers section.  Edit the device type of your ThingShield device to be Lutron Shield.

There is the "Arduino Sketch", that installs on Arduino Mega 2560.

You will also need to add the "SmartThings" folder in this repository to your Arduino Libraries folder on your computer.  This is a new version that is required for use with Hubitat. 

There is the Lutron Gateway SmartApp, that you install in the Hubitat Hub's Apps section.

The required hardware consists of -
- Lutron RadioRA RA-RS232, 
- Arduino Mega 2560, with, 
- SmartThings ThingShield, and
- Arduino RS232 shield.

The Arduino RS232 shield connects to the RA-RS232 with null modem cable.
- There must be jumpers from pins 2,3,4,5 to pins 14,15,16,17 on the Mega.
