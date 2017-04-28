# SeeedStudio 4A Motor Shield v1.0
This is a fork of SeeedStudio's https://github.com/Seeed-Studio/SeeedMotorShieldV2. This is in order to make the shield work with Arduino UNO. Even though in the link says it's SeeedMotorShieldV2, it's actually meant for the 4A Motor Shield v1.0 that you can find here

https://www.seeedstudio.com/4A-Motor-Shield-p-1954.html

The only difference is that in _MotorDriver.h_ I changed the pin numbers so they match the ones supported in Arduino UNO. The schematics is here

http://wiki.seeedstudio.com/images/9/93/4A_MOTOR_Shield_v1.0.pdf

In there, it clearly says that the digital pins to use are:
* 5, 6 and 9 for Motor A
* 7, 8 and 10 for Motor B

I've tested this on Arduino UNO only, but will try on Edison soon. Stay tuned.

# Disclaimer
This is by no means a supported library. I just forked it for the sake of having a library that works for me. You're welcome to use it and even contribute is appreciated.
