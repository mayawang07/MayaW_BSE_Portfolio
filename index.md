# Automated Cat Laser
Provide your cat hours of fun using my project, the Auto Cat Laser! It was built using an Arduino Uno R3, two Micro Servos, a breadboard, a laser diode, and lots of connector wires. My modified code allows it to move side-to-side for more cat action.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Maya Wang | Lowell High School | Mechanical Engineering, Computer Science | Rising Junior

![Headstone Image](https://bluestampengineering.com/wp-content/uploads/2016/05/improve.jpg)

# Introduction
Hey there! My name is Maya and I'm a rising junior with a passion for engineering - I'm a part of my school's FRC robotics team and love to build LEGOs in my (somewhat limited) free time. I have an adorable tuxedo cat named Kit Kat, and she is actually the reason why I chose the auto cat laser as my project. Building the auto cat laser would be a good way for me to learn the engineering design process and how to use various electronics but also, my cat would be able to use it every day if she wanted to!
  
# Final Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint. 

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint.

[![Third Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574014/video_to_markdown/images/youtube--y3VAmNlER5Y-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=y3VAmNlER5Y&feature=emb_logo "Second Milestone"){:target="_blank" rel="noopener"}

# First Milestone

My first milestone was comprised of three objectives: getting the laser to shine, wiring the Arduino, and coding the servos. It sounds simple, but it was actually very challenging for me as I had no experience with electronics prior to Bluestamp Engineering and minimal programming experience. I spent most of the first 3 days of camp researching all the different parts in my kit and figuring out what they did. Eventually, I concluded I could get my laser diode to shine using the Arduino Uno and several connector wires. Getting the laser to light up wasn't *too* hard, and after I did, I decided it was time to wire up everything else. I used [this schematic](https://content.instructables.com/ORIG/FJ9/DRW4/GZDY7AGV/FJ9DRW4GZDY7AGV.jpg) as a reference.

My first challenge was being able to understand the schematic itself! There seemed to be so many wires coming out of the Arduino, servos, and laser, and I was initially very overwhelmed and confused. After analyzing the diagram for a while and playing around with the connector wires, I was able to wire the parts that directly connected to the Arduino pins. I didn't understand how to wire parts that did not directly connect to the Arduino (for example, wiring a servo and the laser together) because I was unable to solder and didn't have a soldering kit anyways. I asked my instructor and learned I had to use a solderless breadboard, another part in my project kit I was unfamiliar with. However, after watching even more YouTube videos, staring at the schematic, and some trial-and-error, I was able to understand how to simultaneously use a breadboard and Arduino. Wiring the Arduino and servos felt so much less stressful after that and more fun! 

Now I could move on to the coding portion of this milestone. After researching what Arduino IDE was for a bit and how to use it with an Arduino Uno, I installed Arduino IDE on my laptop, imported code for the servos from [this website](https://www.instructables.com/CatBot-Automated-Cat-Laser/), and then uploaded it onto my Arduino. The first thing I noticed when I ran the code was that one of my servos was moving, but the other one was not. I double and triple checked the code I imported and the connector wires, but both seemed to have no errors to me. However, it turns out I had wired the servos (very) incorrectly, and I had to rearrange a lot of connector wires on the breadboard. I followed the schematic shown below to rewire the breadboard, and learned that certain colored wires had to go in specific spots on the breadboard. Furthermore, I learned that part of the reason the servo was not moving was because I plugged a wire into a pin without the '~' symbol, which meant the servo was unable to receive power.

After I made all these corrections, I plugged the Arduino Uno into my laptop and reuploaded the code that I had modified just a bit. Sure enough, both servos were now moving and the laser was shining bright as ever.
I plan to modify the code for my third milestone so I can include a motion sensor in this project, but for now, I'm going to move on and work on the mechanical design of the cat laser.  

![2Servo](https://user-images.githubusercontent.com/55466693/127706521-2404cc46-901f-4546-82e4-985a589488a3.PNG)


[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574117/video_to_markdown/images/youtube--CaCazFBhYKs-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=CaCazFBhYKs "First Milestone"){:target="_blank" rel="noopener"}
