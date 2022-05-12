<p align="center">
  <img src="https://user-images.githubusercontent.com/54715463/155894839-e6a05c2e-aa95-4b53-bb4d-c4cbc1a964b9.png" alt="Material Bread logo">
</p>

***

# RoboMedicinae1 - Gripper
<a href="https://github.com/Steigner/RM1_Gripper/blob/main/LICENSE"><img alt="License: MIT" src="https://img.shields.io/github/license/Steigner/RM1_Gripper.svg"></a>

## Master's Thesis - Branch

**Open-source, copy and modify what you need!**

**Open-source, kopírujte a upravujte co potřebujete!**

## About
RM1 is an experimental robotic platform created to automate antigen testing. This project was developed as part of a master's thesis. The aim was to create a functional and modular prototype that is easily modifiable and deployable after debugging. The basic idea is to create a web-based server that communicates with ROS. ROS was used in the work as a simulation and debugging environment, mainly for robot control. The thesis is divided into four main parts:

+ [<=](https://github.com/Steigner/Robo_Medicinae_I) Robo Medicinae I
+ [<=](https://github.com/Steigner/RM1_server) RM1 - Server
+ [<=](https://github.com/Steigner/RM1_ROS) RM1 - ROS         
+ [<=](https://github.com/Steigner/RM1_Gripper) RM1 - Gripper
+ [<=](https://github.com/Steigner/RM1_SegCNN) RM1 - SegCNN

As part of this package, it was necessary to design some parts for 3D printing in order to fit the UR3 end effector, Intel Realsense D435i camera, Optoforce Hex-e sensor, and Optoforce RG2 Gripper. Again, the emphasis was on modularity. A simple rack and thread was designed to handle the entire testing process. All parts were printed on Prusa 3D printers. Within the work both angular and straight attachment for camera mounting was designed, we used **Angular for testing**. Used settings:

* Prusa i3 MK3
* PLA Filament
* 0.2 mm
* filling 15%

## Software
```
Autodesk Inventor Proffesional 2020
PrusaSlicer 2.3.1
```

### Bill Of Materials 
Number | ISO | Parameters
------------ | ------------- | -------------
4x | DIN EN ISO 4762 | M6x16
4x | DIN EN ISO 4762 | M4x16
2x | EN ISO 7045H | M4x12
2x | EN ISO 7045H | M3x5
6x | EN 24035 | M4

**Note:**
* Recommended torque for both M3 mounting points is 0.4Nm Intel Realsense D435i.

## Screenshots and videos

<p align="center"> <b>Click to full resolution</b> </p>

<p align="center"> <b>Angular Gripper</b> </p>

![Gripper_RG2_A_V1](https://user-images.githubusercontent.com/54715463/155989442-a78e2b5c-190b-4571-a883-336fd8a2ab90.png)

![Gripper_RG2_A_V1_2](https://user-images.githubusercontent.com/54715463/155989454-2ba1a16d-52f4-40c9-807e-27dcd25e3792.png)

<p align="center"> <b>Straight Gripper</b> </p>

![Gripper_RG2_S_V1](https://user-images.githubusercontent.com/54715463/155989463-cbdbb8b7-d0af-4f95-9163-3336e7fb3bd0.png)

## Authors

* Author: Martin Juricek
* Supervisor: Roman Parak

## Citation
If you want to cite please check the header repository. 

github.com/Steigner/Robo_Medicinae_I [=>](https://github.com/Steigner/Robo_Medicinae_I#citation) 

## References
* [D435i Spec.](https://www.intelrealsense.com/depth-camera-d435i/)
* [Faculty of Mechanical Engineering BUT](https://www.fme.vutbr.cz/en)
