# COS 426 Computer Graphics Competition Entries
As part of COS 426 Computer Graphics, an upper level Princeton Computer Science course taught in Spring 2020, students were invited to think up, design, and implement additional features on top of course assignments for submission to a staff-judged, class-wide competition. Attached below are my prize-winning entries, alongside brief descriptions of the technical work required. As these were technically part of coursework, I can't attach the source code due to Honor Code regulations -- however, they all were significant additions and modifications to the minimum code required to complete the assignment. For reference, other entries can be seen [here](https://www.cs.princeton.edu/courses/archive/spring20/cos426/gallery).

# Assignment 3 - Raytracing   *Bronze Prize*
![](ContestSubmissions/A3/art-jak4-wash.png)
*Stop the Spread!*

![Soap Bubble](ContestSubmissions/A3/art-jak4-bubble.png)
*Soap Bubble*

Assignment 3 involved implementing a basic raytracing system, including reflections, diffuse color, and basic lighting in OpenGL. I implemented a soap bubble for my competition entry, using a random-offset, sinusoidal color and refraction model based on surface tangent angles to produce a natural, oily look without physical simulation.

# Assignment 5 - Cloth Simulation   *Silver Prize*
![Rip and Tear](ContestSubmissions/A5/rip2.gif)
*Cut and Tear*

Assignment 5 was a basic cloth simulation, including collision physics and gravity. I added interactivity for my competition entry, allowing the user to cut the cloth using a mouse. As the original framework was not designed with tearing in mind (or any sort of dynamic addition / subtraction of fabric), this ended up being a major addition, involving figuring out ways to "disappear" certain fabric nodes without breaking the physics system or introducing unnatural behavior.

# Final Project - Catcher   *Honorable Mention*

![Catcher Gameplay](ContestSubmissions/FinalProject/Catcher.gif)
*Catcher Gameplay*

With a group of 2 others, my final project was a physics-based, vaccine-themed 3D "catcher" game. I implemented the physics, controls, score-system, gamification, bits of lighting, and some UI fixes. You can play [here](https://kirkhamj16.github.io/426-catcher/). Frame-rate may be low on slower machines, optimization was not a priority! You can view a full playthrough [here](https://youtu.be/AWU5k7yN944).
