# Autonomous Car 
<h3> The self driving car project is a miniature representation of  autonomous of vehicular transportation. With the ability to drive, navigate obstacles, modify pace to match surroundings, detect other vehicles and moving objects, the car demonstrates the future of transportation. </h3>








| **Name** | **School** | **Field of Intrest** | **Grade** |
|:--:|:--:|:--:|:--:|
|Tanvi N. | Notre Dame San Jose | MedTech |  Incoming Sophmore 



 ![Tanvi_N Medium](https://github.com/user-attachments/assets/cba16d9a-66a4-4d3e-8b66-dd4184a04624)



# Modifications (7/17/24)

<iframe width="560" height="315" src="https://www.youtube.com/embed/8s18SXfUqbU?si=mNxjnmbxFKdWFP-4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


the car I elected to build this summer at BlueStamp engineering is based off the autonomous car project by sunfounder.org. From their original design, I have modified the project significantly. I have added three more ultrasonic sensors, headlights, side-lights, tail-lights, programmed the tail-lights, a piezzo passive buzzer, and a programmed on/off switch. in addition to adding components, I also removed the line track sensor seen in the original design. This was removed because it no longerwas required for my desired outcome for the project. I added all of the modifications listed prior to give the car the ability to preform alike to modern day self driving cars, such as Tesla and Waymo. This led to the incorporation of more sensors and physical features, both that would allow for greater representation. 

from the standpoint of sensors, the additional ultrasonic sensors allow for the car to have a greatrer understanding of its own environment. This added feature is accompanied by the removal of the line track sensor, as I deemed it unecessary and was therefore using much needed GPIO pins. For the physical features, I added the headlights, sidelights, and tailights, to further give the impression that the car was a model of the larger and much more complex self driving cars. the headlights and sidelights run through a basic circuit by being connected to power and ground. in the case of the tailights, the tailights are programmed to signal to spectators the direction the car is to turn. The left and right lights are individually programmed. this gives the car the ability to signal left and rght movements, as well as breaking and stopping. For audio features, I had the desire to add a 'horn'. My vision for the horn was for it to go off, or produce sound, when the car detected an object that was too close (less than 5 inches). For this purpose I have used the piezo passive buzzer. This buzzer has been programmed to go off whenever an object is detected within 3 inches of the frontmost ultrasonic sensor. Finally, for convienence purposes, I have also added an initiation or on/off switch. This is to allow for greater controll over powering on and off, as well as further demonstration of the tailight coding. through my code, I have programmed the car to only preform its designated functions when the switch is turned on, and to stop all functions when off. the car is also programmed to have both tailights on when the initiation switch is put into the 'off' state. 

To support the addition of hardware, I also 3D printed 4 standoffs and 2 upper levels to support the 2 additional untrasonic sensors, piezobuzzer, and all of the electronics that access power and ground through the elevated breadboards. The levels also served the purpose of creating space closer to the acrylic board for pieces such as additional breadboards, the initiation switch, and the LED wiring. 

overall, the modifications I have added to the original car kit or design by sunfounder.org, have all been added with the aim of giving the car the level of control and apperence of modern day autonomouds vehicles. All modifications were added to my current ability as an engineer. If given more time, I would hve attempted to add a covering for all the wires to give a streamlined apperence, and gone back to the code to make it smoother and more efficiant. 

<h2> 3D printing</h2>

When adding my modifications, it soon became clear that I was running out of space on the bottom acrylic plate. To solve this issue I resolved to add a elevated layer, or level, to allow for space to mount the extra electronics and sensors. To create this layer, I initially elected to construct the structure using custom printed standoffs, to act as pillars, and cardboard to be the main platform (figure 1a). This design was quite durable and sturdy, but as time drew on, I desired for the apperence of the structure to look more finished and elevated, thus I turned to 3D printing to create this custom platforms. (figure 1b). To secure the platforms, I printed the standoffs to screw into some extra holes on the acrylic plate. I had a few issues with this, such as the standoffs being to wide or tiny for the screws to fasten the standoffs through the plate. Eventually, I learned that I have accidently turned off some features that were leading to prints being printed a couple millimeters larger than the original design. 

<h2> Programmed LED Tailights</h2>

One of the most significant and time intesive modifications I have added to my project by far, are the tailights. The tailights function just as those in real cars, signaling to spectators when the car is turning left or right, moving backwards or when the car is coming to a full stop. I have individually programmed the left and right tailights, which are each connected to ground and their own respective GPIO pins. 
 
  
  
 [IMG_9292 Small](https://github.com/user-attachments/assets/b46c6b1d-69c5-41d1-8fcc-ffd3755a77b2) 
 figure (1a): original cardboard platforms supported by 3d printed standoffs

 ![IMG_9436 Small](https://github.com/user-attachments/assets/55faa3c9-3ca0-49f0-a32a-4e61d68051f1)
 figure(1b): final 3D printed platforms with all electronics mounted 


 

  
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

# Schematics for Autonomous Car 



![IMG_1438 Medium](https://github.com/user-attachments/assets/73f62bb9-f830-4b09-85c9-f3d475f6b432)

![IMG_1436 Medium](https://github.com/user-attachments/assets/06761793-e918-4066-9cab-fa058cca8c9d)


*Schematics created by Tanvi N. on ProCreate*



# Code for Autonomous Car 

<pre style="background:#fdfdfd; border:none; height:30pc">

```c++


//const int IR_RECEIVE_PIN=12;

const int switchPin= 13;

const int A_1B = 5;
const int A_1A = 6;
const int B_1B = 9;
const int B_1A = 10;

const int lineTrack=2;

const int rightIR=7;
const int leftIR=8;

const int trigPin=3;
const int echoPin=4;

const int trigPin2= A4;//ultrasound back right 
const int echoPin2= A5;

const int trigPin3= A0;//ultrasound backleft 
const int echoPin3= A3;

const int trigPin4=1;
const int echoPin4=2;

const int ledpin1=12;
const int ledpin2=11;

const int buzzerPin= A2;

int speedA=175;
int speedB=133;
int switchState=0;

int speedBreakA=330;
int speedBreakB=275;

float readSensorData(){
  digitalWrite(trigPin,LOW);
  delayMicroseconds(2);
  digitalWrite(trigPin,HIGH);
  delayMicroseconds(10);
  digitalWrite(trigPin,LOW);
  float distance= pulseIn (echoPin, HIGH)/58.00;
  return distance;
}

  float readSensorData2(){
  digitalWrite(trigPin2,LOW);
  delayMicroseconds(2);
  digitalWrite(trigPin2,HIGH);
  delayMicroseconds(10);
  digitalWrite(trigPin2,LOW);
  float distance= pulseIn (echoPin2, HIGH)/58.00;
  return distance;
}

  float readSensorData3(){
  digitalWrite(trigPin3,LOW);
  delayMicroseconds(2);
  digitalWrite(trigPin3,HIGH);
  delayMicroseconds(10);
  digitalWrite(trigPin3,LOW);
  float distance= pulseIn (echoPin3, HIGH)/58.00;
  return distance;
}
  float readSensorData4(){
  digitalWrite(trigPin4,LOW);
  delayMicroseconds(2);
  digitalWrite(trigPin4,HIGH);
  delayMicroseconds(10);
  digitalWrite(trigPin4,LOW);
  float distance= pulseIn (echoPin4, HIGH)/58.00;
  return distance;
}


 void stopMove() {
  digitalWrite(A_1B,LOW);
  digitalWrite(A_1A,LOW);
  digitalWrite(B_1B,LOW);
  digitalWrite(B_1A,LOW);
}
  void moveForward() {
  digitalWrite(A_1B,LOW);
  analogWrite(A_1A,speedA);
  analogWrite(B_1B,speedB);
  digitalWrite(B_1A,LOW);
  
}
  void moveBackwards() {
  analogWrite(A_1B,speedA);
  digitalWrite(A_1A,LOW);
  digitalWrite(B_1B,LOW);
  analogWrite(B_1A,speedB);
}
  void turnLeft() {
  digitalWrite(A_1B,LOW);
  analogWrite(A_1A,speedA);
  digitalWrite(B_1B,LOW);
  analogWrite(B_1A,speedB);
}
  void turnRight() {
  analogWrite(A_1B,speedA);
  digitalWrite(A_1A,LOW);
  digitalWrite(B_1B,speedB);
  analogWrite(B_1A,LOW);
}
  void moveLeft(int speed ){
  analogWrite(A_1B,0);
  analogWrite(A_1A,0);
  analogWrite(B_1A,speed);
  analogWrite(B_1B,0);
  
}
  void moveRight(int speed){
  analogWrite(A_1B,0);
  analogWrite(A_1A,speed);
  analogWrite(B_1A,0);
  analogWrite(B_1B,0);
  
}
  void turnBackwards(int speed){
  analogWrite(A_1B,speed);
  analogWrite(A_1A,0);
  analogWrite(B_1A,0);
  analogWrite(B_1B,speed);
}
  void stopTurn(){
  analogWrite(A_1B,0);
  analogWrite(A_1A,0);
  analogWrite(B_1A,0);
  analogWrite(B_1B,0);
}
  void backLeft(int speed6){
  analogWrite(A_1B,speed6);
  analogWrite(A_1A,0);
  analogWrite(B_1A,0);
  analogWrite(B_1B,0);
  
}
  void backRight(int speed6){
  analogWrite(A_1B,0);
  analogWrite(A_1A,0);
  analogWrite(B_1B,0);
  analogWrite(B_1B,speed6); 

}
  void speedForward(){
  analogWrite(A_1B,0);
  analogWrite(A_1A,speedBreakA);
  analogWrite(B_1A,speedBreakB);
  analogWrite(B_1B,0);
}

  void ledRight(){
  digitalWrite(11,HIGH);
  digitalWrite(12,LOW);
}
  void ledLeft(){
  digitalWrite(11,LOW);
  digitalWrite(12,HIGH);
}
  void stopLed(){
  digitalWrite(11,LOW);
  digitalWrite(12,LOW);
}
  void ledLeftBlink(){
  ledLeft();
  delay(150);
  ledLeft();
  delay(150);
  ledLeft();
  delay(150);
  stopLed();
}
  void ledRightBlink(){
  ledRight();
  delay(150);
  ledRight();
  delay(150);
  ledRight();
  delay(150);
  stopLed();
}
  void fullStop(){
  digitalWrite(11,HIGH);
  digitalWrite(12,HIGH);
}
  void buzzerON(){
  digitalWrite(buzzerPin,HIGH);
}
  void buzzerOFF(){
  digitalWrite(buzzerPin,LOW);
}



  void setup (){
    Serial.begin(9600);
  //motor
  pinMode(A_1B, OUTPUT);
  pinMode(A_1A, OUTPUT);
  pinMode(B_1B, OUTPUT);
  pinMode(B_1A, OUTPUT);

  pinMode(switchPin, INPUT);

  //line track 
  pinMode(lineTrack,INPUT);
  Serial.begin(9600);

  //IR obstacle 
  pinMode(leftIR,INPUT);
  pinMode(rightIR,INPUT);
  //ultra sonic 
  Serial.begin(9600);
  pinMode(echoPin,INPUT);
  pinMode(trigPin,OUTPUT);

  pinMode(echoPin2,INPUT);
  pinMode(trigPin2,OUTPUT);

  pinMode(echoPin3,INPUT);
  pinMode(trigPin3,OUTPUT);

  pinMode(echoPin4,INPUT);
  pinMode(trigPin4,OUTPUT);

  //LEDs 
  pinMode(12,OUTPUT);
  pinMode(11,OUTPUT);

  //buzzer 
  pinMode(A2,OUTPUT);
}






  void loop(){
  int speed=200;
  int lineColor = digitalRead(lineTrack);//0:white 1:black
  int switchState= digitalRead(switchPin);

if (switchState==HIGH){
  
  moveForward();
  buzzerOFF();
  stopLed();
    
    int left = digitalRead(leftIR); 
    int right = digitalRead(rightIR);
    int speed6=200;
  
  
     if (left && !right){
      backLeft(speed6);
      ledLeftBlink();
      delay(500);
      stopLed();
      moveBackwards();
      moveForward();
      delay(100);
      
      
    

 
  }else if (!left && right){
      backRight(speed6);
      ledRightBlink();
      delay(500);
      moveBackwards();
      stopLed();
      moveForward();
      delay(100);
      
  }
  


    float distance=readSensorData();
      if((distance <8 && distance >2) or (!left && !right)){
          buzzerON();
          delay(200);
          buzzerOFF();
          moveBackwards();
          delay(500);
          turnLeft();
          delay(300); 
     // }else if (distance >10 and distance<40){
        //speedForward();
        //delay(500);
      }
      

    float distance2=readSensorData2();
      if (distance2 <15 && distance2 >10){
        moveLeft(speed);
        moveForward();
      }else if (distance2 <30 && distance2 >20) {
        turnLeft();
        delay(100);
        ledLeft();
        delay(500);
        moveForward();
        stopLed();
      }

    float distance3=readSensorData3();
      if (distance3 <15 && distance3 >10){
       moveRight(speed);
       moveForward();
      }else if (distance3<30 && distance3>20){
      turnRight();
      delay(200);
      ledRight();
      delay(500);
      moveForward();
      stopLed();
    }
    float distance4=readSensorData();
      if (distance <5){
       delay(100);
       fullStop();
       delay(200);
       stopMove();
       delay(200);
       moveLeft(speed);
       moveForward();
       delay(200);
       stopLed();
    }
   
      
}
  
  else if (switchState==LOW) {
  stopMove();
  fullStop();

  }
  }

```
</pre>

# Bill of Materials for Autonomous Car 

<h2> Additional Materials Used </h2>

 | **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Ultrasonic sensor x4 | obstacle detection| ~$4.50 each | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|LED x8 | tailights, headlights, and sidlights| ~$0.34 each or multicolored pack of 100 for ~$6.35| <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| piezzo passive buzzer | horn equivelent| ~$1.73| <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Mini Breadbboard x6| | ~$4.00 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> | 
|on/off switch|  | $8.99 for a pack of ten| <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| 9v battery|  | $9.51 for a pack of ten | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

<h2> Materials used from Sunfounder iot/ self driving car kit </h2>

[SunFounder self driving car kit - LINK]([url](https://www.sunfounder.com/products/sunfounder-3-in-1-iot-smart-car-learning-ultimate-starter-kit?_pos=1&_sid=a6fa33b13&_ss=r))


|**Part**|**Note**|
|:--:|:--:|
| 220 OHM resistors | control current to LED's |
| M3x6 screws | to fasten somponents  | 
| M3x30 screws | to fasten larger components | 
| M3 nuts  | hold screws in place | 
| Arduino Uno Board | |
| L9110 module  | motor driver | 
| TT wheel | | 
| TT motor| to move the wheels| 
| 1" universal wheels |help the car supposrt itself| 
| Acrylic plate | main component for car body |
| Jump wires M/M | wiring  |
| Jump Wires F/F | wiring |






# Starter Project -- BlueStamp Arduino Starter
<h2> The BlueStamp Arduino Starter is a loosly guided project that directs students through the basics of coding, circuits, wiring, and sensors. Students are educated on various outputs and inputs they can use to make their projects as they wish.</h2>




<iframe width="560" height="315" src="https://www.youtube.com/embed/RTJOozuSB_E?si=Yt2DHv0V328usJpQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>



For my starter project, I chose the BlueStamp Arduino starter. Using a breadboard, arduino, wires, button, and motor, I created a circuit that, when the button is pressed makes the motor spin. This project works by deriving power from the computer which is distributed by the arduino to the circuit. the motor is allowed to spin when the button is pressed, and the circuit is complete.  I chose this project because I thought that it would give me practice in skills I would need for my main project, the self driving car.  The main challenge I had when creating this project was soldering. It was a struggle to solder the arduino to the sheild at the angle required, forcing me to become creative with my soldering technique. Next, I will use these skills to aid in the construction of my self driving car.


# Schematic of starter project
![IMG_1440 Medium](https://github.com/user-attachments/assets/ea2d11c0-ed12-4328-918c-d5b5ac25806e)
*schematic created by Tanvi N. With procreate*


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







#Bill of Materials (starter project)
|**Part**|**Notes**|**Link**|
|:-:|:-:|:-:|
| arduino uno | | ~$27.60 | [LINK]([url](https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/ref=asc_df_B008GRTSV6/?tag=hyprod-20&linkCode=df0&hvadid=692875362841&hvpos=&hvnetw=g&hvrand=16666681611808991928&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032183&hvtargid=pla-2281435179978&psc=1&mcid=8d4415853f19330eb6cb8c1e7f18a8ed&hvocijid=16666681611808991928-B008GRTSV6-&hvexpln=73&gad_source=1))|
|QTEATAK button  | used to initiate motors | $5.99 for a set of one hundred and twenty |[LINK]([url](https://www.amazon.com/QTEATAK-Momentary-Tactile-Button-Switch/dp/B07VSNN9S2/ref=asc_df_B07VSNN9S2/?tag=hyprod-20&linkCode=df0&hvadid=692875362841&hvpos=&hvnetw=g&hvrand=3902747494344092328&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032183&hvtargid=pla-2281435178058&psc=1&mcid=3105465e56ba3d87acce02ed42044e08&hvocijid=3902747494344092328-B07VSNN9S2-&hvexpln=73&gad_source=1)) |
| DC motor || $6.99 for a pack of six | [LINK]([url](https://www.amazon.com/Topoox-15000-16500RPM-Electric-Science-Experiments/dp/B073Q2Y3RC/ref=asc_df_B073Q2Y3RC/?tag=hyprod-20&linkCode=df0&hvadid=692875362841&hvpos=&hvnetw=g&hvrand=2476635652248431690&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032183&hvtargid=pla-2281435178098&psc=1&mcid=57669cff5557399f96c7b69fe1a26a6f&hvocijid=2476635652248431690-B073Q2Y3RC-&hvexpln=73&gad_source=1)) |








<!--
# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.-->
