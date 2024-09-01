##ESP32 VR Controller

I recently bought a couple of ESP32s to try and build a VR controller. This was inspired by my desire to make a cheap VR controller to use with my Note 9 phone rather than spending thousands of dollars on a VR setup.

I was very surprised at how well VR worked on my phone so I decided to try and create a complete VR experience with some kind of input device.

The ESP32 has so far proved to be the best bet. It supports HID gamepad profiles over bluetooth straight out of the box without the need for any additional components.

For the motion input I bought a GY521. This very cheap module gives rotation data on X, Y and Z. Plus movement data on the same. This is exactly what the motion controllers for VR do plus joystick and button input.

So far so good. Initial tests are pretty simple but eventually it needs to be assigned as a composite HID input device and the data fed into a VR environment. I am guessing this is going to be the tricky bit.

[![Whatch the video](https://img.youtube.com/vi/P0JaLZ5-NdY/sddefault.jpg)](https://www.youtube.com/watch?v=P0JaLZ5-NdY)

![Alt Text](https://i.imgur.com/7kagkAy.jpeg)
