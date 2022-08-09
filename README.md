# UAVCapstone
Welcome! This repo serves as a log to keep track and details the sections I have worked on for my UAV targeting system capstone project.

In summary, my capstone team (EJ Agena, Manvir Jutla, Ezra Lorono and I) developed a UAV targeting system consisting of 3 main subsystems for the University of Alberta's Aero Design Team.

The targeting system consisted of 3 main systems: the Vision System, Communciation System and Autonomous System. The Vision System was in charge of detecting and locating circular coloured targets (as per SAE Aero Design 2022 competition rules) through the use of an onboard computer (Raspberry Pi 4) with live video feed from an RPi camera attachment. Additionally, the live video feed with the detected targets are sent to a monitor on the ground (this is where the Communication System comes into play) and a separate camera (Go Pro) takes a Hi-Def photograph of the desired target and is also sent wirelessly to a Ground Control Station in which the desired target's GPS coordinates are calculated relative to the aircraft when the photo was taken.

Unfortunately, due a resurgence on COVID cases during the Winter 2022 semester, all classes were transferred virtually which affected in-person collaboration and coordination for the capstone. Furthermore, the capstone coordinator requested all teams to update their projects to accomodate the virtual instruction - such as changing project milestones such that in-person collaboration and coordination is not required. As a result, the Autonomous subsystem was affected as it required in-person collaboration and testing since it required multiple complex hardware to be assembled.

## Vision System: 
[Target Detection](https://github.com/krisian444/UAVTargDetect)

[Camera Calibration](https://github.com/krisian444/CamCalibration)

## Communication System:
[Interface Board](https://github.com/krisian444/UAVInterfaceBoard)
