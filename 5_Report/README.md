# Heating-System

## Code Badges :
 Build| Cppcheck | Codacy | Code inspector|
----|----|-----|-----|
|[![CI](https://github.com/paarventhan1999/M2-Embedded_pc-beeper/actions/workflows/compile.yml/badge.svg)](https://github.com/paarventhan1999/M2-Embedded_pc-beeper/actions/workflows/compile.yml)|[![cppcheck-action-test](https://github.com/paarventhan1999/M2-Embedded_pc-beeper/actions/workflows/cppcheck.yml/badge.svg)](https://github.com/paarventhan1999/M2-Embedded_pc-beeper/actions/workflows/cppcheck.yml)|[![Codacy Badge](https://api.codacy.com/project/badge/Grade/27ab7408f0824317a1a2a63cdee352f3)](https://app.codacy.com/gh/paarventhan1999/M2-Embedded_pc-beeper?utm_source=github.com&utm_medium=referral&utm_content=paarventhan1999/M2-Embedded_pc-beeper&utm_campaign=Badge_Grade_Settings)|[![code quality](https://api.codiga.io/project/30238/score/svg)](https://app.codiga.io/project/30238/dashboard) [![code grade](https://api.codiga.io/project/30238/status/svg)](https://app.codiga.io/project/30238/dashboard)

# **Introduction:**

The heating system is basically used to control the temperature. The user gets access to turn on the heater. The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller. The microcontroller processes the analog input of the temperature sensor and outputs a temperature value through serial communication. All the activities of the activities of the control system are done on a microcontroller called Atmega328. The functionality of the heat control system is coded in embedded c and the working is demonstrated using simuation in a software called SimulIDE.

# Details requirements
### High Level Requirements:
| ID | Description | Status |
|------| ------| ------|
| HLR1 | When the two switches are closed, the first LED glows indicating the actuation of the system and the heater. | Implemented
|HLR2  | Next the analog input from the temperature sensor is received and digitized.| Implemented
|HLR3  | The hard disk must be 4 GB . |	Implemented
|HLR4  | The web browser must be Microsoft Internet Explorer with a resolution of at least 800 \* 600. |	Implemented

#### Low Level Requirements:

| ID | Description | Status |
|-------|------|------|
| LLR1 | The digitized temperature input is visualized using Pulse Width Modulation.| Implemented 
| LLR2 | The system runs effectively on Windows 2000 server but it will also run equally well on compatible operating systems.  | Implemented
| LLR3 | The corresponding temperature values based on the digitized temperature input is transmitted by the UART protocol. Here the data is displayed on the serial monitor.| Implemented 
 
# **SWOT Analysis:**

## **Strength:**

The advantage of such devices is that you can not wait until the entire salon warms up, and immediately go on business. After all, heating has a local effect, so they do their job in 2-5 minutes.

## **Weakness:**
- If you do not follow the recommendations and go too far with the temperature, this can lead to a decrease in the driver’s attentiveness, cause fatigue and headaches, and also increase the risk of catching a cold due to a violation of the body’s temperature regime.
- the power cord is plugged in only after you fix the cape;
- if you spill any liquid on the heater cover, immediately turn off the device;
- if you leave the car, do not leave the device turned on;
- you can not wash the capes, iron, maximum-shake;
- Use dry bags to store the heater.

## **Opportunities:**

The advanced technologies in automotive seat heaters are predicted to increase the growth of the market in the review period. The latest features like modern seat heaters like consistent and controlled warmth, heating level adjustment are attracting the consumers and are expected to propel the market growth. Growing demand for comfort and energy capabilities in vehicles is accelerating market growth.

## **Threats:**
- A lack of regulation for these seats has left consumers more open to injuries.
- Within 10 minutes at 120 degrees an individual can experience third-degree burns. For those with the inability to feel the temperature at the time, this can prove even more dangerous. Those who have been diagnosed with conditions such as paralysis, diabetes, and neuropathy are less like to feel the heat in their lower extremities.
- High electrical resistance could cause the heater pad in the seat to overheat.

# **4W and 1H:**

## **What:**

Heated seats can make cars much more comfortable in the winter, or for those who often get cold even in the summer. The heater in most vehicles work well, but the car's seat warmer is close to your body allowing you to warm up faster. In some cases, the seat warms up before the rest of the vehicle does.

## **When:**

Heated front seats not only offer luxurious comfort, relaxation and benefits for physical health, but also increase safety. Heating seats and backrests ensures a high level of well-being and prevents a cramped posture. Winter clothes limiting freedom of movement can be dispensed with. This also results in better operation of the restraint system by reducing the slack in safety belts. People with back or kidney problems benefit from a possible reduction of pain. It is mostly used in cars.

## **Where:**

In car seats

## **Why:**

Heated seats can bring a lot of different benefits beyond just having a nice and warm place to sit. The single greatest benefit that heated seats can bring is the therapeutic warmth it offers. This is great for older drivers or people with a few aches and pains.

## **How:**

The longer the seat cushion stays on, the hotter it gets. If it were to stay on for too long, it would get hot enough to become uncomfortable or even dangerous to sit in. It could even start a fire in the cushion. To prevent this, most car seat heaters have a thermostat. The thermostat measures the temperature in the cushion. When it reaches a certain temperature, the thermostat sends a signal, automatically turning off the relay until the seat cools down a bit. At that point, the thermostat turns the relay back on again. Many seat cushions also have “high” and “low” settings that let the driver control the temperature of the seat cushions.

# Output

#### Activity 1:

|OFF|OFF|
|:--:|:--:|
| ![activity_1](https://user-images.githubusercontent.com/94169797/144202956-da2afcb1-2086-43e9-ac96-ba98e4552afb.jpg) | ![activity_1 off](https://user-images.githubusercontent.com/94169797/144203019-eba28a62-fede-4c29-aa57-480cf47e14e7.jpg) |

|OFF|ON|
|:--:|:--:|
| ![activity_1off](https://user-images.githubusercontent.com/94169797/144203203-e3263db5-1e75-4043-80c2-522641c7781e.jpg) | ![activity_1on](https://user-images.githubusercontent.com/94169797/144203216-f9b83bc0-6bed-43a9-b230-064a92bce2a7.jpg) |

#### Activity 2:

| ![activity_2 1](https://user-images.githubusercontent.com/94169797/144203736-ba12ed33-a7d6-4b9f-93af-598671344b89.jpg) | ![activity_2 2](https://user-images.githubusercontent.com/94169797/144203746-e5e2f195-efc9-4818-8c9f-6de9e3ded33d.jpg) |
|:--:|:--:|
| ![activity_2 3](https://user-images.githubusercontent.com/94169797/144203750-ea6c71ab-d5b7-4931-9df6-c93c0cfaffea.jpg) | ![activity_2 4](https://user-images.githubusercontent.com/94169797/144203717-e5f0af84-d1f6-4425-9221-9a40f250ed1b.jpg) |

#### Activity 3:

| ![activity_3 1](https://user-images.githubusercontent.com/94169797/144204647-fa0a50f8-3a69-4eed-b218-e24162c325d5.jpg) | ![activity_3 2](https://user-images.githubusercontent.com/94169797/144204651-61de9215-d0fd-4ec0-bcec-1578d4fe3b2d.jpg) |
|:--:|:--:|
| ![activity_3 3](https://user-images.githubusercontent.com/94169797/144204657-8024be8f-dc79-4a44-b356-ccf92e053982.jpg) | ![activity_3 4](https://user-images.githubusercontent.com/94169797/144204642-8a61f95a-df85-4e73-8795-7a4380e3d4c7.jpg) |

#### Activity 4:

| ![activity_4 1](https://user-images.githubusercontent.com/94169797/144205350-6f2318ed-482b-4031-b49c-d77ee6d2e5da.jpg) | ![activity_4 2](https://user-images.githubusercontent.com/94169797/144205360-edb3b2da-b77f-418e-b57c-cdcd2ab27917.jpg) |
|:--:|:--:|
| ![activity_4 3](https://user-images.githubusercontent.com/94169797/144205364-cb47aa68-5a90-4566-830b-aa7a856d5df6.jpg) | ![activity_4 4](https://user-images.githubusercontent.com/94169797/144205368-60e9bf0a-fb85-4913-92df-f6a46ada786a.jpg) |



# TEST PLAN:
### High Level Test plan:
| ID    | Description                             | Expected O/P | Actual O/P | Type of Test |
|-------|-----------------------------------------| ------------ | ---------- | ------------ |
| H_01  |Front page                   |PASSED        |SUCCESS     | Requirement  |
| H_01  |sensing                          |PASSED        |SUCCESS     | Scenario     |
| H_03  |enable blinking led             |PASSED        |SUCCESS     | Boundary     |


### Low Level Test Plan:
| ID    | Description           | Expected O/P | Actual O/P | Type of Test | 
|-------|-----------------------| ------------ | -----------| ------------ |
| L_01  |Open the app           | PASSED       |SUCESS      | Requirement  |
| L_02  |View the board| PASSED       |SUCESS      | Scenario     |
| L_03  |Reserve your possible seat     | PASSED       |SUCCESS     | Boundary     |
