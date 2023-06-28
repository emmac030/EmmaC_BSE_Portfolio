# Posture Corrector 
My project is a posture corrector that reminds a user to sit properly once they slouch or move into a bad posture. The user will sit on a  yoga ball with a flex sensor that will tell if the user is in a bad posture based on the pressure the user exerts on the sensor. When the user applies more pressure on the sensor, the LED strip will light up. 

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

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> -->

<!--# Second Milestone
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
``` -->

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Arduino Uno | Open source microcontroller used to read inputs | $28.50  | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/ref=sr_1_3?crid=3VNEAL981J2CL&keywords=arduino+uno&qid=1685848547&sprefix=arduino%2Caps%2C170&sr=8-3"> Link </a> |
|:--:|:--:|:--:|:--:|
| Breadboard | Used to build circuts | $5.99 | <a href="https://www.amazon.com/Qunqi-point-Experiment-Breadboard-5-5%C3%978-2%C3%970-85cm/dp/B0135IQ0ZC/ref=sr_1_10?crid=2NREO3D61OYUY&keywords=breadboard&qid=1687992200&sprefix=breadboar%2Caps%2C210&sr=8-10"> Link </a> |
|:--:|:--:|:--:|:--:|
| LED Lights | Used to alert the user that they are in bad posture | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Yoga Ball | The user sits on this yoga ball | $24.95 | <a href="https://www.amazon.com/OPTP-Soft-Movement-Ball-Stability/dp/B07HZ1ZF2M/ref=sr_1_6?crid=2Z3VMANLO7K39&keywords=pilates+yoga+ball+12+inches&qid=1687561381&sprefix=pilates+yoga+ball+12+inche%2Caps%2C146&sr=8-6"> Link </a> |
|:--:|:--:|:--:|:--:|
| Jumper Wires Male | Connection source from arduino to breadboard | $1.95 | <a href="https://www.adafruit.com/product/1950"> Link </a> |
|:--:|:--:|:--:|:--:|
| Solid Core Wire | Connection source from arduino to breadboard and LED strip | $2.95 | <a href="https://www.adafruit.com/product/290"> Link </a> |
|:--:|:--:|:--:|:--:|
| Power Source | External powersource to power the arduino and the LED strips | $7.19 | <a href="https://www.amazon.com/Arkare-100V-240V-Replacement-Security-Raspberry-Pi/dp/B09W8X9VGK/ref=sr_1_2?keywords=ac+dc+adapter+5v&qid=1687987358&sr=8-2"> Link </a> |
|:--:|:--:|:--:|:--:|
| Long Flex Sensor | Sensor used to measure the resistance of the user. | $12.95 | <a href="https://www.adafruit.com/product/182"> Link </a> |
|:--:|:--:|:--:|:--:|
| 10K Ohms Resistor | Used to generate values for the flex sensor  | $0.75 | <a href="https://www.adafruit.com/product/2784"> Link </a> |
|:--:|:--:|:--:|:--:|
| Screw Terminal Barrel Jack |  Used to connect the 5V and ground wires to the power source | $4.99 | <a href="https://www.amazon.com/Connector-Barrel-Adapter-Security-Camera/dp/B09S3S6RYC/ref=sr_1_11?crid=UT45N7OH2BQX&keywords=screw+terminal+barrel+jack&qid=1687992329&sprefix=screw+terminal+barrel+jack%2Caps%2C139&sr=8-11"> Link </a> |


<!--# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesom  e examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.--> 
