---
layout: inner
title: About
permalink: /about/
---


### Resume
Please feel free to contact me if you'd like a copy of my resume. I can be reached at [akhil.sankar@sensei.ag](akhil.sankar@sensei.ag).

&nbsp;
### A bit about myself...

<p style='text-align: justify;'>
Hello! My name is Akhil and I am (primarily) a backend engineer with academic training in mechanical engineering. I have always been interested in the intersection of these disciplines and have spent the last few years of my career developing APIs/services to support a variety of IoT projects, from smart home automation to farming automation (first at Wink, subsequently at Farmshelf and currently at Sensei Ag). Over the years, I have developed a more focused interest in the cognitive aspects of robotics such as perception and path-planning. As such, I've recently begun my graduate studies, taking courses in mechatronics, system modeling & identification and robotic manipulation. I am currently interested in software-oriented opportunities in any application of these subdomains.

Outside of work and classes, I keep myself busy on the tennis court, playing the piano or simply just walking around and taking in New York from time to time. This winter, I also had a chance to try skiing in Utah and Vermont for the first time!
</p>
&nbsp;
### My current project:

<p style='text-align: justify;'>
My current passion project is a 3 DoF SCARA robotic arm equipped with an electromagnet as its end-effector to perform a pick-and-place operation. The idea is to use a camera to track any new objects introduced into the workspace, perform a coordinate transformation calculation to determine the location of the object with respect to the physical coordinate space. 
</p>

[Here's a quick demo](https://www.youtube.com/watch?v=rHNCS8GCMkQ&feature=youtu.be) of the object tracking algorithm in action.

<p style='text-align: justify;'>
The robotic arm then performs an inverse kinematics operation to determine the requisite joint orientations to reach the object. Other concepts of interest include a proportional control algorithm to position the electromagnet using a linear actuator using a DC-motor with quadrature encoder assembly.
</p>

![The assembly currently looks something like this](../img/manipulator_current_state.png)

More coming in a series of blog posts as I continue to develop this project into a working prototype!


