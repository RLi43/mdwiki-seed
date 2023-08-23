# Projects

[TOC]

> I noticed that some links to photos are expired. But unfortunately I don't have a backup. Please just pretend as if there're somethings by the captions : )

## Projects in Bachelor University

### The International Genetically Engineered Machine Competition(iGEM) 2018

* 2017.09 - 2018.10
* find more information in [our wiki](http://2018.igem.org/Team:Tsinghua-A)

[![Tsinghua-A at Jiant Jamboree with poster](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/igem/Tsinghua-A--Team-photo.jpg) ]( http://2018.igem.org/Team:Tsinghua-A )

*  attribution:  Designed and constructed the hardware ([Detail](http://2018.igem.org/Team:Tsinghua-A/Hardware ))
*  sponsored by *Academic Research Promotion Plan for Undergraduate Student*

<img src="https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/igem/hardware printer.jpg" alt="Hardware Printing" style="zoom:50%;" />

<img src="https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/igem/developing.png" alt="developing" style="zoom:50%;" />

### Baxter

* 2018.09-2019.05
* sponsored by *Academic Research Promotion Plan for Undergraduate Student*

#### Play Gobang with human

[Video](https://cloud.tsinghua.edu.cn/d/a54c26b100784447b8f3/files/?p=%2Fbaxter%2Ffollower.mp4)

![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/baxter/gobang.png)

Here, we rolled out a project able to play gobang with human, without any help from developer.

This project mainly includes image processing, gobang AI, objects recognition, picking and placing.

#### Arm movement simulation

[Video](https://cloud.tsinghua.edu.cn/d/a54c26b100784447b8f3/files/?p=%2Fbaxter%2Ffollower.mp4)

We capture human skeleton using Kinect SDK and map it into the pose of robot, achieving a pose following effect.

#### Experimental Guide Book for Baxter

Since there's little reference material for students in Tsinghua to use Baxter and develop project on it. We write a manual about how to setup a workspace, run "hello baxter" program, and more advanced manipulation.

### Footroller: Game shoes for the handicapped

2018.07 - 2019.07

- sponsored by *College Students' Innovative Entrepreneurial Training Plan Program*
- https://github.com/RLi43/Footroller 
- Third Prize in 2019 China-US Young Maker Competition in Beijing

How disable people enjoy nowadays colorful digital life? Can they use the smart device as easily as normal people? Focus on the interaction between the handicapped and smart devices, we designed Footroller, game shoes able to control smart device through actions of feet.

![prototype](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/footroller/prototype.jpg)

This system connects PC through wireless network, sends sensor data to program runs on PC which can analysis the actions the user taking and respond with corresponding operation.

### Internship in Future Lab

2019.09 - 2021.01

Working in the LEGO Group with [Dr. Meng Wang](http://thfl.tsinghua.edu.cn/info/post-doctoral/507), I participate in several projects about Modular TUI. Mostly deal with models, circuits, codes. Sometimes severed as a soldering android :laughing:.​

This is a desk robot I finished in 2020.01, consist of 3 replaceable parts of different functions, able to communicate with one another through IR signals.

<img src="https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/flab/mr.png" style="zoom:30%;" /><img src="https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/flab/lego.png" style="zoom:30%;" />

The Lego blocks in the background is for the following project about a modular Lego desk robot. I just finished one block served as "Head" in November and I'm working on the other blocks.

### A Gloves-based Joint Pose Sensing System

2020.07-2020.09

A summer research project focus on improving [form system](https://ieeexplore.ieee.org/document/8206575/). Due to the COVID-19, This project which would have been taken in *UCLA Center for Vision, Cognition, Learning, and Autonomy (VCLA) at Statistics Department*, was taken in my home.

The former project has these problems: 1) the force sensor is neither accurate or sustainable. 2) lots of wires are used making user inconvenient. 3) connected with a raspberry pi, the system is huge as for a glove and movements are constricted by the power wire.

![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/glove/former.png)

Therefore, in this project we, 1) give up the force sensors. 2) replace raspberry pi with ESP32(a MCU) with WiFi module. 3) replace wires and PCB with FPC

This project is not fully completed. Here’s some designs during project.

![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/glove/Hub.png)![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/glove/Hub_design.png)

The design for hub deal with 8-channel IIC signal.

![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/glove/IMU_pcb.png)![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/glove/IMU_design.png)

The test PCB for IMU. (Soldering this tiny board kills me…)

![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/glove/web_data.png)![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/glove/reconstruction.png)

read sensor’ data through wireless network and reconstruct the pose of joints.

![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/glove/main.png)![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/glove/fpc.png)

The development board and the FPC.

## Internship

### Exploration and Implementation of Motion Planning Algorithm with Specified Optimization Goal

2020.07.01-2020.08.31

A summer intern in [Aqrose Technology]( http://www.aqrose.com/ ), a company major in AI for robotics and automation. During the summer of 2019, I worked on planning algorithm of the robot. 

Since a 6-axis Fanuc robot doesn’t give enough detail about its manipulation algorithms, we don’t know the accurate trajectory that robot will take, which makes it dangerous to operate in industry site. Therefore, I worked on a planning algorithm that have enough distance away from the obstacles to make sure that the robot won’t hit them in case the deviation happened.(Meanwhile, there’s another colleague worked on experiments to conjecture the algorithm in black box. Unfortunately, he haven't got the right answer until the end of the summer.)

I learned about planning algorithm by [Planning Algorithms]( http://planning.cs.uiuc.edu/ ). After reading some papers, algorithms, finally I decided to use BIT* as the main algorithm. I set some penalization for short distance to obstacles and got a positive output. And modified the algorithm and speed up it.

What's more, I explored the bi-directional BIT\* and concluded that a simple bi-directional adaption will not benefit BIT* much since it has taken the heuristic information about goal state into consideration.

![biBITstar](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/aqrose/biBITstar.png)

Here’s the [detailed report.pdf(Chinese)](https://cloud.tsinghua.edu.cn/d/a54c26b100784447b8f3/files/?p=%2Faqrose%2Freport%20of%20summer%20intern(Chinese).pdf) and [PPT]( https://cloud.tsinghua.edu.cn/f/decae61280884d46948e/ ) and a [essential version PPT]( https://cloud.tsinghua.edu.cn/f/a575d20f2ca749b0b7c3/ ). [Python Demos for biBIT*]( https://github.com/RLi43/RRTs/blob/master/BiBITstar.py )

### !Ongoing! ==> Modular software architecture for Protection and Control in Substation Automation

2023.04.01-2023.09.30(Expected)

I started this internship in ABB about 5 months ago. Due to the confidential agreement I signed, I can't share much information here. But I will tell you that the workspace is very nice(except for the extreme heat this summer) and our colleagues as well. I think, so far the biggest benefit I had is to learn to cooperate with my teammates. Yes, indeed I did team works before, but they were always easy to divide to independent parts -- I write the code, you collect the result, he writes the report and she will present; we discussed together but one thing has only one executer -- we will never conflict. This time we are writing the same repository. More problems came out: "What should I comment here to let my colleague understand what I'm trying to do?",  "How should the interface be like so we can both take advantages from?", ... I'm glad to have my colleagues teach me, discuss with me and encourage me all these days.

## Projects in Master Program

### Robot Competition

*Arduino, Raspberry Pi*, *Python*

Empty PET bottles are everywhere after a party! We were asked to devise a robot to collect them on different terraces and recycle. Our robot, Well-E, equipped with a motion system with four wheels, a soft gripper and a bottle detection system driven by TensorFlow Lite model, collected 130 points in 10 minutes and won the competition.

More details can be found in [the final report](https://drive.google.com/file/d/1a6YLnnijZq9Y63XLg7rrciTr51LOR2Sg/view?usp=sharing).

### Fixed-base throwing

*Python*

How to throw the object to a desire target position? Previously, Yang proposed a method featured with a hedgehog-shape like data structure storing the robot geometrical information and backwards reachable tube representation storing the objects flying dynamics information. This project continuous his work and adapt the original method from the mobile robot(a robot with omnidirectional wheels) to the more generic settings -- the fixed-base robot(It may sounds easier with a fixed-base one intuitively, but actually it's more constrained and extra information have to be stored offline), by expanding the velocity hedgehog. Some algorithm optimization methods are applied and accelerated it by ~20 times. In addition, we also explored a more complex problem -- controlling rather the landing position but the orientation.

Find out more from [the report](https://drive.google.com/file/d/1AA1faNb2QtpUauX2Eej-r46uxwxERK81/view?usp=sharing) if you are interested!
