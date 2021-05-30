---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: AI Engineer Intern
    company: Neura Integrasi Solusi
    company_url: 'https://neurabot.io/'
    company_logo: 
    location: Indonesia
    date_start: '2021-02-06'
    date_end: ''
    description: |2-
        <b>Supervisor&#58;</b> [Dr. Thomhert Suprapto Siadari](https://www.linkedin.com/in/thomhertsiadari/)<br>Currently developing Deep Learning models to detect and segment objects on microscopic images. Responsibilites include:

        * Data preprocessing
        * Model training and evaluation
        * Delivering model to Neurabot's platform team
        * Delivering reports and documentations
        * Create a [repository](https://github.com/fadamsyah/pytorch_deseg_module) for future use

  - title: Undergraduate Research Assistant
    company: Instrumentation, Control, and Decision Systems (ICoDeS) Laboratory
    company_url: 'https://ik.fti.itb.ac.id/lab-icodes/'
    company_logo: 
    location: Bandung, Indonesia
    date_start: '2019-08-01'
    date_end: '2020-10-31'
    description: |2-
        <b>Supervisors&#58;</b> [Prof. Yul Yunazwin Nazaruddin](https://scholar.google.com/citations?user=Rve3vEYAAAAJ&hl=en) & [Augie Widyotriatmo, Ph.D.](https://scholar.google.co.id/citations?user=MtHwNU4AAAAJ&hl=id)<br>Worked with [Prasetyo W. L. Sanjaya](https://www.linkedin.com/in/prasetyowls/) on the topic of implementation of longitudinal and lateral control systems for autonomous golf cart as a capstone project. We were greatly helped by Udiana Bambang, M.Eng on hardware installations. Responsibilities include:

        * Designing a drive-by-wire system on a golf cart
        * Designing a longitudinal and lateral control [module](https://github.com/fadamsyah/vehicle_control/blob/master/src/Python/stanley_2d.py) using Python
        * Designing a 2D state estimation [module](https://github.com/fadamsyah/vehicle_control/blob/master/src/Python/ekf_2d_imu.py) incorporating accelerometer, gyroscope, GNSS, and vehicle nonholonomic constraint using the Extended Kalman Filter algorithm
        * Implementing a control system consisting of path following and speed controller for an autonomous golf cart

        <b>Tools &emsp; &nbsp;&nbsp; :</b> Python, Arduino, ROS, CARLA Simulator<br>
        <b>Libraries &nbsp; :</b> Numba, Numpy, Matplotlib, Pandas<br>
        <b>Sensors &nbsp;&nbsp; :</b> IMU, GNSS, Absolute encoder, Linear transducer<br>
        <b>Actuators :</b> Nema 34, Brushed DC motor


  - title: Undergraduate Research Student
    company: Instrumentation, Control, and Decision Systems (ICoDeS) Laboratory
    company_url: 'https://ik.fti.itb.ac.id/lab-icodes/'
    company_logo: 
    location: Bandung, Indonesia
    date_start: '2019-08-01'
    date_end: '2019-11-30'
    description: |2-
        <b>Supervisors&#58;</b> [Prof. Yul Yunazwin Nazaruddin](https://scholar.google.com/citations?user=Rve3vEYAAAAJ&hl=en)<br>Worked with five of my friends on conducting research in utilizing neural networks to improve vehicle state estimation. Responsibilities include:

        * Designing a sensor fusion module incorporation data from accelerometer, gyroscope, GNSS, and neural networks using the Error-State Kalman Filter algorithm
        * Designing a recurrent neural networks model
        * Publishing a [conference paper](publication/localization-method-for-autonomous-car-using-virtual-sensing-system/) 

        <b>Tools &emsp; &nbsp;&nbsp; :</b> Python, CARLA Simulator<br>
        <b>Libraries &nbsp; :</b> Keras, Tensorflow, Numpy, Matplotlib, Pandas<br>

  - title: Teaching Assistant
    company: Institut Teknologi Bandung
    company_url: ''
    company_logo: 
    location: Bandung, Indonesia
    date_start: '2017-08-01'
    date_end: '2021-01-31'
    description: |2-
        Responsibilities include but not limited to delivering academic & hands-on tutorials, and examining assignments & quizzes. Courses:
        
        * Engineering Drawing (Nov 2020 - Jan 2021)
        * Engineering Mathematics II (Jan - May 2019)
        * Circuits & Electronics (Aug - Dec 2018)
        * Engineering Drawing (Aug - Dec 2017)

        <b>Tools :</b> LaTeX, Solidworks, LTspice

  - title: Internship
    company: Toyota Motor Manufacturing Indonesia
    company_url: 'https://www.toyota.co.id/'
    company_logo: 
    location: Jakarta, Indonesia
    date_start: '2019-06-16'
    date_end: '2019-08-16'
    description: Worked with my friend on developing a low-cost internet-based automation system. We created an Arduino module enabling users to control bulbs from the internet. We also delivered hands-on tutorials on using Arduino.

design:
  columns: '2'
---
