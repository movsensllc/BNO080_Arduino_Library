BNO080 IMU Library
===========================================================


The BNO080/BNO085 IMU has a combination triple axis accelerometer/gyro/magnetometer packaged with an ARM Cortex M0+ running powerful algorithms. This enables the BNO080 Inertial Measurement Unit (IMU) to produce accurate rotation vector headings with an error of 5 degrees or less. It's what we've been waiting for: all the sensor data is combined into meaningful, accurate IMU information.

This IC was designed to be implemented in Android based cellular phones to handle all the computations necessary for virtual reality goggles using only your phone. The sensor is quite powerful but with power comes a complex interface. We've written an I<sup>2</sup>C based library that provides the rotation vector (the reading most folks want from an IMU) as well as raw acceleration, gyro, and magnetometer readings. The sensor is capable of communicating over SPI and UART as well!

In addition the BNO080 IMU provides a built-in step counter, tap detector, activity classifier (are you running, walking, or sitting still?), and a shake detector. We are duly impressed.

Library written by Nathan Seidle ([SparkFun](http://www.sparkfun.com)).

Thank to all those who have helped improve the library:

* blendmaster for adding [Linear Accel report](https://github.com/sparkfun/SparkFun_BNO080_Arduino_Library/pull/4)
* per1234 for fixing our [keywords file](https://github.com/sparkfun/SparkFun_BNO080_Arduino_Library/pull/12)
* fm4dd for typo - [PR 19](https://github.com/sparkfun/SparkFun_BNO080_Arduino_Library/pull/19)

Repository Contents
-------------------

* **/examples** - Example sketches for the library (.ino). Run these from the Arduino IDE. 
* **/src** - Source files for the library (.cpp, .h).
* **keywords.txt** - Keywords from this library that will be highlighted in the Arduino IDE. 
* **library.properties** - General library properties for the Arduino package manager. 


License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact techsupport@sparkfun.com.

Please use, reuse, and modify these files as you see fit. Please maintain attribution to SparkFun Electronics and release any derivative under the same license.

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
