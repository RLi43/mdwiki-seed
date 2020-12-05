# Projects

[TOC]

### The International Genetically Engineered Machine Competition(iGEM) 2018

* 2017.09 - 2018.10
* find more information from [our wiki](http://2018.igem.org/Team:Tsinghua-A)

[![Tsinghua-A at Jiant Jamboree with poster](../files/igem/Tsinghua-A--Team-photo.jpg) ]( http://2018.igem.org/Team:Tsinghua-A )

*  attribution:  Designed and constructed the hardware ([Detail](http://2018.igem.org/Team:Tsinghua-A/Hardware ))
*  sponsored by *Academic Research Promotion Plan for Undergraduate Student*

![Hardware Printing](C:/Users/Robot.Li/Desktop/selfwiki/mdwiki/Introduction/files/igem/hardware printer.jpg)

### Baxter

* 2018.09-2019.05
* 

* sponsored by *Academic Research Promotion Plan for Undergraduate Student*
* 

#### Play Gobang with human

#### Arm movement simulation

#### Experimental Guide Book for Baxter



### Footroller: Game shoes for the handicapped

- sponsored by *College Students' Innovative Entrepreneurial Training Plan Program*
- https://github.com/RLi43/Footroller 



### Exploration and Implementation of Motion Planning Algorithm with Specified Optimization Goal

2020.07.01-2020.08.31

A summer intern in [Aqrose Technology]( http://www.aqrose.com/ ), a company major in AI for robotics and automation. During the summer of 2019, I worked on planning algorithm of the robot. 

Because a 6-axis Fanuc robot doesn’t give enough detail about its algorithms, we don’t know the accurate trajectory that robot will take, which makes it dangerous to operate in industry site. Therefore, I worked on an algorithm that have enough distance away from the obstacles to make sure that the robot won’t hit them.(Meanwhile, there’s another colleague worked on experiments to conjecture the algorithm in black box.)

I learned about planning algorithm by [Planning Algorithms]( http://planning.cs.uiuc.edu/ ). After reading some papers, algorithms, finally I decided to use BIT* as the main algorithm. I set some penalization for short distance to obstacles and got a positive output.

Here’s the [detailed report.pdf(Chinese)](..\files\report of summer intern(Chinese).pdf) and [PPT]( https://cloud.tsinghua.edu.cn/f/decae61280884d46948e/ ) and a [essential version PPT]( https://cloud.tsinghua.edu.cn/f/a575d20f2ca749b0b7c3/ ). [Python Demos for biBIT*]( https://github.com/RLi43/RRTs/blob/master/BiBITstar.py )

### Internship in Future Lab

2019.09 - Present

Working in the LEGO Group with [Dr. Meng Wang](http://thfl.tsinghua.edu.cn/info/post-doctoral/507), I participate in several projects about Modular TUI. Mostly deal with modals, circuits, codes. Sometimes severed as a soldering android :laughing:.​

Here’re some photos.

<img src="C:/Users/Robot.Li/Desktop/selfwiki/mdwiki/Introduction/files/flab/mr.png" style="zoom:30%;" /><img src="C:/Users/Robot.Li/Desktop/selfwiki/mdwiki/Introduction/files/flab/lego.png" style="zoom:30%;" />

### A Gloves-based Joint Pose Sensing System

2020.07-2020.09

A summer research project focus on improving [form system](https://ieeexplore.ieee.org/document/8206575/). Due to the COVID-19, This project which would have been taken in *UCLA Center for Vision, Cognition, Learning, and Autonomy (VCLA) at Statistics Department*, was taken in my home.

The former project has these problems: 1) the force sensor is neither accurate or sustainable. 2) lots of wires are used making user inconvenient. 3) connected with a raspberry pi, the system is huge as for a glove and movements are constricted by the power wire.

![](C:/Users/Robot.Li/Desktop/selfwiki/mdwiki/Introduction/files/glove/former.png)

Therefore, in this project we, 1) give up the force sensors. 2) replace raspberry pi with ESP32(a MCU) with WiFi module. 3) replace wires and PCB with FPC

This project is not fully completed. Here’s some designs during project.

![](C:/Users/Robot.Li/Desktop/selfwiki/mdwiki/Introduction/files/glove/Hub.png)![](C:/Users/Robot.Li/Desktop/selfwiki/mdwiki/Introduction/files/glove/Hub_design.png)

The design for hub deal with 8-channel IIC signal.

![](C:/Users/Robot.Li/Desktop/selfwiki/mdwiki/Introduction/files/glove/IMU_pcb.png)![](C:/Users/Robot.Li/Desktop/selfwiki/mdwiki/Introduction/files/glove/IMU_design.png)

The test PCB for IMU. (Soldering this tiny board kills me…)

![image-20201203230803141](C:/Users/Robot.Li/Desktop/selfwiki/mdwiki/Introduction/files/glove/web_data.png)![](C:/Users/Robot.Li/Desktop/selfwiki/mdwiki/Introduction/files/glove/reconstruction.png)

read sensor’ data through wireless network and reconstruct the pose of joints.

![](C:/Users/Robot.Li/Desktop/selfwiki/mdwiki/Introduction/files/glove/main.png)![](C:/Users/Robot.Li/Desktop/selfwiki/mdwiki/Introduction/files/glove/fpc.png)

The development board and the FPC.