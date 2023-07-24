---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
[Download Resume here](http://YexinZ1110.github.io/files/resume_robo_yexinz.pdf)
{% include base_path %}

<h2>Education</h2>
<ul>
  <li>
    <span style="float: left;"><b>ShanghaiTech University</b></span>
    <span style="float: right;"><em>Sept.2019-Jun.2023</em></span>
    <br>
    B.S. in Electrical and Information Engineering
  </li>
  <li>
    <span style="float: left;"><b>University of Pennsylvania</b></span>
    <span style="float: right;"><em>Sept.2023-May.2025(expected)</em></span>
    <br>
    M.S. in Robotics
  </li>
</ul>


<h2>Work Experience</h2>
<ul>
  <li>
    <b>P&G</b>
    <span style="float: right;"><em>Shanghai, China</em></span>
    <br>
    Robotics Software Engineering Intern
    <span style="float: right;"><em>Mar. 2023-Present</em></span>
    <ul>
      <li>Developed and implemented a robust algorithm for recognizing multiple boxes in complex backgrounds based on point clouds and grayscale images using <b>Open3D</b>. Achieved an accuracy rate of 97.5%.</li>
      <li>Calculated the transformation matrix between the robot coordinate system and the camera coordinate system.</li>
      <li>Designed and created an efficient path-planning strategy model for a palletizing robot using <b>Matlab</b>.</li>
    </ul>
  </li>
  <li>
    <b>ShanghaiTech University</b>
    <span style="float: right;"><em>Shanghai, China</em></span>
    <br>
    Research Assistant
    <span style="float: right;"><em>June. 2021-June. 2023</em></span>
    <ul>
    <h5>Acoustic Manipulation Platform</h5>
    <ul>
      <li>Developed an intuitive user-friendly interface using <b>Qt</b>, optimizing research efficiency and functionality.</li>
      <li>Integrated software modules with hardware components, enabling precise control of the end-effector and efficient communication with <b>FPGAs</b> through <b>CAN</b>.</li>
      <li>Created functions including real-time camera image display, objects' status updates, and parameter settings.</li>
      <li>Implemented efficient algorithms for image processing and feature extraction using <b>OpenCV</b>, enhancing particle localization capabilities.</li>
    </ul>
    <h5>Micro-Robot Calibration System</h5>
    <ul>
      <li>Engineered a software interface to efficiently control motor and needle hydrophone's movement efficiently, facilitating accurate calibration of the micro-robot system.</li>
      <li>Automated the acoustic field scanning process of the hydrophone, reducing scanning time by 80% through optimized software algorithms.</li>
      <li>Implemented advanced signal processing techniques using a Butterworth high-pass filter in <b>C++</b>, ensuring high-quality data analysis and visualization.</li>
      <li>Conducted image Jacobian matrix calibration using the least mean square method, ensuring exceptional system accuracy.</li>
    </ul>     
    </ul>
  </li>
</ul>


<h2>Publications</h2>>
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->
  
<h2>Projects</h2>
  <ul>{% for post in site.projects %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<h2>Competition Experience</h2>
<ul>
  <li>
    <b>2021 Xilinx China Women in Technology Hackathon</b>
    <span style="float: right;"><em>Oct.2021</em></span>
    <br>
    Runner-up and Best Innovation Award in China Region
    <br>
    Winner in Shanghai Division 
    <ul>
      <li>Led a team to develop a smart line-tracking car using Xilinx PYNQ-Z2 FPGA development board.</li>
      <li>Implemented Joystick control, orientation guidance, obstacle avoidance, and trajectory tracking functions.</li>
      <li>Demonstrated innovative solutions for the visually impaired by combining voice recognition and Bluetooth remote control.</li>
    </ul>
  </li>
</ul>


<h2>Skills</h2>
<ul>
  <li><b>Languages:</b> 
  <br>
  C/C++, Python, MATLAB, JAVA, HTML/CSS, JavaScript, Verilog, VHDL</li>
  <li><b>Technologies:</b>
  <br>
  OpenCV, Qt, Open3D, Keil, Proteus, Git, LaTeX, Solidworks, Unity(Vuforia), Vivado, Multism, PSIM, CST</li>
<!--   Node.js, Express.js, React.js, MongoDB, jQuery, Bootstrap，APIs，OpenCV, Qt, Open3D, Keil, Proteus, Git, LaTeX, Solidworks, Unity(Vuforia), Vivado, Multism, PSIM, CST</li> -->
</ul>
