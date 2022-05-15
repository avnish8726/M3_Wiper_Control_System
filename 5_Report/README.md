# ※⁜ ABSTRACT ※⁜

The automotive industry has been relentlessly researching different ways to harness the power of computing and to make a hopeful shift from mechanisation to 
automation 
to aid advancements in the development of safety, reliability, and entertainment technologies for vehicles over the last few decades. Every traffic incident that 
occurs 
throughout the world 24 hours a day has a common cause: attention. As a result, reducing these distractions is always in everyone's best interests.

When driving in the rain or snow, the driver's visibility is hampered, posing a serious hazard to life. The wiper system comes to the rescue in this case. 
Traditional 
wiper systems, on the other hand, necessitate regular driver attention to alter wiper speed dependent on the severity of rain or snow. Because this manual wiper 
speed 
change diverts the driver's attention, it may result in an accident, rendering the entire system useless.

To address this issue, the 'Wiper Control System' project is being developed. The goal of this project is to start the automated wiper action by detecting the 
intensity 
of the rain or snow and adjusting the wiper speed accordingly. This automatic wiper system consists of a sensing unit, a controller with a 'STM32F407VG' 
Microcontroller 
at its heart, and a motor unit that drives the wiper's arm, allowing for easier wiping.

The proof of concept stage is investigated in this project, so the initial press of a button is regarded to be the starting of ignition. The next three button clicks 
are considered to be the multiple speed control levels supplied by the proposed controller, which range from low to medium to high. The final button press is 
considered 
to be the ignition switch off. The blue, green, and orange LEDs blink in the desired manner to represent the movement of the wiper arm from left to right and back.


# ※⁜ Project Report ※⁜

The project's goal is to start the automatic wipers by sensing the intensity of the rain or snow and increasing or reducing the wiper speed accordingly. This automatic 
wiper system consists of a sensing unit, a controller with a 'STM32F407VG' Microcontroller at its heart, and a motor unit that moves the wiper arm, allowing for easier 
cleaning.


# ※⁜ Features ※⁜

* It can operate wipers without the need for human involvement.
* Low speed, medium speed, and fast speed are the three control options available.
* It's reliable and simple to set up.
* It is very quick to compute and detect to object.

## ※⁜ Identifying the Requirements ※⁜

      Technologies and Tools Used:
      
               * Development Tool: Github Website.
               * IDE Used : STM32CubeIDE.
               * Languages Used: C Language, Makefile.
               * Toolchain : GNU.
               * Emulator : Qemu.
               * Packages : Xpack packages (Windows Build Tools, Open OCD, Qemu).
               * Environment : Windows Subsytem for Linux (WSL).



## ※⁜ High Level Requirements ※⁜
| ID | Description | Status |
|--|--|--|
| HR01 |It shall Lock the car  | Implemented |
| HR02 | It shall Unlock the car | Implemented |
| HR03 | It shall Activate Wiper System |  Implemented |
| HR04 | It shall Deactivate Wiper System |  Implemented |



## ※⁜ Low Level Requirements ※⁜

| ID | Description |  Status |
|--|--|--|
| LR01 |If the user pressed the Button ONCE - ON LED RED  |  Implemented |
| LR02 | If the user pressed the Button TWICE - OFF LED RED| Implemented |
 LR03 | If the user pressed the Button THREE times - ON BLUE, GREEN, ORANGE | Implemented |
| LR04 | If the user pressed the Button FOUR times - IN ORANGE, GREEN, BLUE | Implemented |

## ※⁜ Architecture ※⁜

* Block Diagram

![Block Diagram](https://github.com/avnish8726/M3_Wiper_Control_System/blob/main/2_Design/Block%20Diagram%20Of%20Wiper%20Control%20System.png)

* Low level flowchart

![Image](https://github.com/avnish8726/M3_Wiper_Control_System/blob/main/2_Design/Low%20Level%20Flowchart.drawio.png)

* High level flowchart

![image](https://github.com/avnish8726/M3_Wiper_Control_System/blob/main/2_Design/High%20Level%20Flowchart.drawio.png)

## ※⁜ SWOT Analysis ※⁜
![](https://github.com/avnish8726/M3_Wiper_Control_System/blob/main/6_Output/Others/Swot%20analysis.png)

# ※⁜ 4W's & 1H ※⁜

* **What**  : Automatic Wiper Control System using the microcontroller STM32F407VG.
* **When**  : When the visibility of the road is compromised due to rain, snow, dust.
* **Where** : On the windshield of the vehicle.
* **Why**   : To improve the visibility of the road, to prevent accidents and to ensure safe travel.
* **How**   : By designing an embedded system controller to control the wiper arm action according to severity of conditions without human intervention.

# ※⁜ Output Images ※⁜
1. user button and hold it for two seconds
   ![image](https://github.com/avnish8726/M3_Wiper_Control_System/blob/main/6_Output/Others/Engine%20ON%20state.jpg)
2. Wiper Speed low 
![image](https://github.com/avnish8726/M3_Wiper_Control_System/blob/main/6_Output/Others/Wiper%20Speed%20Low.jpg)
3. Wiper speed medium 

![image](https://github.com/avnish8726/M3_Wiper_Control_System/blob/main/6_Output/Others/Wiper%20Speed%20Medium.jpg)

4. Wiper speed high
![image](https://github.com/avnish8726/M3_Wiper_Control_System/blob/main/6_Output/Others/Wiper%20Speed%20High.jpg)

5. user button is pressed and held for 2 seconds, the red LED is off
![image](https://github.com/avnish8726/M3_Wiper_Control_System/blob/main/6_Output/Others/Engine%20OFF%20State.jpg)

#※⁜ ADVANTAGES ※⁜

* Turn off the irrigation system during wet seasons to save money. As a result, electricity bills are reduced.
* Rain sensors collect water during rainstorms and store it for use throughout the summer and winter.
* As a result, rain sensor-based equipment such as windshield wipers and irrigation systems survive longer because they only operate when needed.
* it is simple to use
* As a consequence less energy is consumed
* Rain sensors based systems are extremely simple to install
* Individual rain sensors are fairly inexpensive.

# ※⁜ DISADVANTAGE ※⁜

* When the rain sensor is directly hit by water. the mechanism became active
* When more components, such as a rain sensor, are required, the total cost of the system rises.
* Rain sensors must make a decision within a few minutes to avoid erroneous detection of rain.

               
