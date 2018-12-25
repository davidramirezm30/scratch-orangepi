# scratch-orangepi: a Python-Scratch handler for the GPIO of the Orange Pi

This is the source of a Orange Pi GPIO handler for Scratch.
It acts as a go-between between Scratch and the GPIO pins and lets you use simple Scratch broadcasts such as "Pin11On"
or "AllOff" to allow you to control LEDs

It understands a number of variable names usch as "set Power11 to 50" which will effectively set Pin11
to half power "set Power12 to 100" will set Pin12 to full power.

it also has support for up to three, cheap, 5 wire unipolar stepper motors and cheap Ultrasonic boards which makes it
very acheivable to program up maze solving robots using Scratch!

The code is being activley developed but the code in this folder is considered stable.  The dev branch contains my day to day
changes.


## Usage
It's based on the Scratch GPIO for Raspberry Pi made by Cymplecy. 
You can find the original repo here https://github.com/cymplecy/scratch_gpio

Install and usuage instructions in this blog http://simplesi.net/scratchgpio/scratch-raspberrypi-gpio/

The code and installer in this folder are a version made only for Orange Pi.


## Issues & Fixes

Please file any issues and feel free to submit pull requests.
