---
layout: project
title:  MAE 3270, Torque Wrench Design Project
description: Ansys and CAD Project
technologies: [Ansys, Autodesk Fusion, MATLAB]
image: /assets/images/3270-img.png
---
<style>
.page-header {
  padding-top: 60px !important;
}

.project-header {
  padding-top: 60px !important;
}
</style>

For my Mechanics of Materials class, we were asked to design, CAD, and analyze a torque wrench. Our design is based on safety requirements and threshholds defined in the project prompt, and we used MATLAB to calculate the dimensions needed to fulfill those requirements based on our chosen material properties. This project was in collaboration with Garrett Smith.


[PDF form of the report]({{ "/assets/MAE3270 Final Project.pdf" | relative_url }}) in PDF format.

Design Project

5.2.1 Results

**1. Image of CAD model**

<div style="clear: both;"></div>

![Photo of CAD model]({{ "/assets/images/3270 images/CAD drawing.png" | relative_url }}){: .inline-image-l}

<div style="clear: both;"></div>
 


**2. A description of our materials' relevant mechanical properties.**

Typically used in the aerospace, defense, and high performance automotive industries, 300M is a highly resilient material with exceptionally high yield and fatigue strengths. A material choice of 300M for our wrench allows us to make the thickness dimensions relatively slim, allowing the torque wrench to be used on bolts in tight spaces. However, the dimensions do not compromise performance with our geometry producing a normal stress of about 64ksi, which is only about 28% of the yield limit of 230 ksi.

<div style="clear: both;"></div>

![Photo of CAD model]({{ "/assets/images/3270 images/3270.21.png" | relative_url }}){: .inline-image-l}

<div style="clear: both;"></div>

<div style="clear: both;"></div>

![Photo of CAD model]({{ "/assets/images/3270 images/3270.22.png" | relative_url }}){: .inline-image-l}

<div style="clear: both;"></div>

**3. Diagram communicating how loads and boundary conditions were applied to theFEM model.**
<div style="clear: both;"></div>

![Photo of CAD model]({{ "/assets/images/3270 images/3270.3.png" | relative_url }}){: .inline-image-l}

<div style="clear: both;"></div>

**4. Normal strain contours (in the strain gauge direction) from FEM**

<div style="clear: both;"></div>

![Photo of CAD model]({{ "/assets/images/3270 images/3270.41.png" | relative_url }}){: .inline-image-l}

<div style="clear: both;"></div>

<div style="clear: both;"></div>

![Photo of CAD model]({{ "/assets/images/3270 images/3270.42.png" | relative_url }}){: .inline-image-l}

<div style="clear: both;"></div>

**5. Contour plot of maximum principal stress from FEM**



<div style="clear: both;"></div>

![Photo of CAD model]({{ "/assets/images/3270 images/3270.51.png" | relative_url }}){: .inline-image-l}

<div style="clear: both;"></div>
<div style="clear: both;"></div>

![Photo of CAD model]({{ "/assets/images/3270 images/3270.52.png" | relative_url }}){: .inline-image-l}

<div style="clear: both;"></div>

**6. Summary results from FEM calculation showing maximum normal stress (anywhere), load point deflection, strains at the strain gauge locations**

maximum normal stress (anywhere): 63935 psi
<div style="clear: both;"></div>

![Photo of CAD model]({{ "/assets/images/3270 images/3270.61.png" | relative_url }}){: .inline-image-l}

<div style="clear: both;"></div>

load point deflection: 0.20277in
<div style="clear: both;"></div>

![Photo of CAD model]({{ "/assets/images/3270 images/3270.62.png" | relative_url }}){: .inline-image-l}

<div style="clear: both;"></div>

strains at the strain gauge locations:1161 (µε)
<div style="clear: both;"></div>

![Photo of CAD model]({{ "/assets/images/3270 images/3270.63.png" | relative_url }}){: .inline-image-l}

<div style="clear: both;"></div>

**7. Torque wrench sensitivity in mV/V using strains from the FEM analysis**

1.16 mV/V at 600 in-lbf using half bridge 


**8. Strain gauge selected**

VISHAY- C2A series strain gages- 062LW

C2A-06-062LW-350
<div style="clear: both;"></div>

![Photo of CAD model]({{ "/assets/images/3270 images/3270.8.png" | relative_url }}){: .inline-image-l}

<div style="clear: both;"></div>

This strain gauge fits comfortably on the dimensions of our CAD and has a fatigue life of 105 cycles at ±1700 microstrain and 106 cycles at ±1500 microstrain. Our FEM calculated a strain of 1161microstrain at the strain gauge, which would insinuate a fatigue life larger than the provided range, making it more than sufficient.




