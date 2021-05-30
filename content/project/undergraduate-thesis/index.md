---
title: Implementation of Longitudinal and Lateral Control on Autonomous Vehicle
summary: Undergraduate thesis.
tags:
- Autonomous Vehicle
date: ""

links:
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/fadamsyah/final-project
url_pdf: "https://digilib.itb.ac.id/index.php/gdl/view/50131/"
url_video: "https://www.youtube.com/watch?v=AbmKmgrQWpM&ab_channel=AugieWidyotriatmo"


---
<b>Supervisors : </b> [Prof. Yul Yunazwin Nazaruddin](https://scholar.google.com/citations?user=Rve3vEYAAAAJ&hl=en) & [Augie Widyotriatmo, Ph.D.](https://scholar.google.co.id/citations?user=MtHwNU4AAAAJ&hl=id)

I worked with [Prasetyo W. L. Sanjaya](https://www.linkedin.com/in/prasetyowls/) on the topic of implementation of longitudinal and lateral control systems for a real-scale autonomous golf cart as a capstone project. We used the PID concept as the longitudinal controller and the [Stanley algorithm](http://ai.stanford.edu/~gabeh/papers/hoffmann_stanley_control07.pdf) as the lateral controller. We were greatly helped by Udiana Bambang, M.Eng on hardware installations. Responsibilities include:

* Designing a drive-by-wire system on a golf cart
* Designing a longitudinal and lateral control [module](https://github.com/fadamsyah/vehicle_control/blob/master/src/Python/stanley_2d.py) using Python
* Designing a 2D state estimation [module](https://github.com/fadamsyah/vehicle_control/blob/master/src/Python/ekf_2d_imu.py) incorporating accelerometer, gyroscope, GNSS, and vehicle nonholonomic constraint using the Extended Kalman Filter algorithm
* Implementing a control system consisting of path following and speed controller for an autonomous golf cart

<b>Tools &emsp; &nbsp;&nbsp; :</b> Python, Arduino, ROS, CARLA Simulator<br>
<b>Libraries &nbsp; :</b> Numba, Numpy, Matplotlib, Pandas<br>
<b>Sensors &nbsp;&nbsp; :</b> IMU, GNSS, Absolute encoder, Linear transducer<br>
<b>Actuators :</b> Nema 34, Brushed DC motor