# Yugo-M-controller-project
#### An STM32-based controller for IBM Model M keyboards

Yugo-M is a drop-in replacement for the original PS/2 controller. It connects to PC (or other devices) via USB, and it is programmable. By default it runs [QMK firmware](https://qmk.fm/), but you can flash it with any firmware compatible with STM32 chip, or you can write your own firmware. It is just a simple implementation of the STM32F303 microcontroller. 

## Abstract
IBM Model M keyboards, produced in 80s and early 90s, come with a detachable PS/2 controller board. The PCB is commonly found in one of the following sizes: 170x50mm or 150x38mm. There is no special need to explain reasons to replace the controller which is non-customizable, has high power consumption and connects through obsolete PS/2 interface. Although there are solutions in the form of converters in which the cable is plugged in, a more elegant and similarly priced solution would be to replace the original PCB with an aftermarket one. This would turn Model M into a modern keyboard (minus n-key rollover) with customizable layout. 
I am aware that at least one similar project exists at the moment. I have no intentions to compete with other projects. Yugo-M covers a lower, currently unoccupied price range. In fact, the lack of an existing, relatively affordable solution, made me start this project for my own needs. 

## Variants
* 16pin+12pin
* 16p+8p+4p
* 16p+8p+cable (+5€). Comes with a new cable and LED board. Connector isn't compatible with the original one!
* 16p+8p (SSK)

## Hardware availability
***Note:** Available soon!*\
***Note #2:** Well, it's taking a bit longer than I anticipated. Covid and unusual work schedule are doing their thing. As of 19-Feb-21, the project is still active.*
* On eBay (~40€) [link will be added when I make the listing]
* On Tindie (~40€) [link will be added when I make the listing]
### Shipping
* As a registered letter (5€); 
* Via EMS (23€). 

## Rev 1.1b
* Entering and exiting bootloader mode with one button accessible from the outside;
* Replaces both 170x50 and 150x38mm PCBs;
* 101-key (ANSI), 102-key (ISO) and SSK keyboards supported;
* Optional daughterboards for USB-C and Micro-USB instead of Type B connector. 
## Rev. 0.9b (prototype batch)
* Can replace only larger (170x50mm) board in 101 and 102-key keyboards; 
* Entering bootloader with two buttons; 
* USB B connector. 

## Updates
#### 2021-03-06
* Since STM32F303 MCUs are virtually impossible to get for quite some time, I will be switching to the F103. This will require some more time and testing, and another pull request to QMK. 
#### 2020-10-04
* Firmware is all set up (yay!). As soon as I get and test out the last revision of PCBs (are they easy to solder, do they fit properly etc.) I'll be putting them up for sale and open-sourcing the project. 
#### 2020-09-14
* I intend to open-source the project. Tidying up the schematics and writing the documentation will take some time though. It's a simple design and I have no 'intellectual property' to hide. 
