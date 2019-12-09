# autonomousHarlan
In this repository we show the progress we had in the construction of an autonomous vehicle. An autonomous vehicle needs to know what is its path where it will drive and have a control system to take decisions to make the different mechanisms work that give him moviment.
In order to achieve the above, we use a ZED Camera Stereo, ORB_SLAM2 (it has been modificated from the original version), an PLC Unitronics model V133-33, an Harlan vehicle that we have automated and a PID Driver that we have programmed. 

# Requirements:
## ROS
You must have the ROS-Kinetic-Kame version installed in Ubutu 16.04

## Workspace creation (Catkin)
Our workspace is called zed_ws. You have to write in a terminal:
```
mkdir -p ~/zed_ws/src
cd zed_ws/src
catkin_init_workspace
ls
```

You must verify that CMakeList.txt exists in the folder. Next, you build the workspace using these commands:
```
cd ..
catkin_make
```
Check that the build, develop and src folders exist in the catkin_ws folder. To do this from home, the commands are made:
```
cd zed_ws
ls
```


## ORB_SLAM2 (MAPPING AND LOCALIZATION MODE)
In this page we attached a document called "ORB_SLAM2 AND ZED STEREO CAMERA INSTALLATION", where you can find all the requirements to install.

## PID DRIVER
We attached in the "ORB_SLAM2" folder a programm in python called fullPIDControlComms.py. This file is our driver used to give the autonomy function to our vehicle.


## PYMODBUS


# Video:
We are attaching a YouTube link to evidence the work that began in August-December 2017 and has been worked until August-December 2019.
YouTube link:
