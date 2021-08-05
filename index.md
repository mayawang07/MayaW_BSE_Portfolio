# Automated Cat Laser
Provide your cat hours of fun using my project, the Auto Cat Laser! It was built using an Arduino Uno R3, two Micro Servos, a breadboard, a laser diode, and lots of connector wires. My modified code allows it to move side-to-side for more cat action.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Maya Wang | Lowell High School | Mechanical Engineering | Rising Junior

![Headstone Image](https://bluestampengineering.com/wp-content/uploads/2016/05/improve.jpg)

# Introduction
Hey there! My name is Maya and I'm a rising high school junior with a passion for engineering - I'm a part of my school's FRC robotics team and love to build LEGOs in my (somewhat limited) free time. I have an adorable tuxedo cat named Kit Kat, and she is actually the reason why I chose the auto cat laser as my project. Building the auto cat laser would be a good way for me to learn the engineering design process and how to use various electronics but also, if I successfully complete this project, my cat would be able to use it every day if she wanted to!
  
# Final Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint. 

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My second milestone was designing and building the servo tilt/pan. I didn't have any spare metal pieces in my house or in my project kit, so I decided to just use cardboard, zipties, and a hot glue gun. I spent a day or two just brainstorming and sketching (and sometimes trashing) design ideas. I came up with the design shown below after drawing some inspiration from [this design](https://content.instructables.com/ORIG/FBT/XOJD/GZDY7AI1/FBTXOJDGZDY7AI1.jpg?auto=webp&frame=1&width=1024&fit=bounds&md=d3c243628d753cd08d7d95415e2988c7) and using it as a reference. After finalizing the design, I began measured and cut the cardboard I had to make the parts. Sticking the breadboard on the cardboard base wasn't too hard; I simply peeled off the adhesive protective paper on its backside and placed it on its assigned area on the board. However, the Arduino Uno definitely gave me a bit of trouble.

![Laser Design](https://user-images.githubusercontent.com/55466693/128218813-3d14a4e9-810f-4f41-8b1a-e47befc82af1.jpg)

The first challenge I encountered while assembling was that the zipties provided in my project kit were too big to fit through the pre-drilled holes in the Arduino Uno. I looked around my house for string, but I only managed to find one spool of yarn that was also too thick to fit through the Arduino holes. After a while, I found a black rubber band hanging on my desktop lamp and decided to give it a try. I cut it into smaller pieces so it would secure the Arduino and thankfully, it easily fit through the hole! Unfortunately, the next challenge I encountered was getting said rubber band to stay in place, because standard office tape wasn't strong enough to hold it down. To solve this, I used packaging tape instead and added multiple layers of it. Afterwards, I used a hot glue gun to fasten the horizontal servo holder to the base and to glue the vertical servo holder onto the horizontal servo. I used double sided tape to secure both servos to their respective holders. Once that was finished, I cut off some excess cardboard from the base and taped the laser onto the vertical servo. I initially wanted to attach the laser to the servo using zipties, but when I tried to do so, the zipties would not tighten enough to secure the laser and the laser would just slide out of the ziptie.


Another challenge I had was getting the laser to shine in the direction I wanted it to, because the laser diode was very sensitive and only worked at certain angles. I used tape to fasten the laser diode's wires and angled it in different directions (basically, I just used trial-and-error and prayed for the best). 

When I plugged the Arduino into a power bank, the auto cat laser successfully worked without any problems which means I am done with my project! For my third milestone, I am planning to add modifications to the project - including a sensor. 

{:target="_blank" rel="noopener"}

# First Milestone

![Project GIF](https://media.giphy.com/media/lYCUCDHz125aLytXLS/giphy.gif)

My first milestone was comprised of three objectives: getting the laser to shine, wiring the Arduino, and coding the servos. It sounds simple, but it was actually very challenging for me as I had no experience with electronics prior to Bluestamp Engineering. I spent most of the first 3 days of camp researching all the different parts in my kit and figuring out what they did. Eventually, I concluded I could get my laser diode to shine using the Arduino Uno and several connector wires. Getting the laser to light up wasn't *too* hard, and after I did, I decided it was time to wire up everything else. I used [this schematic](https://content.instructables.com/ORIG/FJ9/DRW4/GZDY7AGV/FJ9DRW4GZDY7AGV.jpg) as a reference.

My first challenge was being able to understand the schematic itself! There seemed to be so many wires coming out of the Arduino, servos, and laser, and I was initially very overwhelmed and confused. After analyzing the diagram for a while and playing around with the connector wires, I was able to wire the parts that directly connected to the Arduino pins. I didn't understand how to wire parts that did not directly connect to the Arduino (for example, wiring a servo and the laser together) because I was unable to solder and didn't have a soldering kit anyways. I asked my instructor and learned I had to use a solderless breadboard, another part in my project kit I was unfamiliar with. However, after watching even more YouTube videos, staring at the schematic, and some trial-and-error, I was able to understand how to simultaneously use a breadboard and Arduino. Wiring the Arduino felt so much less stressful after that and more fun! 

Now I could move on to the coding portion of this milestone. After researching what Arduino IDE was for a bit and how to use it with an Arduino Uno, I installed Arduino IDE on my laptop, imported [this code](https://content.instructables.com/ORIG/FM8/U0OR/GZDY7BDV/FM8U0ORGZDY7BDV.ino) for the servos, and then uploaded it onto my Arduino. The first thing I noticed when I ran the code was that one of my servos was moving, but the other one was not. I double and triple checked the code I imported and the connector wires, but both seemed to have no errors to me. However, it turns out I had wired the servos (very) incorrectly, and I had to rearrange a lot of connector wires on the breadboard. I followed the schematic shown below to rewire the breadboard, and learned that certain colored wires on the servos had to go in specific spots on the breadboard. Furthermore, I learned that part of the reason the servo was not moving was because I plugged a wire into a pin without the '~' symbol, which meant the servo was unable to receive power.

![2Servo](https://user-images.githubusercontent.com/55466693/127706521-2404cc46-901f-4546-82e4-985a589488a3.PNG)

After I made all these corrections, I plugged the Arduino Uno into my laptop and reuploaded the code that I had modified just a bit. Sure enough, both servos were now moving and the laser was shining bright as ever. I plan to modify the code for my third milestone so I can include a motion sensor in this project, but for now, I'm going to move on and work on the mechanical design of the cat laser.  

[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1627865584/video_to_markdown/images/youtube--yVBORp45Mpw-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/yVBORp45Mpw "Maya W First Milestone")
