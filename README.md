# h's homemade Motion Control: the Mac app / server

##Introduction

This is the code for a Mac app, written in Swift, that acts as a motion control server. With the appropriate hardware 
(see below) and with wind in just the right direction, a fully functioning robotic camera motion control system may
seem to work. Appearances may be deceptive.

To see it working, watch this: https://www.youtube.com/watch?v=rWuKmWKicro

Firmwares for the various axes:
* Teensy LC / Stepper motor:  https://github.com/howiemnet/h-moco-STEPPER-Teensy
* Teensy LC / DC Servo motor:  https://github.com/howiemnet/h-moco-DCSERVO-Teensy
* Arduino / Canon Lens AF:   https://github.com/howiemnet/h-moco-LENS-Arduino

Blender project coming soon (it's equally horrifying), but until then:

* Example python code for generating a CSV animation file from Blender: https://gist.github.com/howiemnet/8f617ff7b4845161fe7ebeb64ceba5dd

##Warnings

This code contains approximately 7 bugs per line of code. I will not be offering support or help in understanding
what the hell is going on beyond what I can get written up for my blog, but I will update this as frequently as life permits. Individual support requests may be met with stoney silence, for which I apologise in advance. It's just too big and complex a project: it relies 
on not just this app working correctly, but the right hardware wiring up, and the appropriate firmware running on
the various microcontrollers involved.

That said, it's my intention to try and tidy this up and document it well enough that the project will be reproducable, in the 
hope that others may be able to hack together motion control systems without having to re-invent these wheels.


![Screenshot](http://i.imgur.com/SI0pRMs.png)

A lot more documentation will come: this is just the first commit to get it all up there - feel free to poke around and laugh
at my appalling coding style.

:)

h 17/7/2016

