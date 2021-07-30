# Automated Cat Laser
Provide your cat hours of fun using my project, the Auto Cat Laser! It was built using an Arduino Uno R3, two Micro Servos, a breadboard, a laser diode, and lots of connector wires. My modified code allows it to move side-to-side and up-and-down for more cat action.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Maya Wang | Lowell High School | Mechanical Engineering | Rising Junior

![Headstone Image](https://bluestampengineering.com/wp-content/uploads/2016/05/improve.jpg)

# Introduction
Hey there! 
  
# Final Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint. 

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint.

[![Third Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574014/video_to_markdown/images/youtube--y3VAmNlER5Y-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=y3VAmNlER5Y&feature=emb_logo "Second Milestone"){:target="_blank" rel="noopener"}

# First Milestone

My first milestone was getting the laser to shine, wiring the Arduino, and coding the servos. It sounds simple, but it was actually very challenging for me as I had no experience with electronics prior to Bluestamp Engineering and minimal programming experience. I spent most of the first 3 days of camp researching all the different parts in my kit and figuring out what they did. Eventually, I concluded I could get my laser diode to shine using the Arduino Uno and several connector wires. After I successfully got my laser to shine, I decided it was time to wire everything else. I used this diagram as reference: https://content.instructables.com/ORIG/FJ9/DRW4/GZDY7AGV/FJ9DRW4GZDY7AGV.jpg.

My first challenge was being able to understand the schematic itself! There seemed to be so many wires coming out of the Arduino, servos, and laser, and I was initially very overwhelemed and confused. After analyzing the diagram for a while and playing around with the connector wires, I was able to wire up the wires that directly connected to the Arduino pins. I didn't understand how to wire parts that did not connect to the Arduino (for example, connecting the servo and the laser) because I was unable to solder and didn't have a soldering kit anyways. I asked my instructor and learned I had to use a breadboard, another part I was unfamiliar with. However, after even more YouTube videos, staring at the schematic, some trial-and-error, and a handful of tape, I was able to understand how to simultaneously use a breadboard and Arduino. Wiring up the Arduino felt much less stressful after that and more fun, and I was successfully able to wire up the Arduino and get my laser to shine!

Now I could move on to the coding portion of the milestone. After researching Arduino IDE for a bit and how to use it with an Arduino Uno, I installed Arduino IDE on my laptop, imported code for the servos from this website: https://www.instructables.com/CatBot-Automated-Cat-Laser/, and then uploaded onto my Arduino. The first thing I noticed was that one of my servos was moving, but the other one was not. I double and triple checked the code I imported and the wires, but both seemed to have no errors. However, it turns out I had wired the servos incorrectly, and I had to move and rearrange a lot of connector wires on the breadboard. I followed the scehmatic shown below to rewire the breadboard, and learned that certain colored wires had to go in specific spots on the breadboard. Furthermore, I learned that part of the reason the servo was not moving was because I plugged a wire into a pin without the '~' symbol, which meant it was unable to receive power.

I plan to modify the code for my third milestone so I can include a motion sensor in this project, but for now, I'm going to move on and work on the mechanical design of the cat laser.  

![2Servo](https://user-images.githubusercontent.com/55466693/127706521-2404cc46-901f-4546-82e4-985a589488a3.PNG)


[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574117/video_to_markdown/images/youtube--CaCazFBhYKs-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=CaCazFBhYKs "First Milestone"){:target="_blank" rel="noopener"}
