# Forest-fire-detector
I have made this project in my college I have I had used nodeMCU ir sensor buzzer

**Objective**
The primary objective of this project is to create an efficient and responsive fire alarm system, specifically for forested areas. The system aims to:

**Flame Detection for Early Warnin**g: Uses sensors to detect flames or excessive heat, providing early detection to prevent the spread of forest fires.
**Immediate Push Notifications via Adafruit IO and IFTTT**: Sends real-time notifications to users’ smartphones, ensuring prompt action.
Audible Alerts Through a Buzzer: Emits a loud sound to alert anyone nearby of the danger.

IFTTT is used to send gmail to others by just setting conditions when it meets the condition gmail will be sent automatically



Components Used
**NodeMCU ESP8266:** Wi-Fi-enabled microcontroller for processing sensor data.
**Flame Sensor:** Detects flames or elevated temperatures.
**Buzzer:** Emits an audible alert upon detecting a fire.
**Adafruit IO:** Cloud service for remote monitoring and control.
**Breadboard:** For prototyping and connecting components.
**Jumper Wires**: Provide electrical connections.
**Micro USB Cable:** Used to upload code to the NodeMCU board.



System Operation
The operation of the IoT-based fire alarm system can be broken down into three main stages: initialization, fire detection, and alert mechanism.

**Initialization:**
**Wi-Fi Connection**: NodeMCU connects to the local Wi-Fi network.
**Adafruit IO Configuration**: Set up with an authentication token to send notifications.

**Fire Detection:**
Continuous Monitoring: Flame sensor monitors for flames or elevated temperatures.
Detection and Response: Triggers alert mechanisms upon detecting a fire.
**Alert Mechanism:**
Audible Alert: Buzzer emits a loud sound.
Remote Notification: Adafruit IO sends a push notification to the user’s smartphone.




