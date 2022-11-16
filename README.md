# stm32-led-timer

It's a simple project of blinking two LEDs with a timer interrupt. 
These Two LEDs are connected to pin PA5 and PB14.

You can find the interrupt handler function- *void HAL_TIM_PeriodElapsedCallback(TIM_HandleTypeDef * htim)* in the main.c file, which handles the GPIO toggle operation.

How to build and upload the code
--------------------------------------
1. Open hello-stm32-btn-led.ioc file with STM32CubeMX
2. Generate Code
3. Open Project with IAR EW for ARM
4. Build and upload the code
5. 
