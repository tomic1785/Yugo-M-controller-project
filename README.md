# Yugo-M-controller-project
#### The STM32-based controller for IBM Model M keyboards

Yugo-M is a drop-in replacement for the original PS/2 controller. It connects to PC (or other devices) via USB, and it is programmable. By default it runs QMK firmware, but you can flash it with any firmware compatible with STM32 chip, or you can write your own firmware. It is just a simple implementation of the STM32F303 microcontroller. 

## Abstract
IBM Model M keyboards, produced in 80s and early 90s, come with a detachable PS/2 controller board. The PCB is commonly found in one of the following sizes: 170x50mm or 150x38mm. There is no special need to explain reasons to replace the controller which is non-customizable, has high power consumption and connects through obsolete PS/2 interface. Although there are solutions in the form of converters in which the cable is plugged in, a more elegant and similarly priced solution would be to replace the original PCB with an aftermarket one. This would turn Model M into a modern keyboard with customizable layout. 
I am aware that at least one similar project exists at the moment. I have no intentions to compete with other projects. Yugo-M covers a lower, currently unoccupied price range. In fact, the lack of an existing, relatively affordable solution, made me start this project for my own needs. 

## Variants
* 16pin+12pin
* 16p+8p+4p
* 16p+8p+cable (+5€). Comes with a new cable and LED board. Connector isn't compatible with the original one!
* 16p+8p (SSK)

## Hardware availability
***Note:** I'm planning to start a small batch production (10-50pcs at a time) as soon as the QMK Configurator is up and running.*
* Directly from me - write me an email at [tomicn8@hotmail.com] (~40€). 
* On eBay (~45€) [link will be added when I make the listing]
### Shipping
* As a registered letter (7,5€); 
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
#### 2020-09-09
* Rev 1.1b prototype is being tested for several days. One-button bootloader/reset is working reliably. It's ready for production. 
* USB-C and Micro USB daughterboards are designed and ready for production. They are yet to be tested (the only concerns are of mechanical nature - sturdiness and fit). 
#### 2020-08-11
* Prototype is fully functional, all initial bugs are resolved, and there is enough parts to assemble 5 of them. I'm going to keep 2 pieces for testing purposes. 
* Rev 1.1b development is underway. Waiting for some parts to arrive. 
