---
title: "Projects"
draft: false
---

## Inverse Lift Mapping with REINFORCE
<div style="display: flex; gap: 2rem; align-items: flex-start;">
<div style="flex: 1;">

### 2026

When on exchange at AGH, I enrolled in the Individual Research Project Related to Mechatronic Design course. However, I spent most of my free time during this semester developing the UASISI simulation framework. When it came time to put a project together, I decided to utilize my newly developed framework and I set forth to find a solution to map lift distribution to wing torsion. Using UASISI's python wrapper module along with the pyTorch package, I implemented a reinfocement learning scenario using a convolutional neural network as the agent. The code was included in UASISI's GitHub repo as an example.

[Code](https://github.com/Bel16ario/uasisi/tree/main/examples/reinforcementLearning) · [Report](/docs/reinforce.pdf) 

</div>
<img src="/images/projects/reinforce.jpg" alt="REINFORCE" style="width: 700px; border-radius: 1px; flex-shrink: 0;">
</div>

---

## UASISI
<div style="display: flex; gap: 2rem; align-items: flex-start;">
<img src="/images/projects/uasisi.jpg" alt="UASISI" style="width: 700px; border-radius: 1px; flex-shrink: 0;">
<div style="flex: 1;">

### 2025–2026

UASISI is an extendible and modular simulation framework written in C++. It is optimized for problems related to wings. I undertook this project when I realised the difficulty involved in coupling simulink with external software which was necessary for my thesis. For work relating to my thesis, I wanted to be able to integrate both Torch's Machine Learning capabilities and OpenFOAM simulations. I decided to port my simulation to a new framework that I developed from scratch. UASISI, like simulink, is signal based. Modules are implemented in separate C++ source files with separate dependencies. I have written about 10 modules so far, including a python wrapper and a lift estimation tool using Phillips' solution to Prandtl's Lifting Line Theory. Also included in the proyect is a logger and a python based data visualizer. I uploaded the project to GitHub and I am working on making the code more generic to accomodate more use cases and hopefully be useful to people other than myself. 

[GitHub](https://github.com/Bel16ario/uasisi)

</div>
</div>

---

## Bare Metal Oscilloscope
<div style="display: flex; gap: 2rem; align-items: flex-start;">
<div style="flex: 1;">

### 2024

For my final project in my Microcontrollers and Microprocessors course, I developed an audio digital oscilloscope using a Texas Instruments TIVA C TM4C1294 microcontroller. The project was coded in C and the Hardware Abstraction Layer (HAL) was written from scratch in TI's CCS IDE. A TFT display was used to display the audio signal. This course in general taught me not only to program in assembly and low level C, but also to effectively comb through very long datasheets.

[Code](https://github.com/Bel16ario/audioOsc)

</div>
<img src="/images/projects/oscilloscope.jpg" alt="Oscilloscope" style="width: 700px; border-radius: 1px; flex-shrink: 0;">
</div>

---

## Panel Method Solver
<div style="display: flex; gap: 2rem; align-items: flex-start;">
<img src="/images/projects/panel.jpg" alt="Panel Method" style="width: 700px; border-radius: 1px; flex-shrink: 0;">
<div style="flex: 1;">

### 2024

The final project in my Aerodynamics course was supposed to be to code a potential flow simulator. Due to the complexity and the short amount of time left, the project was changed to simply simulate flow over an airfoil using a pre-existing solver. I decided to write a simulator myself regardless and I used the Panel Method to do so. The program is coded in Go and it takes data files with airfoil coordinates, as well as flow parameters through arguments.

[Code](https://github.com/Bel16ario/panelsolver)

</div>
</div>

---

## PCPuma
<div style="display: flex; gap: 2rem; align-items: flex-start;">
<div style="flex: 1;">

### 2022–2023

Due to a student strike in autumn 2022, an oversight committee comprised by students, faculty administrators and university technical staff was created to improve wireless connectivity. In early 2023, I became a student representative and subsecuently, student coordinator in the connectivity committee. We oversaw the addition of around 30 additional wireless access points to the existing network and the expedition of a new network, PCPuma. I proposed an iniative to include students in PCPuma's roll-out. More than 650 students across all 14 engineering bachelors signed up. A partnership with CISCO was established to provide training and issue technical diplomas to the participating students. Those who succesfully passed training where then put into work brigades which ended up configuring the network's switches, writing testing scripts and measuring network performace across faculty grounds. In total, about 100 students participated and received certificates from the faculty.

[Newsletter 1](https://www.comunicacionfi.unam.mx/mostrar_nota.php?id_noticia=2669) · [Newsletter 2](https://www.comunicacionfi.unam.mx/mostrar_nota.php?id_noticia=2826)

</div>
<img src="/images/projects/pcpuma.jpg" alt="PCPuma" style="width: 700px; border-radius: 1px; flex-shrink: 0;">
</div>

---

## Line Follower
<div style="display: flex; gap: 2rem; align-items: flex-start;">
<img src="/images/projects/follower.jpg" alt="Line Follower" style="width: 700px; border-radius: 1px; flex-shrink: 0;">
<div style="flex: 1;">

### 2023

This line follower was built for the recruitment process into my faculty's robotics club. The frame was 3D printed and held together with copper inserts and metric screws. A maximum of two reflectivity sensors were allowed. A ESP-32 microcontroller programmed with Arduino was used alongside two pololu motors. It was the only line follower that managed to follow the line smoothly 

[Code]() · [Video](/docs/follower.mov)

</div>
</div>

---

## Matrix Solver
<div style="display: flex; gap: 2rem; align-items: flex-start;">
<div style="flex: 1;">

### 2022

This was the final project for my Introduction to Programming course. I developed a program written in C that can calculate the determinant of a square matrix of any size. This was my first approach to manual memory management and dynamic memory which were not part of the course. Matrix cofactors are calculated recursively.

[Code]()

</div>
<img src="/images/projects/matrix.jpg" alt="Matrix Solver" style="width: 700px; border-radius: 1px; flex-shrink: 0;">
</div>

---

## Consejo Table
<div style="display: flex; gap: 2rem; align-items: flex-start;">
<img src="/images/projects/consejo.jpg" alt="Consejo Table" style="width: 700px; border-radius: 1px; flex-shrink: 0;">
<div style="flex: 1;">

### 2019

This was the course project for my Design and Visual Communication (DVC) class during my senior year at Green Bay High School. Biomimicry was a central requirement in the course and during the first part of the academic year, I compiled photographs of nature during field visits. Particularly, I photographed leaves at the Domain Wintergardens. Through a few ideation stages, and with the influence of conic curves as well as constant client and stakeholder feedback, I landed on a steel, glass and MDF table design. Significant graphic material was rendered using Autodesk Inventor.

[Report](/docs/consejo.pdf) · [Poster](/docs/consejoPoster.jpg) · [Booklet](/docs/consejoBooklet.pdf) · [Cover](/docs/consejoCover.jpg)

</div>
</div>
