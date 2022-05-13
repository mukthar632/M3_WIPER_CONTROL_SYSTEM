# INTRODUCTION
- A windshield wiper or wiper blade is a device which is used to remove rain, snow, ice, washer fluid, water, from a vehicle's front window. 
- Every heavy  motor vehicles including cars, trucks , train locomotives and some aircraft—are installed  with such wipers .
- After reading several research papers , I understood that safety requirements under unfavourable weather condition is necessary even at low speed also for motor vehicles and therefore I started making wiper control system using arm based microcontrollers. 
- It consist of rubber blades attached at its metal arms with pivot magnets at its other ends.
- Finally this project application helps users in day to day life and prevents accidents and allows safe and healthy journey.

## RESEARCH
This application is researched from various sources (like you tube , google and research papers ) and then I have modified into successful working model application of wiper control system using arm based microcontrollers. 

## END GOAL
- Clear vision in adverse weather conditions .
- Avoid accidents and ensure safety with latest mechanism.

### Who
-   Everyone who wants safety and clear vision of road in driving using motor vehicles.
### What
-   Wiper Control System for motor vehicles.
### Why
-   Curious about carrier in embedded system . 
### When 
-   When you understand the importance of safety management and start to be accountable for your health during driving motor vehicles in unfavourable weather conditions.
### Where
-   This can be  used by the user in day to day life where they can track their safety and  generate better results in life during travelling via motor vehicles  .
### How
-   LED shows the position of wiper and it will return to the original position after cleaning windsheet of motor vehicles  .
## SWOT ANALYSIS
![SWOT](https://user-images.githubusercontent.com/101577287/167350083-a490665c-2697-474b-aea1-3fe3871a6fb4.png)
## Detail requirements
## High Level Requirements
| ID | Description | Requirement | Status | 
| ----- | ----- | ------- | ---------|
| HR001 | SSD or HARD DRIVE  | 1GB TO 20 GB | IMPLEMENTED | 
| HR002 | OPERATING SYSTEM  | WINDOWS |  IMPLEMENTED  |
| HR003 | PROGRAMMING LANGUAGE | EMBEDDED C |  IMPLEMENTED  |
| HR004 | ARM BASED MICROCONTROLLER | STM32F407VGT6 BOARD  |  IMPLEMENTED  |
## Low level Requirements
| ID | Description | REQUIREMENT | Status (Implemented/Future) |
| ------ | --------- | ------ | ----- |
| LR001 | WIPER COMES TO INITIAL POSITION AFTER HIS WORK | LED USED FOR THIS |  IMPLEMENTED  |
| LR002 | PROPER SUPPLY TO PINS AND BOARD | DONE |  IMPLEMENTED |
| LR003 | ON AND OFF SWITCH MECHANISM FOR ACTIVATION AND DEACTIVATION OF WIPER BLADES  | DONE  | IMPLEMENTED |
# BLOCK DIAGRAM
![BLOCK DIAGRAM](https://user-images.githubusercontent.com/101577287/167358640-8543dc2b-6fd4-4d27-9797-004e5d80bb1b.png)
## FLOWCHART
![FLOWCHART (2)](https://user-images.githubusercontent.com/101577287/167533935-eecad978-818a-4b38-9f5e-a8c9ce945f75.png)

# Test Plan
## High Level Test Plan

| Test ID| Description | Exp I/P | Exp O/P | Status |
| -------| ----------- | ------- | ------- | ------ |
| H_01 | DEVELOPMENT OF .elf file    | .C file | .elf| Implemented |
| H_02 | Cross Compilation of Files  | Converting .c file into target output | .elf or .hex   | Implemented |
| H_03 | Search components in STM32 CUBE IDE |  Components  | Assembling     | Implemeted  |

## Low Level Test Plan

| Test ID| Description | Exp I/P | Exp O/P | Status |
| -------| ----------- | ------- | ------- | ------ |
| L_01 | DONT STOP WIPER AT MIDDLE OF WINDSHEILD  | RAIN CONDITION | ADVERSE WEATHER | Implemented |
| L_02 | SERIAL WISE LED GLOW REGULATION | DONE | whenever required | Implemented |


