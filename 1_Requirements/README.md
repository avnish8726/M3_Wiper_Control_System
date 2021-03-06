# ※⁜ Description ※⁜

In vehicles, a wiper control system replaces the standard wiper blade with an electrical component. In this setup, the ignition button (on the motor) will be    controlled 
by a single switch in the ACC position. Switch on the wiper system with a second press, then vary the wiper speed with a third press, and finally turn off the motor 
with a fourth press. All of this was done with the help of LEDs and a simulation tool.


# ※⁜ Features ※⁜

* It can operate wipers without the need for human involvement.
* Low speed, medium speed, and fast speed are the three control options available.
* It's reliable and simple to set up.
* It is very quick to compute and detect to object


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



# ※⁜ SWOT Analysis ※⁜
![](https://github.com/avnish8726/M3_Wiper_Control_System/blob/main/6_Output/Others/Swot%20analysis.png)




# ※⁜ 4W's & 1H ※⁜

* **What**  : Automatic Wiper Control System using the microcontroller STM32F407VG.
* **When**  : When the visibility of the road is compromised due to rain, snow, dust.
* **Where** : On the windshield of the vehicle.
* **Why**   : To improve the visibility of the road, to prevent accidents and to ensure safe travel.
* **How**   : By designing an embedded system controller to control the wiper arm action according to severity of conditions without human intervention.
