# Yugo-M-controller-project
The STM32-based controller for IBM Model M keyboards

Yugo-M is a drop-in replacement for the original PS/2 controller. It connects to PC (or other devices) via USB, and it is programmable. By default it runs QMK firmware, but you can flash it with any firmware compatible with STM32 chip, or you can write your own firmware. 

## Abstract
IBM Model M keyboards, produced in 80s and early 90s, come with a detachable PS/2 controller board. The PCB is commonly found in one of the following sizes: 170x50mm or 150x38mm. There is no special need to explain reasons to replace the controller which is non-customizable, has high power consumption and has a tendency to fail with age. Although there are solutions in the form of converters in which the cable is plugged in, a more elegant and similarly priced solution would be to replace the original PCB with an aftermarket one. This would turn Model M into a modern keyboard with customizable layout. 
I am aware that at least one similar project exists. It's a more sophisticated and higher-priced product than Yugo-M. I have no intentions to compete with it; Yugo-M is occupying a lower price range. In fact, the lack of an existing, relatively affordable, solution made me start this project for my own needs. 


## Rev. 0.9b
* Can replace only larger (170x50mm) board in 101 and 102-key keyboards; 
* Entering bootloader with two buttons; 
* USB B connector. 
## Rev 1.1b (work in progress)
* Replaces both 170x50 and 150x38mm PCBs;
* 101-key (ANSI), 102-key (ISO) and SSK(needs verification!) keyboards supported
* ...

## Availability
* Directly from me - write me an email at [add address] ($45). 
* On eBay ($49) [add link]
### Shipping
* As a registered letter ($8); 
* Via EMS ($26). 
