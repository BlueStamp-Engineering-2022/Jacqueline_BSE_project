# Modified 5 Joint Robotic Arm
This robotic arm is a modified version of the 4 joint robotic arm. It's uses 5 servos to move each joint of the arm, and can be controlled using a joystick or by bluetooth using an android phone app. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Jacqueline Li | Palo Alto High School | Mechanical Engineering | Incoming Junior

![Headstone Image](https://lh3.googleusercontent.com/pw/AM-JKLWvRZPySKtNMw2l8cFQgy0hguL3NRoTFVlV7KkOgYxTWD3nOlJwgJsVo3F3tkhdnyeY9Ajf88zYGMP5llmJCRMDiq_inE7K75EN8vGzypXLCgeLmKIJpN6nrvHO3c4rvDGbwAylgRGtgEn-LO_HIu4=s943-no?authuser=0)

# Second Milestone
My second final milestone was getting the bluetooth module and app set up to control the arm and adding a fifth joint to the arm. Setting up the module just required me to plug it into the right ports on the arduino, and after downloading the app and connecting it, almost everything worked the way it was supposed to. All I needed to change was the range of the servos in the code. After that was working smoothly, I began planning my modification to the arm. I decided I wanted to add a fifth joint where the claw was so it was able to flip over, so I used Onshape to make a 3D model of the existing pieces. I then used it to design a couple new pieces that I would need to make the modification work, and used a 3D printer to print them out. Because 3D printing isn't very precise, it took a couple tries and changes to the design to print pieces that fit. After everything was printed, I got a fifth servo and assembled everything together. To allow this servo to be controlled by the joystick, I had to add code to the program. Since the x and y axes of both joysticks were already being used, I chose to assign the flipping motion to the joystick buttons instead. I learned that the pressed position of each button was LOW, and used that to write a code where if LOW was read, the servo would activate to flip. In this way, the joystick could be used to control the new servo, but since the phone app was preprogrammed, I wasn't able to add anything to it.

![CAD file](https://github.com/BlueStamp-Engineering-2022/Jacqueline_BSE_project/blob/gh-pages/Assembly%201%20Drawing%201.png?raw=true)

[![Third Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574014/video_to_markdown/images/youtube--y3VAmNlER5Y-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=y3VAmNlER5Y&feature=emb_logo "Second Milestone"){:target="_blank" rel="noopener"}

# First Milestone
  
My first milestone was finishing the assembly of the robotic arm and setting up the joystick controls. Assembling the frame of the arm was my first step, and after that I began attaching the servo motors to the joints of the arm and wiring them to the Arduino. Because the servos only have a range of 180 degrees, I had to be careful attaching them at the right angle to cover all the range of motion the arm needed. I used a short program to set every servo to 0 degrees, then attached them to the arm in the positions required. The code for the joystick assigns each x and y axis of the left and right joysticks to a different servo motor. Pushing the joystick returns a value from 0 to 1024, and the script works by reading this value, and when it exceeds or is below a certain value, it will call the servos to move the arm. 

[![First Milestone](https://i3.ytimg.com/vi/Qqwz8_yHCeY/maxresdefault.jpg)](https://www.youtube.com/watch?v=Qqwz8_yHCeY&ab_channel=BlueStampEng "First Milestone"){:target="_blank" rel="noopener"}

# Starter Project
  
My starter project was the Simon Says game, a memory game where you copy series' of flashing lights using buttons. It's comprised of four buttons with LED lights underneath, a buzzer for sound, and a micro controller that runs the game. There are two switches, one to control the power and one to enable or disable the sound buzzer. All the parts are soldered to a board. 

[![Starter Project](https://i3.ytimg.com/vi/HAckeBsume0/maxresdefault.jpg)](https://www.youtube.com/watch?v=HAckeBsume0&ab_channel=BlueStampEng)
![simon says](https://cdn.sparkfun.com//assets/parts/5/1/5/0/SparkFun_Simon_Says_-_Through-Hole_Soldering_Kit-03.jpg)
