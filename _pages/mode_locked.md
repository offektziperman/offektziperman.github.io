---
layout: archive
title: "Mode Locked Laser"
permalink: /mode_locked/
author_profile: true
redirect_from:
  - /mode_locked
--- 
A mode locked laser is a special type of laser which emits ultrashort light pulses, having temporal width ~ 1 picosecond. Since the temporal duration of the pulses is much shorter than the pulse frequency, the peak power of the laser can be orders of magnitude greater than its average power. The different temporal modes in the laser have identical phase resulting in a short intense pulse.

<p align="center">
  <img src='/images/Mode_locking_example.gif' width="400" height="300">
</p>
A key component in any mode locked laser is a saturable absorber. Saturable absorbers are nonlinear components which exhibit intensity discrimination, meaning their transmitance depends on the input intensity of the light. The goal of this project was to make a mode locked laser where the saturable absorber is simpily a multimode fiber. In this scheme, light occupying a single spatial mode is coupled to a multimode fiber (MMF), whose output facet is spliced to a single mode fiber as shown below. The light transmittance at the splicing point depends on the interference of the excited MMF modes. At high intensity, the interference is modified by Kerr nonlinearity making the transmittance at the splicing point power-dependent and making the configuration a saturable absorber. This was our setup:
<p align="center">
  <img src='/images/Setup.png' width="400" height="300">
</p>
<p align="center">
  <img src='/images/mode_locked_results.png' width="400" height="300">
</p>
 
