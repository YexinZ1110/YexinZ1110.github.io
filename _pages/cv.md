---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<h2>Education</h2>
<ul>
  <li>
    <b>ShanghaiTech University</b>
    <div style="text-align: right; display: inline;"><em>Sept.2019-Jun.2023</em></div>
    B.S. in Electrical and Information Engineering
  </li>
  <li>
    <b>University of Pennsylvania</b>
    <div style="text-align: right; display: inline;"><em>Sept.2023-May.2025(expected)</em></div>
    M.S. in Robotics
  </li>
</ul>




<h2>Work Experience</h2>
<ul>
  <li><b>P&G</b></li> 
  <div style="text-align: right; display: inline;"><em>Shanghai, China</em></div>
  Robotics Software Engineering Intern
  <div style="text-align: right; display: inline;"><em>Mar. 2023-Present</em></div>
  <ul>
    <li>Developed and implemented a robust algorithm for recognizing multiple boxes in complex backgrounds based on point clouds and grayscale images using Open3D. Achieved an accuracy rate of 97.5%.</li>
    <li>Calculated the transformation matrix between the robot coordinate system and the camera coordinate system.</li>
    <li>Designed and created an efficient path-planning strategy model for a palletizing robot using Matlab.</li>
  </ul>
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
  <li><b>2021 Xilinx China Women in Technology Hackathon</b>
  <div style="text-align: right; display: inline;"><em>Oct.2021</em></div>
  Runner-up and Best Innovation Award in China Region
  <br>
  Winner in Shanghai Division
  <ul>
    <li> Led a team to develop a smart line-tracking car using Xilinx PYNQ-Z2 FPGA development board.</li>
    <li> Implemented Joystick control, orientation guidance, obstacle avoidance, and trajectory tracking functions;</li>
    <li> Demonstrated innovative solutions for the visually impaired by combining voice recognition and Bluetooth remote control.</li>
  </ul>
</ul>

<h2>Skills</h2>
<ul>
  <li><b>Languages:</b> 
  <br>
  C/C++, Python, MATLAB, JAVA, HTML/CSS, JavaScript, Verilog, VHDL</li>
  <li><b>Technologies:</b>
  <br>
  Node.js, Express.js, React.js, MongoDB, jQuery, Bootstrap，APIs，OpenCV, Qt, Open3D, Keil, Proteus, Git, LaTeX, Solidworks, Unity(Vuforia), Vivado, Multism, PSIM, CST</li>
</ul>