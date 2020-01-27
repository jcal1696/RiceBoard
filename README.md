# JISkeyboard
86-key back-lit mechanical keyboard with JIS, ISO, and ANSI layout support; and addressable RGB LEDs.

## UPDATES

### 1/26/2020
I haven't ordered the PCB to be assembled yet, but I will do so in the near future and test it out. Hopefully it'll be compatible with QMK but if not, I can write the code myself.

## Description
I started this project on around January 19th, 2020 since I felt that there wasn't a keyboard PCB that truly suited my desires. I could've gone with something similar, but I felt that making this would both be fun and beneficial (since I'd be familiarizing myself with PCB design through EDA/ECAD software, namely, KiCAD). This is the first time I've designed a PCB, but by following several guides and using many resources found online, I hope I can design something that works, at least.

### Guides
* [ruiqimao's keyboard pcb guide](https://github.com/ruiqimao/keyboard-pcb-guide)
  Great for getting started, doesn't cover a full layout though, but will explain everything from beginning the design to getting it      manufactured
* [Deskthority KiCAD keyboard PCB design guide](https://deskthority.net/wiki/KiCAD_keyboard_PCB_design_guide#Creating_a_keyboard_schematic) 
  Covers designing the schematic with what a full layout looks like
* [wiki.ai03.me PCB Design book](https://wiki.ai03.me/books/pcb-design)
  Great step-by-step keyboard PCB design tutorial with advanced tutorials (from which I learned about backlighting)
* [urushiyama's MJ65-PCB](https://github.com/urushiyama/MJ65-PCB)
  The board I used as a reference
* [Adding a logo to you KiCAD PCB](https://www.re-innovation.co.uk/docs/adding-logo-to-kicad/)
  Pretty self-explanatory'
* [ATMEGA32U4 Datasheet](http://ww1.microchip.com/downloads/en/devicedoc/atmel-7766-8-bit-avr-atmega16u4-32u4_datasheet.pdf)
  Useful for determining pinout configurations, voltage/current ratings, memory size, etc.
  
### Libraries
* [ai03-2725's MX/Alps Hybrid Library](https://github.com/ai03-2725/MX_Alps_Hybrid)
  I modified this to include a 4U-no-LED footprint
* [Hasu's tmk kicad library](https://github.com/tmk/kicad_lib_tmk)
  Includes the ATMEGA32U4 and crystal footprints
