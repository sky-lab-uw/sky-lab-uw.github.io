---
layout: page
permalink: /research areas and projects/
title: Research
description: 
nav: true
nav_order: 1
---

<p style="text-align: left; font-size: 18px;"><strong>The research and open-source platforms developed at Sky-Lab would not be possible without the generous support of our sponsors. <br> We are sincerely grateful for their vital contributions.</strong></p>

<div style="display:flex; flex-wrap:wrap; justify-content:space-between; align-items:center; gap: 20px; margin: 40px 0;">
  <img src="../../assets/img/Research/USDOT.png" alt="USDOT" style="height: 120px; object-fit: contain; flex: 1; min-width: 120px;">
  <img src="../../assets/img/Research/WisDOT.png" alt="WisDOT" style="height: 120px; object-fit: contain; flex: 1; min-width: 120px;">
  <img src="../../assets/img/Research/CCAT.png" alt="CCAT" style="height: 120px; object-fit: contain; flex: 1; min-width: 120px;">
  <img src="../../assets/img/Research/UW-COE.png" alt="UW-COE" style="height: 120px; object-fit: contain; flex: 1; min-width: 120px;">
  <img src="../../assets/img/Research/WARF.png" alt="WARF" style="height: 120px; object-fit: contain; flex: 1; min-width: 120px;">
  <img src="../../assets/img/Research/NVIDIA.png" alt="NVIDIA" style="height: 120px; object-fit: contain; flex: 1; min-width: 120px;">
</div>

---
<!-- <h3 style="font-size: 18px; font-weight: bold; text-align: left;">Research Examples</h3> -->
<!-- <h3 style="font-size: 18px; font-weight: bold; text-align: left;">Autonomous Transportation and Cyber-Physical Systems (CPS) testbeds</h3> -->


<h3 style="font-size: 18px; font-weight: bold; text-align: left;">Research Examples</h3>

<p style="text-align: left; font-weight: bold; margin-bottom: 5px;">- Autonomous Transportation and Cyber-Physical Systems (CPS) Testbeds</p>
<p style="text-align: left;">Sky-Lab has an electric connected and autonomous van, a Ford E-Transit retrofitted with a drive-by-wire system, sensors, onboard units, 5G connectivity for remote control and data sharing, and a high-performance computer (e.g., 3 LiDARs, 7 cameras, radars, NETGEAR Nighthawk M6 Pro 5G mobile hotspot, etc.). Sky-Lab also has several sets of portable roadside units and traffic signals, which can be used to form an array of customizable traffic control systems at an intersection or along a corridor. This vehicle and equipment together serve as Cyber-Physical Systems (CPS) testbeds for developing and testing advanced technologies, such as vehicle-to-everything (V2X) and vehicle-to-infrastructure (V2I) communication, sensor fusion, autonomous driving algorithms, AR/VR-enabled digital twin platforms, and foundation AI model deployment. <br> Sky-Lab hosts high-performance Lambda Servers, which feature multiple Nvidia GPUs, including A6000, RTX 4090, and 4080. We are also deeply grateful to Nvidia, which has donated two RTX PRO 6000 Blackwell GPUs and 20,000 GPU hours on A100 clusters to the lab.</p>

<div style="display:flex; flex-wrap:nowrap; justify-content:center; align-items:center; gap: 0; margin: 7px 0;">
  <img src="../../assets/img/Research/AV1.png" alt="AV1" style="height: 350px; object-fit: contain;">
  <img src="../../assets/img/Research/AV2.png" alt="AV2" style="height: 350px; object-fit: contain;">
  <!-- <img src="../../assets/img/Research/AV3.jpg" alt="AV3" style="height: 200px; object-fit: contain;"> -->
  <img src="../../assets/img/Research/AV4.png" alt="AV4" style="height: 350px; object-fit: contain;">
  <img src="../../assets/img/Research/AV5.jpg" alt="AV5" style="height: 350px; object-fit: contain;">
</div>

<div style="display:flex; justify-content:center; align-items:flex-start; gap: 7px; margin: 15px 0;">
  <div style="text-align: center;">
    <video width="auto" height="370" controls preload="metadata">
      <source src="{{ '/assets/img/Research/run175_360p.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="margin-top: 10px; font-size: 14px; margin-top: 3px;">Live demo at 2025 AAA Safe Mobility Conference, Madison, WI</p>
  </div>
  <div style="text-align: center;">
    <video width="auto" height="370" controls preload="metadata">
      <source src="{{ '/assets/img/Research/end-to-end.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="margin-top: 10px; font-size: 14px; margin-top: 3px;">End-to-end autonomous driving in urban and rural environments</p>
  </div>
