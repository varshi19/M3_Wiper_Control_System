# Abstract

A windshield wiper is a device that cleans the front window of a car by removing rain, snow, ice, washer fluid, and water. Almost all motor vehicles, including cars, lorries, buses, railroad locomotives, and watercraft with a cabin—as well as some aircraft—have one or more such wipers, which are usually required by law. The previous technology needed manual wiper activation; adjusting the frequency results in a variable operation of raising the wiper speed. This project seeks to improve the system of older cars by providing automated wiping, to improve the system by using a sensor with actuators, and to build a basic software that will completely work with the system. This proposed wiper system's principle is comparable to those of other existing conventional wipers.Despite removing water from the windscreen, this system also will be upgraded to an automatic control system by using a Peripheral Interface Controller


# INTRODUCTION
 A wiper speed control system regulates the operational speed of a wiper based on frequencies. To generate a control signal, the pulse signal is digitally processed. The control signal is received by a wiper driving circuit, which then adjusts the operational speed or time accordingly.
# SOFTWARE REQUIREMENTS
 STM32 CUBE IDE
# COMPONENTS
  STM32F4O7VG MICROCONTROLLER BOARD
## DESCRIPTION
# STM32F407VG
 The STM32F407  Kit takes advantage of the high-performance STM32F407 microcontrollers' capabilities to make it simple for users to create audio-based applications. It comes with an ST-LINK embedded debug tool, an ST-MEMS digital accelerometer, a digital microphone, an audio DAC with integrated class D speaker driver, LEDs, pushbuttons, and a USB OTG micro-AB connector.Ethernet connectivity, an LCD display, and other features have been added to the STM32F4 DISCOVERY kit. The STM32F405xx and STM32F407xx families are built around the high-performance Arm® Cortex®-M4 32-bit RISC core, which runs at up to 168 MHz.
 # FEATURES OF STM32F407VG MICROCONTROLLER
  * In a LQFP100 package, the STM32F407VGT6 microcontroller has a 32-bit ARM Cortex-M4 with FPU core, 1-Mbyte Flash memory, and 192-Kbyte RAM.
  * On-board ST-LINK/V2 or ST-LINK/V2-A on STM32F4 DISCOVERY (old reference) or STM32F407G-DISC1 (new order code)
  * USB ST-LINK with three separate interfaces and re-enumeration capability.
  * Virtual Com port Debug port (with new order code only)
  * Large-scale storage (with new order code only)
  * Board power is supplied through USB or an external 5 V supply source.
  * 3 V and 5 V external application power supply
 # USES
  * This Microcontroller is utilised in printing and scanning machines ,heat ventilation, air conditioning, and security systems. 
  * This module can be found in a variety of household products.
 # WORKING PRINCIPLE
 Consider the automobile as microcontroller. If the button is hit, the first LED (red) will turn on. Pressing the button again the wiper will start and the second LED (blue) will turn on for the desired rate. If the button is pressed again, the third LED (green) will turn on and the wiper's speed will be increased in comparison to the previous one. The fourth press will turn on the fourth LED (orange) and the wiper speed will be increased in accordance with the previous one. The microcontroller (vehicle) is turned off after the fifth click.
## FOLDER STRUCTURE
Folder | Description
-- | --
0_Abstract | Explaination of the project
1_Requirements | Documents detailing requirements and research
2_Design	| Behavioural and Structural UML Diagrams along with Block diagrams and flow charts
3_Implemenatation	 | All code and documentation
4_TestCases	| Documents with test plans and procedures and Output
5_Report	| Overall report of the project
6_Output	| Code Execution Images and Video
 ## 4 W'S
 # WHAT IS WIPER SYSTEM
  Windscreen wipers are necessary for maintaining sufficient view for the driver, especially in modern high-speed cars.
 # WHY WIPER SYSTEM
   To keep the windscreen clean enough to give adequate view at all times.
 # WHEN SHOULD USE WIPER SYSTEM 
  The windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.
 # WHO DISCOVERED WIPER SYSTEM
  Mark Anderson invented on 1902
     ## HOW 
  The control system includes a rain sensor which detects the rain condition. An analog signal having an amplitude depending upon the detected rain conditions has been identified.A converter is used to convert analog signal into digital pulse signal and is transferred to a digital circuit system.The pulse signal is digitally processed where a control signal is produced.The control signal is applied to a wiper driver circuit to adjust the operational speed or timing in accordance with the control signal.
# SWOT ANALYSIS
## STRENGTH
* Low cost 
* High reputation
* Clarity of vision 
## WEAKNESSES
* Replacement cost are higher.
* Chances of wiper motor failure.
## OPPORTUNITIES
* High possibilities for safety.
## THREATS
* Wiper mix might be an issue in rain.
* Replaced  by advanced technology.

# Engine OFF state
![Engine OFF state](https://user-images.githubusercontent.com/102513343/168284308-cd28a8ca-1481-4c9f-9325-92b9612642e1.jpeg)
# Engine ON state
![Engine ON state](https://user-images.githubusercontent.com/102513343/168284335-d8da3938-dce2-436e-8f7f-9f378f885176.jpeg)
# Wiper is at LOW speed
![Wiper is at LOW speed](https://user-images.githubusercontent.com/102513343/168284355-ee043542-051d-46bc-93b3-18ee89abcea7.jpeg)
# Wiper is at MODERATE speed
![Wiper is at MODERATE speed](https://user-images.githubusercontent.com/102513343/168284374-fb3dd730-934b-48a3-ae41-a8e7b46d888f.jpeg)
# Wiper is at HIGH speed
![Wiper is at HIGH speed](https://user-images.githubusercontent.com/102513343/168284390-814665c0-de6d-461b-b31b-d9b299375182.jpeg)


  
