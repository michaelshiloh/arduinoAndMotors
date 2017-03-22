# Arduino Tutorial: Using an Adafruit Motor Shield V2



1. Always use separate power supplies for the Arduino and the motors to avoid
any possibility of the motor affecting the proper operation of your Arduino.
This means you should always remove the VIN jumper on the Adafruit Motor
Shield V2. This jumper would be on the two pins next to the motor power
screw terminals, so if you see two bare pins there the jumper has been
removed.

2. You can power your Arduino either using a USB cable (e.g. from a
rechargable USB battery) or the DC barrel jack on the Arduino. If you provide
power through the DC power jack it must be in the range of 7-12v. It is
possible that your Arduino might run at a lower voltage but this is not
guaranteed to work and is unreliable.

#[](images/AdafruitMotorShieldSeparatePower_bb.png)

