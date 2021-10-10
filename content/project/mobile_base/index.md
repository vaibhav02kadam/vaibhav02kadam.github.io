---
title: Mobile Base with Spherical Robots as wheels
summary: <div align= "justify"> The project investigated the use of spherical robots as wheels. A omnidirectional mobile base was developed each spheros at 120 degrees apart connected via a link. A kinematic model for orienting and commanding the velocities of these actuation is developed. Various experiments were performed with feedback from Vicon Motion Capture systems. </div>
# tags:
# - Deep Learning
date: "2019-06-05T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Mobile Base
  focal_point: Center

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: "https://github.com/vaibhav02kadam/Mobile_base_sphero"
url_pdf: "https://ieeexplore.ieee.org/abstract/document/9123198"
url_slides: "https://drive.google.com/file/d/1dXOPVmUuvN7ZxRmnzbVeUBNcnv5Oxfar/view?usp=sharing"
url_video: "https://www.youtube.com/watch?v=jAoLYkS1-F0"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
### ABOUT THE PROJECT

<div align="justify"> The project investigated the use of spherical robots as wheels. The commerically available Sphero mini, spherical bots with IDU (Internal Driving Unit) were used. A omnidirectional mobile base was developed each spheros at 120 degrees apart connected via a link. Each robot is independently actuated. In order for the three robots to coordinate for mobile robot, the kinematic model for orienting and commanding the velocities of these actuation is developed. Various experiments were performed with feedback from Vicon Motion Capture systems. </div>

{{<video src ="mobile_base_waypoint_navigation.mp4" >}}

### SKILLS INVOLVED

- Kinematic Modelling of Mobile robots.
- Way-Point Navigation.
- Trajectory Tracking.
- Vicon MoCap.
- ROS-Python.
- Design and Development of Snap Ball joints.

### DESIGN AND DEVELOPMENT
<div align="justify"> The sphero mini is snap fit into the ball joint of each link. Developing a ball joint was a challenging such that the sphero is placed within the joint and has less friction to move easily. The design was developed in SOLIDWORKS and was 3D printed with ABS material using FDM. </div>

###  KINEMATICS AND EXPERIMENTS
<div align="justify"> The kinematic model was developed inorder to derive the required heading velocities and angles for each spheros. Provided the linear velocity and angular velocity of mobile base, the velocities were calculated using inverse kinematics that can be found here Kinematic model 

Waypoint Navigation                    |  Circle Tracking 
:-------------------------------------:|:-------------------------:
{{<video src ="plot_waypoint.mp4" >}}  |  {{<figure src="perfect_circle.jpg" width= "500px" >}}


<!-- {{<video src ="plot_waypoint.mp4" >}}  {{<figure src="perfect_circle.jpg" >}} -->

- Spheros can be communicated using a python package via bluetooth. Each sphero were commanded headed angle and velocities via laptop and the position feedback was taken from VICON MoCAP using the ROS package.

- Python ROS wrappers were written to interface with bluepy python package. The kinematic model was validated with experiments like waypoint navigation and circular trajectory tracking. The above figure shows the results of the experiments done.
</div>  

## <div align= "center"> Want to know more ?? </div>

### <div align= "center"> Checkout this Talk by me at IIT Bombay </div>


{{< youtube jAoLYkS1-F0>}}


