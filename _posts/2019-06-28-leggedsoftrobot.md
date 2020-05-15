---
layout: post
title: Design and Manufacture of a Legged Soft Robot
subtitle: This project was submitted as my 3rd year project as part of my undergraduate degree, QMUL 
tags: [robotics, design, soft robot, undergraduate, QMUL]
comments: true
cover-img:
  - "/img/big-imgs/workingonrobot.jpg"
  - "/img/big-imgs/conference.jpg" : "UK Undergraduate Research Conference, 2019"
  - "/img/projects/hexsoftmobilerobot/sideview.png" 
  - "/img/projects/hexsoftmobilerobot/pictureofrobot.png"


---
This project investigated a proof of concept approach to the design of a textile based leg that is primarily uses easily available techniques and materials. A linear actuator using the transformation of an object from a 2d area to a 3d volumetric object is investigated and tested to produce an operational leg that is used to create a hexapod robot.

This project was done under Dr Kaspar Althoefer's supervision.


The legged robot system developed is a proof of concept that has proven that such a system is capable of walking on a relatively flat surface without much trouble, which is successful at achieving the aims set initially. It does this with an extremely low cost in terms of the structure and actuator in comparison to other soft robots utilising materials such as silicone and moulding, and traditional robots utilising discrete joint systems. The system is also achieving its goal of being easily manufactured with materials and components that are easily available and low cost, with the exception being the parts involved in the control system such as the pressure regulator or the custom power distribution board. 

![Walking Robot Sped Up](/img/gif/walkingfast.GIF){: .mx-auto.d-block :}


In this design, the robot is capable of functioning using small binary valves that are cheaper, lighter and more energy efficient than the regulators for sections such as the actuators, and using a single regulator that would ensure that the pressures entering all the actuators and/or legs are below the maximum threshold. This would therefore lower the number of regulators needed from 6 to 2, with 6 binary valves used for the group control. 

![UR5 Mount](/img/projects/hexsoftmobilerobot/pictureofrobot.png){: .mx-auto.d-block :}


In terms of manufacturing, alternative materials and manufacturing techniques could be used to create parts with less variation than the manual method, which would therefore make it easier to accurately model and control. 

Variation within the legs has caused issues regarding the bending capabilities of each leg, with some legs bending more than others, and some having longer middle tubes than others which caused less points of contact under low loads which fixed itself as more weight was added through moving the electronics and control on board. 

The system developed was capable of supporting its own weight with all the electronics on board except for the compressor and power supply, reaching a total height of 37cm under full inflation, and 20cm when deflated. This is an almost 50\% reduction in the height of the fully inflated system which shows a clear advantage for transport of the system as the legs are able to decrease its volume. This can be further improved by decreasing the length of the supporting EPDM tube by evaluating different lengths to find the minimum effective length. 


The limitations and strengths of this type of leg are discussed, with possible gait patterns, actuation steps, and problems/solutions encountered when developing such a leg. The leg demonstrates clear advantages with regard to simplicity, ease of manufacturing, and low price, however there are limitations with regards to the materials used in this given they were chosen based on availability rather than optimal properties. 

These materials were sufficient to demonstrate a working hexapod robot with a tripod gait pattern to minimise the number of regulators used to only 6, and creating a robot that can achieve an almost %50 reduction in its height and therefore external volume by deflating the legs. 

Read the [Project Report here](/projectdata/MobileSoftRobot_Report.pdf)


Read the [Literature Review for all the background and theory here](/projectdata/MobileSoftRobot_Literature.pdf)