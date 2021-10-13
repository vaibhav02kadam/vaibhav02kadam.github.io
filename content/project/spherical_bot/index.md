---
title:  Search and Reconnassiance using Spherical Robot.
summary: <div align= "justify">  Spherical robot is palms-sized robot with in built Pan-360 system and can be teleoperated using a andriod phone. Investigations were made to develop a robust and ergonomic spherical robot and control its wobble while manevuering due to its highly nonlinear nature. </div>
# tags:
# - Deep Learning
date: "2021-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Spherical robot in action
  focal_point: Smart

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: "https://youtu.be/LVJ2bTSwBdU"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

### ABOUT THE PROJECT

<div align= "justify"> Spherical Robot is teleoperated ball-shaped mobile rolling robot with all electronics inside. It is equipped with an onboard Pan-360 vision system that provides visual feedback which is then transmitted to the operator thereby enabling better control of the robot’s movement. A manually operated spherical robot has been designed that provides visual feedback for reconnaissance and search. The design of the robot can be easily modified to add sensors for collecting application-specific information to the operator. This work was carried out under the guidance of Prof. Leena Vachhani at NCETIS IIT Bombay. </div>

### SKILLS INVOLVED

  
- ROS & ROS plugins.
- C++ & Python.
- Motion planning & control algorithms.
- Embedded Control Devevlopment.
- Robotics Product Development.
- Design in Solidworks & Fabrication.
- Rapid Prototyping.
- MATLAB Multibody simulation.
- Sensor Interfacing.
- PCB designing and prototyping.
- 3D Printing.
- Gazebo, RViz
- Troubleshooting real robot hardware

###  SPHERICAL ROBOT 



<div align= "justify">
Spherical robots are non-holonomic rolling robots that have advantages compared to 4WD robots to manevoure in cluttered indoor environment. The spherical robot has yoke having actuator that drives the robot ahead with pendulums to steer with shift of CoM.
</div>
<br>


  {{<video src ="small_spherical_bot.mp4"  >}}

### DESIGN AND DEVELOPMENT

<div align= "justify">
My research involved developing a novel palm-sized robot that has ergonomic design. Focused in developing compact spherical robot that can be easily deployed. I contributed in rapid prototyping of the robot. Spherical robot has symmetric body and CoM plays a crucial role. Designing a robot considering its CoM to lie on a calculated co-ordinate involved in numerous iterations and prototyping. Design was developed in SOLIDWORKS and to understand its motion it was simulated in MATLAB Multibody Simulation (Simmechanics).
</div>
</br>

{{<figure src ="spbot.jpg">}}

### CONTROL SOFTWARE DEVELOPMENT

<div align= "justify">
Developing software to integrate all elements. Along with sensor interfacing such as IMU and encoders. Worked on embedded control algorithms to reduce wobble of spherical robot and for position and velocity control of actuators. Contributed to a ROS package for spherical bots. Validated feedback control algorithms with ground truth from VICON Motion capture systems.
</div>

### REAL ROBOT HARDWARE
<div align= "justify">
Spherical robot investigations included great extent of experimentation, testing & on field deployments. Worked on deployments with real robot hardware and its troubleshooting. Furthermore investigated in fabrication of polycarbonate Hull (outer shell) and its design analysis.
</div>

</br>

{{< gallery album="spbot" >}}

> ## Spherical Robot in **NEWS** 
> Published in TIMES OF INDIA</br>
> Check it [here](https://timesofindia.indiatimes.com/city/mumbai/mumbai-iit-b-profs-create-robot-for-reconnaissance-search-ops/articleshow/81694432.cms)
> Glad to be the key contributor to the project.
  {{<figure src="sp_news.jpg" >}}


## Spherical Robot Demo Visits 

{{< gallery album="themes" >}}