</div>





<p style="text-align: left; font-weight: bold; margin-bottom: 5px;">- Remote Vehicle Operations and Cloud-Based AI Deployment</p>
<p style="text-align: left;">Our team has engineered a complete remote operations (teleoperation) platform for our autonomous van. Leveraging its 5G connectivity, the vehicle can be controlled in real-time for driving, operation, and data collection from any location with an internet connection, such as a conference room or an off-site lab (see video examples below). More importantly, our platform is designed for remote AI model deployment. This enables a powerful hardware-in-the-loop workflow: real-time sensor data is streamed from the vehicle to a local computer or a cloud service like Amazon Web Services (AWS), where AI models can process the data and transmit control commands back to the vehicle for immediate execution. <strong>We welcome collaboration with partners from industry, academia, and public agencies. Please contact us to discuss how our platform can help you remotely develop, deploy, and test your models, or to explore other forms of partnership.</strong></p>

<div style="display:flex; justify-content:center; align-items:flex-start; gap: 7px; margin: 15px 0;">
  <div style="text-align: center;">
    <video width="auto" height="370" controls preload="metadata">
      <source src="{{ '/assets/img/Research/sky-remote-driving-1min.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="margin-top: 10px; font-size: 14px; margin-top: 3px;">Remote driving from the office. The van can be seen passing the window on the right at 0:02 and 0:42.</p>
  </div>
  <div style="text-align: center;">
    <video width="auto" height="370" controls preload="metadata">
      <source src="{{ '/assets/img/Research/remote_boyue_zilin.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="margin-top: 10px; font-size: 14px; margin-top: 3px;">Students testing remote driving function with Logitech G923 Racing Wheel and Pedals</p>
  </div>
</div>



<p style="text-align: left; font-weight: bold; margin-bottom: 5px;">- Sky-Drive: An Evolving Open-Source Project</p>
<p style="text-align: left; font-style: italic; margin-top: -3px; font-size: 15px;">Open-source code will be released on this website. Stay tuned!</p>
<p style="text-align: left;">

This has been a long-term initiative of our lab since in summer 2023. We have made significant progress, as detailed in our recent publication "Sky-Drive: A Distributed Multi-Agent Simulation Platform for Human-AI Collaborative and Socially-Aware Future Transportation" Journal of Intelligent and Connected Vehicles (accepted, in-press).

Sky-Drive enables distributed, multi-agent human-AI interaction by integrating Unreal Engine, CARLA, ROS, WebSocket, and custom scenario generation pipelines. It supports real-time behavior modeling of pedestrians, human-driven vehicles (HVs), and autonomous vehicles (AVs), along with collaborative testing across multiple terminals.

A core component of the Sky-Drive platform is the Sky-Lab, which provides a full Human/Hardware-in-the-Loop (HiL) setup for immersive simulation and behavioral analysis. This setup includes specialized equipment to create a realistic and data-rich testing environment:
</p>

<ul style="text-align: left; margin-top: -10px;">
  <li><strong>VR Headsets:</strong> The HTC Vive Pro Eye (with eye-tracking) and Meta Quest Pro are used to create immersive experiences and explore new possibilities in human-AI-machine interaction.</li>
  <li><strong>Human/Hardware-in-the-Loop (HiL) System:</strong> This system enables researchers to test and validate control systems, algorithms, and human-machine interfaces in a safe and controlled environment. By integrating hardware components and human input into the loop, researchers can evaluate the performance and reliability of their designs under realistic conditions.</li>
  <li><strong>Synchronization and Driving with Logitech Racing Wheel & Pedals:</strong> This enhances the realism of driving simulations and is designed to synchronize the simulation with the remote driving of our real-world autonomous van (a planned feature), allowing for more accurate studies of human behavior and interaction in vehicle-related research.</li>
</ul>

<p style="text-align: left;">


</p>

<div style="display:flex; flex-wrap:nowrap; justify-content:center; align-items:center; gap: 0; margin: 7px 0;">
  <img src="../../assets/img/Research/sky-drive_framework.png" alt="AV1" style="height: 700px; object-fit: contain;">
  <!-- <img src="../../assets/img/Research/AV2.png" alt="AV2" style="height: 350px; object-fit: contain;"> -->
  <!-- <img src="../../assets/img/Research/AV3.jpg" alt="AV3" style="height: 200px; object-fit: contain;"> -->
  <!-- <img src="../../assets/img/Research/AV4.png" alt="AV4" style="height: 350px; object-fit: contain;"> -->
  <!-- <img src="../../assets/img/Research/AV5.jpg" alt="AV5" style="height: 350px; object-fit: contain;"> -->
