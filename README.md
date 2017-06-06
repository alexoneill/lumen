# lumen
Capturing the idea of motion in a desktop art piece

### Description 

_lumen_ provides a way for capturing the idea of motion in a desktop art piece. Featuring wooden construction, the project fools the eyes by quickly illuminating parts of complex motion to give the illusion of slow motion.

Using Arduino 101 and RaspberryPi, _lumen_ connects to your Spotify account to react to music playing through your speakers. When music isn't playing, it remains as a decorative piece, displaying the intricacies of motion within.

### Background

Videos are just rapidly changing images. Each frame is shown for a split second, and this gives us the perception of continuous motion capture.

This same effect can be reproduced in a slightly different way. By placing a strobe light above a moving subject, the quick flashes of light effectively produce stationary frames of the motion, much like video.

This project takes this a step further: by using a strobing light, and a vibrating object, the relative frequencies can be precisely tuned to make an object appear to be moving in slow motion.

### Specifications 

###### Hardware 
+ Arduino 101
+ Raspberry Pi
+ White LED Light Strip
+ Fast action linear actuator 
+ 2x MOSFET transistors
+ Wires, resistors, status LEDs, etc.

###### Software
+ Python
+ Spotify API

###### Enclosure
+ Wooden box with lower compartment for electronics 
+ Semi-tinted plexiglass
+ Feather or flower

###### Construction 
The Arduino 101 board controls the light and linear actuator, the RaspberryPi provides access to the Spotify API via a network connection.
