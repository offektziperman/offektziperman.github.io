---
layout: archive
title: "Mode Locked Laser"
permalink: /mode_locked/
author_profile: true
redirect_from:
  - /mode_locked
--- 
A mode locked laser is a special kind of laser which emits a periodic train of ultrashort light pulses, having temporal width ~ 1 picosecond. Since the temporal duration of the pulses is much shorter than the period, the peak power of the laser can be orders of magnitude greater than its average power. In a typical laser (continuous wave), The different temporal modes in the cavity are **out of phase**, in a mode locked laser thousands of temporal modes oscillate **in phase** resulting in a short intense light pulse. 

<p align="center"> 
  <img src='/images/Modelocking.gif' width="800">
</p>
A key component in any mode locked laser is a saturable absorber. Saturable absorbers are nonlinear components which exhibit intensity discrimination, meaning their transmittance depends on the input intensity of the light. The combination of satrable absorbtion and gain essentially makes a mode locked laser. The goal of this project was to make a mode locked laser where the saturable absorber is simply a multimode fiber. In this scheme, light occupying a single spatial mode is coupled to a multimode fiber (MMF), whose output facet is spliced to a single mode fiber as shown below. The light transmittance at the splicing point depends on the interference of the excited MMF modes. At high intensity, the interference is modified by Kerr nonlinearity making the transmittance at the splicing point power-dependent and making the configuration, with proper tuning, a saturable absorber. Here is a sketch of our setup with the multimode-singlemode splice pictured in the middle, and the output pulse train from our laser.
<p align="center">
  <img src='/images/Setup.png' width="400" height="300">   <img src='/images/mode_locked_results.png' width="450" height="300">
</p>
