# UART on AndroidThings

## Describe
Implement an app that receives commands from UART and run functions as follows.
 + 'O' : App starts ready to receive commands.
 + '1' : Using three pins to control an RGB LED displaying in different colors.
 + '2' : Get input from a button and then change the pace of color displaying (ex 1). For example, the RGB LED changes colors in 2s by default. After a button is pressed, the rate will change to 1s, then 0.5s, 0.1s and back to 2s. 
 + '3' : Similar to exercise 1, control the RGB LED by using PWM to change the brightness of the led. Please read this link for more details of PWM
 + '4' : Get input from a button and change the brightness of each color of the RGB LED. For example, the RGB LED changes the brightness of red, green, blue by default. After a button is pressed, only the red one is changing its brightness, then green, blue and back to three colors.
 + '5' : Blink each LED in different paces. The RED LED is blinking every 0.5s, the green is 2s, and the blue is 3s.
 + 'F' : App stops any running.

## GPIO ports

| Peripherals    |  Raspberry Pi 3 ports |
|----------------|-----------------------|
| LED RED        |  BCM2|
| LED GREEN      |  BCM3|
| LED BLUE       |  BCM4|
| BUTTON         |  BCM20|
| PWM PIN        |  PWM0|

## MEMBERS

+ Trần Minh Đức
+ Trần Thanh Sang
+ Nguyễn Minh Nhựt
+ Lê Đức Trung
