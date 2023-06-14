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
      <li>Developed and implemented a robust algorithm for recognizing multiple boxes in complex backgrounds based on point clouds and grayscale images using Open3D. Achieved an accuracy rate of 97.5%.</li>
      <li>Calculated the transformation matrix between the robot coordinate system and the camera coordinate system.</li>
      <li>Designed and created an efficient path-planning strategy model for a palletizing robot using Matlab.</li>
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
  Node.js, Express.js, React.js, MongoDB, jQuery, Bootstrap，APIs，OpenCV, Qt, Open3D, Keil, Proteus, Git, LaTeX, Solidworks, Unity(Vuforia), Vivado, Multism, PSIM, CST</li>
</ul>