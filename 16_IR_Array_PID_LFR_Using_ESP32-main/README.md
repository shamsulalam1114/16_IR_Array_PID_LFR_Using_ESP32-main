# 16_IR_Array_PID_LFR_Using_ESP32

This is my Second Attempt to make a Line Follower Bot, I tried to correct the mistakes I made in my first LFR and here we go This is my new 16 IR Sensor Line Follower Bot using ESP32.

Why ESP32 because it has a High Clock Speed.

A line follower bot is a type of autonomous robotic vehicle designed to follow a predefined path or track marked with contrasting lines, typically black on a light-coloured surface or vice versa. These robots employ a combination of sensors, such as infrared or optical sensors, to detect the contrast between the line and the surrounding area. By continuously analyzing the sensor data, the bot makes real-time decisions on how to adjust its wheels or propulsion system to stay centred on the line.

Line follower bots are popular in robotics competitions and educational settings, as they provide an engaging way to introduce students and enthusiasts to basic robotics principles, sensor technology, and programming. They serve as a fundamental example of closed-loop control systems and can be customized with various features, like obstacle avoidance and speed adjustments, to make them more versatile and adaptable to different scenarios. Line follower bots can be a great starting point for those interested in exploring the world of robotics and automation.

A PID Line Follower Bot using an ESP32 Microcontroller is a small autonomous robot that uses infrared sensors to follow a designated path. It employs a PID (Proportional-Integral-Derivative) control algorithm to continuously adjust its motor speeds based on sensor feedback, maintaining alignment with the path. The ESP32 microcontroller processes the sensor data and sends control signals to the motors, allowing the bot to track lines, it is a popular choice for educational robotics projects and competitions.


## Source Code
1. `main.py` file which contains the basic setup and Run.
2. `bitmap.py` file contains all the menu graphics.
3. `KpValue.csv` and `KdValue.csv` are the files which store the kp and kd values.
4. `ssd1106.py` file is the library used for Oled display.
5. `framebuf.py` file is the library used for displaying graphics on Oled display.

>[!IMPORTANT]
>All the Files must be saved on the ESP32 Memory.

