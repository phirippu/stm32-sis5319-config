# stm32-sis5319-config
Basic tool to configure SIS5316 PLL for 28.8 MHz to use as a master clock for RTL-SDRs.

It is a direct adaptation of the code by iroks.
https://github.com/iroks/SI5319config

The code does nothing but configures SIS 5316 bi I2C and blinks a LED to show success/failure.
The hardware is a $1 STM32F040 development board from AliExpress.
