---
title: Autonomous Robot
layout: project
image: ../assets/images/autonomous-robot/robot2.jpg
link: /projects/autonomous-robot/
order: 1
---


## Overview


I, alongside three teammates, designed and built an autonomous robot from scratch capable of traversing an obstacle course filled with rough terrain, traps, and chasms. The goal: retrieve treasures and deliver them to the finish line for the Engineering Physics "Robot Summer" competition ([full details here](https://docs.google.com/document/d/1w-FPY5TIh77HwoJq-ieJ4AjniQIBwqUylwcSBE2u_jk/edit?tab=t.0)). 

I primarily focused on:
- **Designing and building the arm**: A three-degree-of-freedom mechanical arm that extends up to 10 inches and rotates 60° to either side. I achieved this using servo motors, a stepper motor-driven rack and pinion, and a sonar sensor for precise treasure detection. 
- **High and low voltage power systems**: Designed the power distribution circuits to ensure stable operation.
- **H-bridge motor control**: Soldered and configured circuits for bidirectional wheel movement using DC motors.
- **Line-following control**: Implemented and tuned PID algorithms using reflectance sensors for accurate path following.

This project showcased my skills in:
- Embedded systems
- Algorithm development
- Hardware design
- Integration of multiple technologies into a cohesive system

**Check out the robot control code on [GitHub](https://github.com/cvgjnh/autonomous-robot)!**


---

## Technologies and Tools

- **Microcontrollers**: STM32 Blue Pill
- **Programming Languages**: C++  
- **Development Environments**: PlatformIO, VS Code
- **Hardware**: Ultrasonic sensors, IR sensors, reflectance sensors, hall effect sensors, DC motors, motor drivers, LiPo batteries  
- **Prototyping Tools**: Onshape, 3D printer, waterjet cutter, laser cutter

---


## Gallery

<section class="section">
    <div class="container">
        <div class="columns is-multiline is-custom-gapless">
            <div
                class="column is-full-mobile is-half-tablet is-one-third-desktop is-one-third-widescreen is-one-third-fullhd">
                <figure class="image">
                    <img src="{{site.baseurl}}/assets/images/autonomous-robot/competition_layout.png?"
                        alt="Competition Layout">
                    <figcaption class="has-text-centered">The competition layout and obstacles.</figcaption>
                </figure>
            </div>

            <div 
                class="column is-full-mobile is-half-tablet is-one-third-desktop is-one-third-widescreen is-one-third-fullhd">
                <figure class="image">
                    <img src="{{site.baseurl}}/assets/images/autonomous-robot/linkage.png" alt="Basket Lifting Mechanism">
                    <figcaption class="has-text-centered">CAD design of basket lifting mechanism.</figcaption>
                </figure>
            </div>

            <div
                class="column is-full-mobile is-half-tablet is-one-third-desktop is-one-third-widescreen is-one-third-fullhd">
                <figure class="image">
                    <img src="{{site.baseurl}}/assets/images/autonomous-robot/pickup_procedure.png"
                        alt="Treasure Pickup Procedure">
                    <figcaption class="has-text-centered">Demonstration of treasure pickup procedure.</figcaption>
                </figure>
            </div>
            <div
                class="column is-full-mobile is-half-tablet is-one-third-desktop is-one-third-widescreen is-one-third-fullhd">
                <figure class="image">
                    <img src="{{site.baseurl}}/assets/images/autonomous-robot/h_bridge.png" alt="H-bridge Circuit">
                    <figcaption class="has-text-centered">H-bridge circuit for bidirectional wheel movement.
                    </figcaption>
                </figure>
            </div>
            <div
                class="column is-full-mobile is-half-tablet is-one-third-desktop is-one-third-widescreen is-one-third-fullhd">
                <figure class="image">
                    <img src="{{site.baseurl}}/assets/images/autonomous-robot/robot2.jpg" alt="Robot">
                    <figcaption class="has-text-centered">Fully-assembled robot prototype.
                    </figcaption>
                </figure>
            </div>
       
        </div>
    </div>
</section>