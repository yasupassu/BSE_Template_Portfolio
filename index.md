# Gesture Control Car
A car controlled by hand gestures recoreded with a remote camera. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Yasmin Husain | Evergreen Valley High School | Robotics | Incoming Senior

![Headstone Image](https://i.imgur.com/av0lSgR.jpeg)

# Demo Night
[![Demo Night Presentation](https://res.cloudinary.com/marcomontalbano/image/upload/v1625246002/video_to_markdown/images/youtube--d3aIzg7xNMY-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=d3aIzg7xNMY "Demo Night Presentation"){:target="_blank" rel="noopener"}

# Final Milestone
My final milestone was to mount the motors on the chassis and get the accelerometer values to move the motors. As I was able to communicate the x and y acceleration values to the ESP32 on the car, I used those values to give the car direction. The car would go forward if the x values were positive and backwards if the values were negative. To turn left or right I had one set of motors turn backwards and one set turn forwards. 

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1628560981/video_to_markdown/images/youtube--_Kh4Z2_YrRo-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=_Kh4Z2_YrRo&ab_channel=BlueStampEng "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My second milestone was to communicate the accelerometer values from one ESP32 to the one on the car. I had some difficulty getting the values to appear on the recieving ESP32 serial monitor, but I was able to fix this by changing the source code in the library. After doing this I was able to communicate the x, y, z acceleration values and the rotation values. The only values I needed were the x and y values of acceleration so I only communicated those values to the ESP32 on the car. 

[![Milestone 2](https://res.cloudinary.com/marcomontalbano/image/upload/v1625244709/video_to_markdown/images/youtube--zTZI7BwsVhM-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=zTZI7BwsVhM "Milestone 2"){:target="_blank" rel="noopener"}

# First Milestone
My first milestone was getting my dc motors to work with the motor driver. I ran into some difficulty with the speed control, but I was able to fix this by rewiring the five volt pin to the five volt port behind the ENA pin. Then I needed to wire the battery in a way to power my Audrino and my motor driver. I was able to get my DC motors to run withe a 6V battery pack. To connect all four motors to one motor driver I had to wire two motors to a port. I was able to get the motors to run, and to prvent the reduction of the speed of the motors, I will have to increase the voltage of the battery. 

[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1624291749/video_to_markdown/images/youtube--zME3vZloXAk-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=zME3vZloXAk "First Milestone"){:target="_blank" rel="noopener"}

