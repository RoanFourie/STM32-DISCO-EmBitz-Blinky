Date: 2017-Week-38  
Status: In Progress.  

# Blink the LED when User Button is pressed on the STM32 NUCLEO-F411RE board (STM32F411RET6)  
On startup the Green LED will blink and the Blue one will stay ON. When the User Button is pressed the Green LED will stay on and the Blue LED will blink.  
## Introduction:  
Getting started with the STM32-Discovery board using the free [EmBitz IDE](https://www.embitz.org/) on Windows.  
To blink the LED when the User Button is pressed.  
Based on [this article](./User Manuals/isildak_en.pdf) and used [this article](http://www.firmcodes.com/stm32f407-discovery-gpio-tu) to get it working.  
Flashed firmware hex file using [ST-Link Utility](http://www.st.com/en/development-tools/stsw-link004.html).  

---

## Information about the STM32-Discovery:  
- STM32F100RBT6B microcontroller, 128 KB Flash memory, 8 KB RAM in 64-pin LQFP, 4 to 24Mhz crystal.    
- On-board ST-LINK with selection mode switch to use the kit as a stand-alone ST-LINK (with SWD connector)  
- Designed to be powered by USB or an external supply of 5 V or 3.3 V  
- Can supply target application with 3 V and 5 V  
- Two user LEDs (green and blue)  
    + Green / LD3 / PC9  
    + Blue / LD4 / PC8  
- One user push-button  
    + B1 / PA0  
- JP1 (idd) can be used to measure the current consumption by removing jumper and connecting an Ammeter.  
- Extension header for all QFP64 I/Os for quick connection to prototyping board or easy probing  

---

## Useful Links:  
[ST Microelectronics STM32 ARM MCU Site](http://www.st.com/en/microcontrollers/stm32-32-bit-arm-cortex-mcus.html)  
[STM32 Info](http://www.emcu.it/STM32.html) @ emcu  
[STM32-Discovery Info](http://www.emcu.it/STM32Discovery/STM32ValueLineDiscovery.html) @ emcu  

