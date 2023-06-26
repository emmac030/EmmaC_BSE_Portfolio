# Posture Corrector 
<!--My project is a posture corrector that reminds a user to sit properly once they slouch or move into a bad posture. The user will sit on a wedged yoga block with pressure sensors that will tell if the user is in a bad posture based on the pressure the user exerts on the sensor. -->

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Emma C | Lynbrook High School | Engineering | Incoming Sophome 

<!-- **Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Second Milestone
For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>-->

# First Milestone

<iframe width="537" height="301.5" src="https://www.youtube.com/embed/OPL-LPEhqJY" title="Emma C. Milestone 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" ></iframe>

My project is a device that is used to ensure that the user is sitting in a good posture. My first step to this project was to create a velostat pressure sensor using 4 materials; velostat, neoprene fabric, conductive thread and conductive fabric. The neoprene sandwiches the velostat. Both pieces of neoprene have the same stitching pattern made with conductive thread. When you place both pieces of neoprene on top of each other, the stitches make the figure "x" which allows the current to flow through. The Velostat then is placed between these pieces of neoprene and measures the current going between the pieces of thread. Once you apply pressure on the sensor, then the current is able to flow through and the arduino measures the current that flows through.  

A big challenge and problem with this sensor is that it is extremely inconsistent and not as sensitive as I would like it to be for my project. The Velostat often moves in between the pieces of neoprene making it hard for the arduino's reading to be consistently accurate. Instead of using the velostat pressure sensor, my next step is to figure how to use the flex sensor for my project. 


# Starter Project 

<iframe width="537" height="301.5" src="https://www.youtube.com/embed/l6ldjOKdyIM" title="Emma C. Starter Project" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" ></iframe>

For my starter project, I chose the custom arduino project where an LED light turns on when it senses motion. The PIR sensor has two settings, one being LOW and one being HIGH. LOW corresponds to the value 0 while HIGH corresponds to the value 1. When the sensor detects something, then the value changes from 0 to 1, causing the light to turn on. One challenge that took a long time to troubleshoot was to figure out why my LED light was constantly on. After printing the value from the sensor, I found out that the sensor kept detecting motion, causing the value to stay at 1 and the light to stay on. Switching the ground and the 5 volt jumper wire fixed the problem because my sensor didn’t specify which port was the positive versus negative. My next step is to move on to my main project. 



<!--# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.--> 
