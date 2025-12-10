---
layout: project
title:  MAE 3270, Torque Wrench Design Project

description: Ansys and CAD Project
technologies: [Ansys, Autodesk Fusion, MATLAB]
image: /assets/images/3270-img.png
---

For my Mechanics of Materials class, we were asked to design, CAD, and analyze a torque wrench. Our design is based on safety requirements and threshholds defined in the project prompt, and we used MATLAB to calculate the dimensions needed to fulfill those requirements based on our chosen material properties. 

[PDF form of the report]({{ "/assets/MAE3270 Final Project.pdf" | relative_url }}) in PDF format.

Design Project

5.2.1 Results

1. Image of CAD model

![Photo of CAD model]({{ "/assets/images/3270 images/CAD drawing.png" | relative_url }}){: .inline-image-r style="width: 200px}
 




2. A description of our materials' relevant mechanical properties.

Typically used in the aerospace, defense, and high performance automotive industries, 300M is a highly resilient material with exceptionally high yield and fatigue strengths. A material choice of 300M for our wrench allows us to make the thickness dimensions relatively slim, allowing the torque wrench to be used on bolts in tight spaces. However, the dimensions do not compromise performance with our geometry producing a normal stress of about 64ksi, which is only about 28% of the yield limit of 230 ksi.








3. Diagram communicating how loads and boundary conditions were applied to theFEM model.


4. Normal strain contours (in the strain gauge direction) from FEM



5. Contour plot of maximum principal stress from FEM




6. Summarize results from FEM calculation showing maximum normal stress (anywhere), load point deflection, strains at the strain gauge locations

maximum normal stress (anywhere): 63935 psi

load point deflection: 0.20277in

strains at the strain gauge locations:1161 (µε)


7. Torque wrench sensitivity in mV/V using strains from the FEM analysis

1.16 mV/V at 600 in-lbf using half bridge 


8. Strain gauge selected 

VISHAY- C2A series strain gages- 062LW

C2A-06-062LW-350


This strain gauge fits comfortably on the dimensions of our CAD and has a fatigue life of 105 cycles at ±1700 microstrain and 106 cycles at ±1500 microstrain. Our FEM calculated a strain of 1161microstrain at the strain gauge, which would insinuate a fatigue life larger than the provided range, making it more than sufficient.




