# CMake Crosscompilation, OpenOCD  
Basics about CMake Crosscompilation using arm-none-eabi toolchain  
Using OpenOCD to program STM32F410RB NUCLEO board  
The code flashes green user LED for testing purposes  
Used Ninja generator  

## Preequisites  
* CMake
* OpenOCD  
* gcc-arm-none-eabi
  
## Build and compile  
<code>cmake -D FLASH=OFF build </code>  
<code>ninja</code> (generator used)

## Flash
<code>cmake -D FLASH=ON build</code>  
<code>ninja</code> (generator used)

