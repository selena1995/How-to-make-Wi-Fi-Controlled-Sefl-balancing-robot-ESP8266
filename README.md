# How-to-make-Wi-Fi-Controlled-Sefl-balancing-robot-ESP8266
I have already made so many wifi-controlled robots using ESP8266. Today, l am making wifi controlled bot like before but it's self-balanced.
I have already made so many wifi-controlled robots at home using ESP8266. Now, I have decided to make the same wifi-controlled bot but with an upgraded version. So here I am going to make a self-balancing bot. I really hope this will be more interesting than before. so, let's make it together...
And yes of course l have tried to make it as simple as possible and assure that anyone can make it easy with this tutorial...


WHAT WILL YOU LEARN FROM THIS TUTORIAL
About Node MCU
how to upload code in esp8266
about l298n
what is a self-balancing robot
how to make PCB
why should we use PCBs in our project
how to control the bot via mobile phone


NODE MCU
NodeMCU is an open-source IoT platform. It includes firmware that runs on the ESP8266 Wi-Fi SoC from Espressif Systems, and hardware that is based on the ESP-12 module. The term "NodeMCU" by default refers to the firmware rather than the development kits. The firmware uses the Lua scripting language.

WHY NODE MCU/ESP8266 IS USED IN IOT PROJECTS?
ESP8266 has very low cost and high features which makes it an ideal module for the Internet Of Things (IoT). It can be used in any application that requires it to connect a device to the local network or the internet. NodeMCU Development Board/kit v1. 0 (Version2) NodeMCU is an Arduino-like device.


HOW TO UPLOAD THE CODE IN NODE MCU?
Please follow the steps below, If you are new and not well familiar with this ESP8266 module, or facing a problem while uploading the code

1.First Download the code from the link below. Now open Arduino and Go to File~New.

2.Now a new window will appear. Next, Delete all the existing code and Paste the given code.

3.In the code, you will find Additional Board Manager URL now copy the URL and do the next step. For Different OS you have a different option. MAC: Go to Arduino ~ Preferences Windows: Fille ~ Preferences

4.Now Paste it in the Additional Board Manager URL section and press Ok. Now go to Tools ~ Board ~ Boards Manager Search for ‘ESP8266‘ and install the latest version.
5.After the installation Then go to Tools ~ Board and then select the ESP-12E Module. So, The Board is selected Now.

6.Next, Select the Right COM Port.

7.Then compile the Programme First and then Upload it to NodeMCU. After a few seconds, the code will be compiled and then Uploaded to NodeMCU Car.


WHAT IS L298N AND WHY USE IT?
The L298N is an integrated monolithic circuit in a 15- lead Multiwatt and PowerSO20 packages. It is a high voltage, a high current dual full-bridge driver designed to accept standard TTL logic level sand drive inductive loads such as relays, solenoids, DC, and stepping motors.
The L298N is a dual H-Bridge motor driver which allows speed and direction control of two DC motors at the same time. The module can drive DC motors that have voltages between 5 and 35V, with a peak current up to 2A.


WHAT IS THE SELF-BALANCING ROBOT?
The two-wheeled self-balancing robot represents a robotic platform with two independently actuated wheels and a center of gravity above the axis of the rotation of the wheels. The behavior of the robot is similar to the classical mechanical system of an inverted pendulum.



What does PCB mean?
printed circuit board

A printed circuit board, PC board, or PCB, is a non-conductive material with conductive lines printed or etched. Electronic components are mounted on the board and the traces connect the components together to form a working circuit or assembly.


Why should we use PCBs in our project?
An effective PCB design can help in reducing the chances of errors and also the possibilities of short circuits. PCBs have a vital role in this modern-day as technology is improving daily. These circuit boards are the foundation of electronic products as they are used in almost every electronic device.


HOW TO MAKE PCB BOARDS EASILY?
Making PCB boards at home is possible but it's really very hard to make and takes a lot of time. But it is really very easy if you purchase them from any PCB manufacturing company. Usually, l design the circuit diagram and the Garber file () in EasyEDA ln my case, l always prefer to use service from JLCPCB to make my desired PCB board. they are very professional and also provide very fast delivery which helps me to complete my project in a short amount of time. one more thing I want to share, i.e; their price of PCB board making is really very less. They have also provided this coupon through which I have paid only a minimum amount of charge. In my next project, l am going to take their JLCPCB SMT service which will fulfill my money&time saving needs. I can make anything as they have more than 200k+ in-stock components. As an electronics engineer and a project maker, l almost always prefer to make my electronics projects using PCB and if you ask my personal choice, the JLCPCB is my best choice for making customized PCBs

if you sign up through this link:https://jlcpcb.com/IAT or make it an affiliate link if you sign up through JLCPCB, you can get $27 coupons after registering successfully.


HOW TO ASSEMBLE THE HARDWARE PARTS?
In this step, we have to make the robot chassis first. For this, I am going to use a small piece of PVC sheet to make the robot chassis. Then l have attached two 500rpm gear motors using a clamp and some hot glue. Then l have attached the wheels to the motor terminals and tightened the screws properly.

Then l have attached the 18650 li-ion battery holder with the robot chassis using double-sided tape.

next, l have attached some wires into the positive and negative terminal of motors and then connected the terminals with the l298n motor driver module.

Now I have made other connections by following the circuit diagram.

l have already provided the circuit diagram with this article for your reference.


HOW TO CONTROL THE ROBOT USING A SMARTPHONE?
This is the last & final step for this project. Once you have done making the robot successfully by following the steps, then you have to install a software named "NodeMCU_Car", which is easily available in play-store, on your android mobile phone.


Please follow the steps, once you have done the installation successfully-

turn on the wifi of your mobile phone
Search for the available network. Here, in this case, the name will be "Wifi Robot by Monalisa"
connect with the available network
now open the android app named "NodeMCU_Car"
now connect with the robot
thus it connected successfully. let's play with the bot.


