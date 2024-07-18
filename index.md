# Autonomous Car 
The self driving car project is a miniture representation of  autonomous of vehicular transportation. With the ability to drive, navigate obstacles, modify pace to match surroundings, detect other vehicles and moving objects, the car demonstrates the future of transportation. 








| **Name** | **School** | **Field of Intrest** | **Grade** |
|:--:|:--:|:--:|:--:|
|Tanvi N. | Notre Dame San Jose | MedTech |  Incoming Sophmore 

![Tanvi_N](https://github.com/user-attachments/assets/f06afc21-4bbd-4709-82ad-e549635c4e95)



# Modifications (7/17/24)

<iframe width="560" height="315" src="https://www.youtube.com/embed/8s18SXfUqbU?si=mNxjnmbxFKdWFP-4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


the car I elected to build this summer at BlueStamp engineering is based off the autonomous car project by sunfounder.org. From their original design, I have modified the project significantly. I have added three more ultrasonic sensors, headlights, side-lights, tail-lights, programmed the tail-lights, a piezzo passive buzzer, and a programmed on/off switch. in addition to adding components, I also removed the line track sensor seen in the original design. This was removed because it no longerwas required for my desired outcome for the project. I added all of the modifications listed prior to give the car the ability to preform alike to modern day self driving cars, such as Tesla and Waymo. This led to the incorporation of more sensors and physical features, both that would allow for greater representation. 

from the standpoint of sensors, the additional ultrasonic sensors allow for the car to have a greatrer understanding of its own environment. This added feature is accompanied by the removal of the line track sensor, as I deemed it unecessary and was therefore using much needed GPIO pins. For the physical features, I added the headlights, sidelights, and tailights, to further give the impression that the car was a model of the larger and much more complex self driving cars. the headlights and sidelights run through a basic circuit by being connected to power and ground. in the case of the tailights, the tailights are programmed to signal to spectators the direction the car is to turn. The left and right lights are individually programmed. this gives the car the ability to signal left and rght movements, as well as breaking and stopping. For audio features, I had the desire to add a 'horn'. My vision for the horn was for it to go off, or produce sound, when the car detected an object that was too close (less than 5 inches). For this purpose I have used the piezo passive buzzer. This buzzer has been programmed to go off whenever an object is detected within 3 inches of the frontmost ultrasonic sensor. Finally, for convienence purposes, I have also added an initiation or on/off switch. This is to allow for greater controll over powering on and off, as well as further demonstration of the tailight coding. through my code, I have programmed the car to only preform its designated functions when the switch is turned on, and to stop all functions when off. the car is also programmed to have both tailights on when the initiation switch is put into the 'off' state. 

To support the addition of hardware, I also 3D printed 4 standoffs and 2 upper levels to support the 2 additional untrasonic sensors, piezobuzzer, and all of the electronics that access power and ground through the elevated breadboards. The levels also served the purpose of creating space closer to the acrylic board for pieces such as additional breadboards, the initiation switch, and the LED wiring. 

overall, the modifications I have added to the original car kit or design by sunfounder.org, have all been added with the aim of giving the car the level of control and apperence of modern day autonomouds vehicles. All modifications were added to my current ability as an engineer. If given more time, I would hve attempted to add a covering for all the wires to give a streamlined apperence, and gone back to the code to make it smoother and more efficiant. 


  
# Final Milestone (7/10/24)


for my third milestone, and final milestone, I have smoothed out my code, added three more ultrasonic sensors, and an initiation switch.  the ultrasonic sensors were added to give the car a better understanding of it's environment and more control over navigation. I added the on/off switch to minimize the hassle of powering the robot on/off. From a technical standpoint, the ultrasonic sensors work by transmitting infrared waves, and based off the frequency of waves returning to the sensor, the robot is able to determine how far it is from a given object. Furthermore, the on/off switch works predominantly through code, where the arduino is told, that when the switch is turned on the car must preform the code, and when the switch is turned off to stop all movement. Reflecting on my time at BlueStamp, I faced quite a few challenges, some of them being the imbalanced motors, difficulty interpreting instructions, and unfimiliarity with electronic devices and instruments. I overcame all of these challenges through research and diligent work. On the flipside, some of my biggest triumphs at BlueStamp were finally getting the car to move in all four directions, independently being able to program my autonomous car, and implementing modifications independently. Following the conclusion of BlueStamp, I hope to constinue to learn more about robotics and how to create a further autonomous robots using a variety of techniques.


# Key Lessons Learned

over the course of my six weeks at BlueStamp engineering, I learned many lessons that I will carry on into my future engineering endevors. However, there are some lessons that have resonated with me the most. These lessons are to: always save code, always save code under a deciperable or destinguishable tag, closely document changes made, pay close attention to wiring (as to not short circuit electronics), and to proceeed with a calm and patient mindset. These particular lessons are those that I have learned through major errors that either led to me having to restart a particular componet or to me wasting valuable time. Given these lesssons learned, I will undoubtedly be using them in the future to prevent any mistakes alike to the ones I made during this project. 



# Second Milestone (6/26/24)



<iframe width="560" height="315" src="https://www.youtube.com/embed/GFu1FAuYxyo?si=fPRPxAk2z6cI7xVP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


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


![IMG_1438](https://github.com/user-attachments/assets/669fda2d-0687-48db-a911-bc6b13f63898)

![IMG_1436](https://github.com/user-attachments/assets/886e7d45-65cd-4bb7-a7c0-4328e9a15f52)


*Schematics created by Tanvi N. on ProCreate*




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

<!--
#Bill of Materials (starter project)
| arduino | self explanatory| $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| male to male wires  | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| motor | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
-->



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
