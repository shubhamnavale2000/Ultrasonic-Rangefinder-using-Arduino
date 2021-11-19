# Distance-finder-using-Ultrasonic-Sensor-with-Arduino
In this project we are going to discuss how to use Ultrasonic sensor  (Distance /Range Finder) with arduino micro-controller .We will be getting the object distance or range of an object on the Serial Monitor of arduino application.

Step 1:

Connecting the SR04 Ultrasonic Sensor to the Arduino
Here in the picture Trig and Echo is connected to 12 and 11 But according to our code we have connected trig to 13 and echo to 12 .
So be sure you are connecting trig and echo to 13 and 12.

Connecte larger leg of LED to pin 5 and shorter with pin 6 of arduino.

![ultrasonic_arduino_wiring](https://user-images.githubusercontent.com/39452340/46581930-be672480-ca5d-11e8-8706-2b24c421e3b8.png)

![th](https://user-images.githubusercontent.com/39452340/46582129-f7a09400-ca5f-11e8-8ba2-3b5ab4a3eb44.jpg)


Step 2: Parts List
1               Arduino uno R3, or any Arduino for that matter
1               SR04 Ultrasonic Sensor
4               Jumper Wires


Step 3:

Connect Ultrasonic Sensor to Arduino
You Need 4 Jumper wires to conect the SR04 Ultrasonic Sensor to the Arduino:

1  From the SR04  VCC pin to the Arduino 5v
1 From the SR04  GND pin to the Arduino GND
1 From the SR04  TRG pin to the Arduino Digital pin 12
1 From the SR04  ECHO pin to the Arduino Digital pin 11


That's All The wireing you need... Easy,  no?

Next Step, load the Software library and sketches.

Step 4:

Step 4 Download SR04 Library and its code from above folder and Install to Arduino IDE
 

If you were successful at installing the codes,  Compile the sketch  by clicking on the verify button and make sure there are no errors.

It's time to connect your Arduino to your PC using the USB cable.  Click on the upload button  to upload the sketch to the Arduino.

Once uploaded to the Arduino, open the serial monitor, and you should see the distance  data stream   coming from the sensor.
