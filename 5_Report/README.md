# INTRODUCTION
Wiper is an essential component that is used to wipe raindrops or any water from the windscreen. Wipers are designed and made to clear the water from a windscreen. Most cars have two wipers on the windscreen, one on the rear window and the other on each headlight. The wiper parts visible from outside the car are the rubber blade, the wiper arm holding the blade, a spring linkage, and parts of the wiper pivots. The wiper itself has about six parts called pressure points or claws that are small arms under the wiper

The existing system uses a control stalk to activate the wiper and the process of pulling up the wiper is difficult.r needs to switch on and off the control stalk and it will reduce the driver’s concentration during the driving. Thus, this system is proposed to solve all these problems. The concept of this wiper system is similar to other conventional wipers, yet this system will be upgraded to an automatic control system by using a controller.When water hits a dedicated sensor located on the windscreen, it triggers the wiper motor to move. is not detected by sensor, the wiper will automatically stop. This will help the driver to give more concentration and reduce the car accident probability.

In this project, there were two innovations reviewed as the literature review. The two were designed with different concepts and operating mechanism however with same objective of working principle of the car wiper. The rain sensor was a highly versatile device for automatic wiping of vehicle windscreen when it is wet due to moisture, raindrops or even mud. It worked by reflecting harmonious light beams within the windscreen. When raindrops fall onto the windscreen, this harmony light is disturbed and creating a drop in the light beam intensity. The system then activated the wipers to be operated in full automatic mode. It has a response time of 0.1 seconds. It allowed for a quick reaction when it is a sudden splashes of water that will make the driver totally ‘blinds’ when the situation happened. With the automatic wiper, the driver can avert the risk of an accident. The automatic wiper is important during heavy traffic, e.g. in town, city, school zone and other public places. A driver may be subjected to many distractions with bad weather, dangerous road conditions and fatigue. The Rain Sensor reduced the driver’s burden by making driving more comfortable. Trailing a wet car is no longer a nuisance as detection of even 0.005 milliliters of water is possible.

# COMPONENTS AND SUPPLIES:
1. STM32F407 Discovery Board
2. Push Button
3. LEDs
4. Resistors
5. Power Supply

# ADVANTAGES:
* To save money during wet seasons, turn off the irrigation system. Electricity bills are lowered as a consequence.
* Rain sensors store water during rain events, allowing it to be available throughout the summer and winter.
* As a consequence, rain sensor-based equipment like vehicle wipers and irrigation systems last longer since they only work when needed.
* It is quite simple to use.
* As a consequence, less energy is consumed.
* Rain sensor-based systems are extremely simple to install.
* Individual rain sensors are fairly inexpensive.

# Disadvantages:
* When water falls squarely on the rain sensor, the mechanism activates.
* The entire system cost rises when more components, including a rain sensor, are required.
* Rain sensors must make a decision within a few minutes to avoid erroneous detection of rain. 

## SWOT ANALYSIS
  The image below shows the SWOT analysis 
  ![swot](https://user-images.githubusercontent.com/68462123/167817970-b2e6d1df-1407-4363-82e7-9cf3ccc385e7.png)
  
## 4W & H (WHO,WHAT,WHEN,WHERE,HOW)
  - WHO- Useful for drivers like car, buses and trucks for clear vision of the road
  - WHAT- Aim is to implement automatic wiper system for vehicles
  - WHEN- Helpful during rain 
  - WHERE- Installed at the front windshield
  - HOW- Ignition is turned on, the wiper starts its operation.
  
## HIGH LEVEL REQUIREMENTS
| ID | Description | Status |
| ---|:------------|:-------|
| HL1 | car wiper using STM32F407VG | Implemented |
| HL2 | Led glowing in sequence| Implemented |
| HL3 | Car on and off | Implemented |
## LOW LEVEL REQUIREMENTS
| ID | Description | Status |
| ---|:------------|:-------|
| HL1-LL1 | Push Button | Implemented | 
| HL2-LL2 | Red,Green,Blue Leds | Implemented |

# Exploring STM32F407 Discovery Board
![STM32F407 BOARD](https://user-images.githubusercontent.com/85924451/168370794-43b685a0-46d6-42b0-a372-5c802280ffcb.PNG)

 This project gives almost all the basic information needed to get started with STM32F407 Discovery Board and also development of driver code.

* Hardware Used : STM32F4 DISCOVERY kit, for more information visit: STM32F4 DISCOVERY
* Software Tool : STM32cubeIDE, for more information visit: STM32CubeIDE
* For installation of STM32CubeIDE refer Youtube
* Note : As this microcontroller has many advanced features and the main aim of this project is to ge
t all basic insights, during the driver development only the required functionalities are added and other advanced functionality is not added. I may update the driver and other functionality in the future.

# OUTPUT IMAGES
1. user button and hold it for two seconds
 ![ENGINE ON STATE](https://user-images.githubusercontent.com/85924451/168373434-684fd226-1173-4482-8166-f61c7f7cc649.PNG)
 
2. WIPER SPEED LOW
   ![LOW](https://user-images.githubusercontent.com/85924451/168373559-3628ee0a-71b2-4cb4-93ea-be0c6ecc79cc.PNG)
  
3. WIPER SPEED MEDIUM
   ![medium speed](https://user-images.githubusercontent.com/85924451/168373752-43437f0b-c20d-4b05-958a-09b74410d1db.PNG)

4. WIPER SPEED IS HIGH
   ![HIGH SPEED](https://user-images.githubusercontent.com/85924451/168374143-8c69fbd6-114d-4bb5-ac89-f7dbcd1b9baa.PNG)

5. USER PRESSED BUTTON AND HELD FOR 2sec, THE RED LED IS OFF
   ![PRESS   HELD FOR 2 SEC](https://user-images.githubusercontent.com/85924451/168374389-1f51ccba-b36b-45f8-85ce-f1832c6751d2.PNG)

6. WIPER SYSTEM 1
   ![WIPER SYSTEM 1](https://user-images.githubusercontent.com/85924451/168374521-0abd8cf7-9601-4e06-a25a-b347cccd28bc.PNG)

  
 
