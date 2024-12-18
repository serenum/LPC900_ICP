# LPC900_ICP
LPC900 Arduino ICP programmer
Arduino project of MCU programmer for LPC900 lineup (NXP, Philips). Use with Flash Magic or any COM-terminal software.
This is a fork from ISP/ICP bridge for MCB900 programmer created by Bauke Siderius.
You can use any Arduino board, I have used ESP32-S3-Zero. Edit progdef.h for pins define, if you need it.
My pins definition:
* 1 - RESET
* 2 - PCL
* 3 - PDA
* 4 - Vcc
