

# STM32F401 WITH Auto Boot Mode 
!["STM32F401"](https://github.com/tingliwong/ZM-Micro-Board-STM32F4/blob/master/images/STM32F401CEU6-V1.JPG)
<!-- PROJECT LOGO -->
<br />


* [Introduction](https://github.com/tingliwong/ZM-Micro-Board-STM32F4#Introduction)<br>
* [Getting Started](https://github.com/tingliwong/ZM-Micro-Board-STM32F4#getting-started)<br>
* [Troubleshooting](https://github.com/tingliwong/ZM-Micro-Board-STM32F4#troubleshooting)<br>
* [Wiki](https://github.com/stm32duino/wiki/wiki/)

## Introduction

This repo adds the support of STM32F401CxU6 MCU in Arduino IDE.<br>

This porting is based on:
* [STM32Cube MCU Packages](https://www.st.com/en/embedded-software/stm32cube-mcu-packages.html) including:
    * The HAL hardware abstraction layer, enabling portability between different STM32 devices via standardized API calls
    * The Low-Layer (LL) APIs, a light-weight, optimized, expert oriented set of APIs designed for both performance and runtime efficiency
    * CMSIS device defintion for STM32
* [CMSIS](https://developer.arm.com/embedded/cmsis): Cortex Microcontroller Software Interface Standard (CMSIS) is a vendor-independent hardware abstraction layer for the Cortex®-M processor series and defines generic tool interfaces. It has been packaged as a module for Arduino IDE: https://github.com/stm32duino/ArduinoModule-CMSIS
* [GNU Arm Embedded Toolchain](https://developer.arm.com/open-source/gnu-toolchain/gnu-rm): Arm Embedded GCC compiler, libraries and other GNU tools necessary for bare-metal software development on devices based on the Arm Cortex-M. Packages are provided thanks [The xPack GNU Arm Embedded GCC](https://xpack.github.io/arm-none-eabi-gcc/): https://github.com/xpack-dev-tools/arm-none-eabi-gcc-xpack


<!-- GETTING STARTED -->
## Getting Started

This repo is available as a package usable with [Arduino Boards Manager](https://www.arduino.cc/en/guide/cores).

Add this link in the "*Additional Boards Managers URLs*" field:

https://raw.githubusercontent.com/tingliwong/ZM-Micro-Board-STM32F4/master/release/package_ZM_Micro_Board_index.json


For full instructions on using the "**Boards Manager**", see the [Getting Started](https://github.com/stm32duino/wiki/wiki/Getting-Started) page.

Advanced user can use the repository to benefit from the latest development. See the [Using git repository](https://github.com/stm32duino/wiki/wiki/Using-git-repository) page.

User can add a STM32 based board following this [wiki](https://github.com/stm32duino/wiki/wiki/Add-a-new-variant-(board)).


## Troubleshooting

For question, support, ...,  you could submit a topic on the (zircuitmatch@gmail.com).

If you have any issue, you could [file an issue on Github](https://github.com/tingliwong/issues).

In any case, it always fine to search if your issue was not already existing before submit a new one.

