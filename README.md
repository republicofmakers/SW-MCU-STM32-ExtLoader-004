# SW-MCU-STM32-ExtLoader-004


Here is a project file to create external loader for STM32 microcontrollers.

It is an flash (W25Q64) and it is connected to stm32h743 via QSPI.
You can edit the code and can create your external loader.

1.) import all the code as usual

2.) edit linker file to new linker file from settings

3.) compile the code

4.) rename the created file .elf (under debug folder) and change its ending to .stldr

5.) Put related folder of stm32 cube programmer and test your external loater flash.



Hope this helps you,

Ceyhun Pempeci STM32 Blink
