# Autonomous Car 
The self driving car project is a miniture representation of  autonomous of vehicular transportation. With the ability to drive, navigate obstacles, modify pace to match surroundings, detect other vehicles and moving objects, the car demonstrates the future of transportation. 





| **Name** | **School** | **Field of Intrest** | **Grade** |
|:--:|:--:|:--:|:--:|
|Tanvi N. | Notre Dame San Jose | MedTech |  Sophmore 

<!--**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE-->



# Second Milestone (6/26/24)

<!--**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**


<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
-->

For my second milestone, I elected to program the line sensor, ultrasonic, and object sensors. Given the application of these sensors, the robotic car is now able to navigate its environment autonomously. The new sensors allow the car to function by helping the car to detect objects, thus allowing it to manuver around obstacles. Some issues I have run ito when attatching and programming the sensors were: incorrect use of digitalWrite and analogWrite, poor sensor sensetivity, and failing to state integers in void setup. Through a dedicated week, I was able to work through these challenges and was eventually able to get my car to maneuver its environment by itself. As stated in the previous milestone, I also faced the challenge of having imbalanced motors, I was able to fix this through adjusting the speed of the individual motors. Next, for my third milestone, I plan to adjust the sensors and coding so the car is able to move smoothly. I also plan to program an initiation button to make the process of turning the car on an off more efficiant. 


<!--For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 
-->
# First Milestone (6/14/24)

 <iframe width="560" height="315" src="https://www.youtube.com/embed/tr8M64cWmQk?si=XJblCqyB5Nor48RA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
 





The project I chose to build this summer at BlueStamp is the self drving, or autonomous car. The self driving car project,  is a robot that is able to navigate through a course with no human intervention. The end result car should be able to detect and navigate around crosswalks, moving objects, static objects, vehicles, as well as stay in the correct lane.  For my first milestone, I have constructed a basic circuit on the drive base that allows the robot car to move forward continously. From a technical standpoint, the circiuit works by deriving power provided by the 9v battery that is then directed to the arduino and distributed to the motors. Because of this, the car is moving continuously in a straight plane with no stoping point or directional change. Some challenges I faced in the construction so far are having to restart due to not having the correct instruction manual, and reciving motors that did not have the same base speed. I eventually plan to fix this imbalance in milestone 2, along with adding directional commands using the line tracking and object detectiting sensors. 

<!--For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project
--> 

# Schematics (Main Project)

<img width="661" alt="Screenshot 2024-06-24 at 12 04 18 PM" src="https://github.com/TanviNulkar/Tanvi-BlueStamp-Portfolio/assets/172317262/a6e51f5b-b35e-476f-aca7-fe73c7500c1f"> 



*schematic credited to sunfounder.com*

# Main Project (Track Construction)

(insert photo here madam)

For my project, I elected to construct a track for the car to run on. constructed of _____, ________, and ________, the car provides a clear and clean course for the car to demonstrate it's autonomous abilites. Littered with obstacles of multiple kinds, the car showcases its ability to handle a myriad of obstacles and maintain consistant accuracy. 


# Starter Project

<iframe width="560" height="315" src="https://www.youtube.com/embed/RTJOozuSB_E?si=Yt2DHv0V328usJpQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>



For my starter project, I chose the BlueStamp Arduino starter. Using a breadboard, arduino, wires, button, and motor, I created a circuit that, when the button is pressed makes the motor spin. This project works by deriving power from the computer which is distributed by the arduino to the circuit. the motor is allowed to spin when the button is pressed, and the circuit is complete.  I chose this project because I thought that it would give me practice in skills I would need for my main project, the self driving car.  The main challenge I had when creating this project was soldering. It was a struggle to solder the arduino to the sheild at the angle required, forcing me to become creative with my soldering technique. Next, I will use these skills to aid in the construction of my self driving car.


# Code for Starter Project 


```c++
const int buttonPin=2;  //the number of the pushbutton pin
const int motorPin=9;  // the number of the motor pin

//variables will change:
int buttonState=2;  //variable for reading the pushbutton status

void setup() {
  pinMode(motorPin,OUTPUT);
  pinMode(buttonPin,INPUT);
 }

void loop() {
  buttonState = digitalRead(buttonPin);
  //check if the pushbutton is pressed. If it is, the buttonState is HIGH:
    if(buttonState == LOW) {
      // turn MOTOR on:
        digitalWrite(motorPin, LOW);
      } else if(buttonState == HIGH) {
        // turn MOTOR off:
        digitalWrite(motorPin, HIGH);
      }
  }
```



<!--# Schematics (starter project)
Here's where you'll put images of your schematics.
[Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 
-->



<!--

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
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.-->
