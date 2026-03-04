---
layout: project
title: Nut cracker design
description: Additional problem from HW
technologies: [MATLAB, python]
image: /assets/images/diagram.jpg
---
For this project, I needed to find and design a simple nut cracker machine and pick a linear actuator that could work on the nut cracker. 
Given: The Force applied by the average human female: 65 lbs, the force exerted by the nut to be 490 lbs, and the distance between the hinge and the diameter of the nut being 1 inch , and the constraint that the nut cracker had to be within reasonable dimensions. - Based on the diameter of the nut, I estimated that L1, the distance from the hinge connecting the 2 arms of the nut cracker and the center of the nut where the force is applied, equals to 1.5 inches.

This is how I solved the problem:
I designed a very simple 2 part machine, connected by one pin. 
I then drew a free body diagram of one component, and calculated the moment about that pin, resulting in this equation:
Ma = L1*490 - L2 *65 = 0

L2 = 11.3 in - the total lenght of this nut cracker.



