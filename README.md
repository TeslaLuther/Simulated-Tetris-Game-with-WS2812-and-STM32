# Simulated-Tetris-Game-with-WS2812-and-STM32

Apart from an STM32 MCU, this project involves the use of a WS2812 screen with the size of 16 * 16, a MPU6050 module, as well as a USART HMI produced by Taojingchi company. 

Connections:
  PE9 connects with the signal input pin of WS2812 screen;
  I2C1 (PB6, PB7) connects with a MPU6050 module. This MPU6050 can move a block left and right through its roll angle;
  UASRT1 (PA9, PA10) connects with a USART HMI;
  PA3, PA4, PA5 connect with 3 keys. Among them PA3 is used to stop and restart the game; PA4 control the rotation of a block in the game; PA5 makes a block makes a block fall more quickly when the key is pressed.

The MCU used in this project is STM32F407ZGT6. It is also acceptable to use other STM32 MCUs if STM32F407ZGT6 is unavailable.
