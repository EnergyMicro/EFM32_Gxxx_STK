Keil RTX RTOS - tick-less example with LCD off

This example is modification of rtx_tickless to demonstrate ultra low power consumption 
of Gecko processors in connection with RTX RTOS. Comparing to previous example it has LCD
turned off. Low frequency crystal oscillator was disabled and low frequency RC oscillator
used instead to lower energy consumption even more.


This example project uses the Keil RTX RTOS, and gives a basic demonstration
of using two tasks; one sender generating number and one receiver.
The RTX is configured in tick-less mode, going into EM2 when
no tasks are active. This example is intended as a skeleton for new projects
using Keil RTX for energy aware applications.

Board:  Energy Micro EFM32_Gxx_STK
Device: EFM32G890F128
