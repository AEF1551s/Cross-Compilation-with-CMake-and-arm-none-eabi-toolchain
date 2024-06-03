

# CMake Crosscompilation, OpenOCD  
Basics about CMake Crosscompilation using arm-none-eabi toolchain  
Using OpenOCD to program STM32F410RB NUCLEO board  
The code flashes green user LED for testing purposes  
## Problems
Altough OpenOCD outputs that the programming has been finished without errors - LED doesn't flash. 
When programming .elf file compiled and linked from CubeIDE - LED flashes. 

Solution - add vector table