</div>

<div style="display:flex; justify-content:center; align-items:flex-start; gap: 7px; margin: 15px 0;">
  <div style="text-align: center;">
    <video width="auto" height="370" controls preload="metadata">
      <source src="{{ '/assets/img/Research/full_vr.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="margin-top: 10px; font-size: 14px; margin-top: 3px;">Sky-Drive demo: distributed, multi-agent VR experiment</p>
  </div>
  <div style="text-align: center;">
    <video width="auto" height="370" controls preload="metadata">
      <source src="{{ '/assets/img/Research/sky-drive.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="margin-top: 10px; font-size: 14px; margin-top: 3px;">Sky-Drive overview</p>
  </div>
</div>





<h3 style="font-size: 18px; font-weight: bold; text-align: left;">Outreach Activities</h3>
<p style="text-align: left;">We connect our research to the real world through our Cyber-Physical Systems (CPS) platform, which combines our open-source Sky-Drive platform and our lab’s full-scale autonomous van (both software and hardware). This integrated system enables a complete pipeline from simulation to on-road testing. We regularly demonstrate our progress to professionals from industry, academia, and public agencies to ensure our work meets real-world needs.</p>


<p style="text-align: left; font-weight: bold; margin-bottom: 5px;">- Live demo at 2025 AAA Safe Mobility Conference, Madison, WI</p>
<p style="text-align: left; margin-top: 5px;">We hosted a live demonstration of our electric autonomous van for over 50 conference attendees from industry, academia, and public agencies in the Madison Capitol area. The demo showcased our integrated software and hardware systems and featured our in-house developed technologies, including autonomous driving, path following, crash avoidance, and traffic signal recognition.</p>

<div style="display:flex; flex-wrap:wrap; justify-content:center; align-items:flex-start; gap: 10px; margin: 15px 0;">
  <img src="../../assets/img/Research/outreach/AAA0.jpg" alt="AAA0" style="width: 350px; height: auto; object-fit: contain;">
  <img src="../../assets/img/Research/outreach/AAA1.jpg" alt="AAA1" style="width: 350px; height: auto; object-fit: contain;">
  <img src="../../assets/img/Research/outreach/AAA2.jpg" alt="AAA2" style="width: 350px; height: auto; object-fit: contain;">
  <img src="../../assets/img/Research/outreach/AAA3.jpg" alt="AAA3" style="width: 350px; height: auto; object-fit: contain;">
  <img src="../../assets/img/Research/outreach/AAA4.jpg" alt="AAA4" style="width: 350px; height: auto; object-fit: contain;">
  <img src="../../assets/img/Research/outreach/AAA5.jpg" alt="AAA5" style="width: 350px; height: auto; object-fit: contain;">
</div>


<p style="text-align: left; font-weight: bold; margin-bottom: 5px;">- Live demo at 2025 Wisconsin Automated Vehicle External (WAVE) Advisory Committee Meeting</p>
<p style="text-align: left; margin-bottom: 5px;">We had the privilege of presenting our latest research on connected and automated vehicles (CAVs) to a distinguished audience, including WisDOT Deputy Secretary Scott Lawry, his colleagues at WisDOT, and partners from industry and academia. The presentation was followed by a live demonstration of our vehicle's capabilities, which took place after the workshop "CAV Technologies and Applications: A Transportation Stakeholders Resource Guide".</p>

<div style="display:flex; flex-wrap:wrap; justify-content:center; align-items:flex-start; gap: 10px; margin: 5px 0;">
  <!-- <img src="../../assets/img/Research/outreach/AAA0.jpg" alt="AAA0" style="width: 350px; height: auto; object-fit: contain;"> -->
  <img src="../../assets/img/Research/outreach/WAVE1.jpg" alt="WAVE1" style="width: 350px; height: auto; object-fit: contain;">
  <img src="../../assets/img/Research/outreach/WAVE2.jpg" alt="WAVE2" style="width: 350px; height: auto; object-fit: contain;">
  <img src="../../assets/img/Research/outreach/WAVE3.jpg" alt="WAVE3" style="width: 350px; height: auto; object-fit: contain;">
  <img src="../../assets/img/Research/outreach/WAVE4.jpg" alt="WAVE4" style="width: 350px; height: auto; object-fit: contain;">
  <img src="../../assets/img/Research/outreach/WAVE5.jpg" alt="WAVE5" style="width: 350px; height: auto; object-fit: contain;">
  <img src="../../assets/img/Research/outreach/WAVE6.jpg" alt="WAVE6" style="width: 350px; height: auto; object-fit: contain;">
</div>
