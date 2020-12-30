# Not-So-Basic-Arduino

## LED Blink Revisited

This was my first Arduino assignment. I had to make an LED Fade on and off.

[LED Blink Revisited]
https://create.arduino.cc/editor/FinnWimberley/5b6b91f8-97b5-40aa-ac85-d2b039ef2025

![BlinkingLED2](Images/BlinkingLED2.png)

At the start I struggled a lot trying to figure out how to use Arduino Editor. I eventually figured out how to make it recognize that I had the Arduino plugged into my Chromebook. Once I did that I didn't have too much trouble making the LED blink but when I had to make it fade on and off I had a little more trouble. Then I figured out that I had to put in more lines of code and shorten the delay time in between them. Once I played around with that for long enough I found some values that worked and then I was done.

---

## Finite LED Blinker

For this assignment I had to make an LED blink five times and then stop.

[Finite LED Blinker]
https://create.arduino.cc/editor/FinnWimberley/6c2560ff-0819-494f-8df7-9a32b46de519

![FiniteLEDBlinker](Images/FiniteLEDBlinker.jpg)

This assignment was a little similar to the last assignment because it involved making an LED blink, but it was a lot more complicated and difficult. I had to use "if" and "else" statements to tell Arduino to blink the LED if the counter was five or less and to stop blinking the LED if the counter was six or more.  I also had to make sure I made the delays long enough and in the right areas so that I was able to tell when it stopped blinking.  Like with the last assignment, after I played around with varying delay times in different areas, I eventually got it to look nice.

---

## Hello Functions

For this assignment I had to use functions to make the servo rotate based on information gathered by the ultrasonic sensor.

[Hello Functions]
https://create.arduino.cc/editor/FinnWimberley/d8cc3e68-0564-485b-9fe2-75d574ad8e53

![SensorAndServo](Images/SensorAndServo.jpg)

This was the most challenging assignment yet.  It involved skilles that I learned in all the other assignment and learning how to use then together to make something work.  First I made a seperate sketch to figured out how to use the servo.  After that I made another sketch to figured out how to use the ultrasonic sensor.  Then I hooked up the servo and the ultrasonic sensor to the arduino at the same time.  I had to figure out how to make the outputs of the ultrasonic sensor the inputes of the servo, so I used an if statement and put a nice delay time.  Suprisingly after that I put my hand in front of the ultrasonic sensor and the servo started to rotate.

---

## NewPing

For this assignment I had to code something using the NewPing library.

[NewPing]
https://create.arduino.cc/editor/FinnWimberley/f0011cec-e91f-4155-8e65-579b9e3700e6

![NewPing](Images/NewPing.jpg)

This was a smaller assignment then the last one but it was still very challenging.  I had to creat a program that utilized the NewPing library.  First I included the library at the top of the program.  Then I difined the variables for the trigger pin, echo pin, maximum distance and one more distance mesured by the sensor.  Next I wrote the constructor which allows me to easily use functions from the NewPing library in my code.  Finally I dicided to use the sonar.ping function to print the distance captured by the sensor to the serial monitor in centimeters.

---

## Photoresistor

For this assignment I had to make an LED turn on based on the light levels around it.

[Photoresistor]
https://create.arduino.cc/editor/FinnWimberley/f0011cec-e91f-4155-8e65-579b9e3700e6

![Photoresistor](Images/Photoresistor.jpg)

This was the last asignment before the project and was another very challenging one.  I reilized I was not given the 10k resistor so I had to make my own with salt, water and wires.  Then I had to wire the photoresistor and the LED to the breadboard and the aurduino.  Next I wrote a program to figure out the voltage of the photoresistor circuit when it was bright and when it was dark.  After that I added some code to turn the led on and off based on the amount of voltage in the curcuit using an if else statement and added a good delay time.  Finally When I ran the code the LED was off but when I put my finger over it to make it dark the LED turned on.

---

