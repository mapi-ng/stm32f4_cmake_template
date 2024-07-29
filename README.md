# STM32F4 CMake template
Template project for STM32F4 with CMake

## Prerequisites (Ubuntu)

1. Download _STM32CubeMX_
https://www.st.com/en/development-tools/stm32cubemx.html#get-software

2. Make sure the installation files have execution rights:
`sudo chmod 755 jre/bin/*`

3. Install using _SetupSTM32CubeMX-6.12.0_

4. Download _STM32CubeIDE_:
https://www.st.com/en/development-tools/stm32cubeide.html#st-get-software

5. Execute sh script from the archive and follow the installation steps.

Default installation directory is `/home/user/st/stm32cubeide_1.16.0/`

6. Install GCC for ARM
`sudo apt -y install gcc-arm-none-eabi`

## CMake project generation

CMake project can be generated from _STM32CubeMX_. Afterwards it can be built and connfigured from other IDE, e.g. _Visual Studio Code_.
