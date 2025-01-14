---
title: Self-Driving Vehicle
layout: project
image: ../assets/images/self-driving-vehicle/competition_diagram_cropped.png
link: /projects/self-driving-vehicle
---

## Overview

With a partner, I developed a self-driving car for the ENPH 353 competition. The project centered on training a robot to autonomously navigate a track in Gazebo simulator while avoiding pedestrians and identifying parked vehicles by their license plates and parking space numbers. This project strengthened my expertise in machine learning, data collection pipelines, and practical robotics applications. 

### Key Features:
- **Track Navigation**: Trained and optimized an imitation learning convolutional neural network (CNN) using TensorFlow to enable smooth navigation around a track in simulation. I wrote a script to automatically collect and label data for training and validation.
- **Vehicle Identification**: Utilized SIFT and neural networks to identify parked cars, returning their parking numbers and license plate details with near-perfect accuracy.
   **Pedestrian Avoidance**: Incorporated computer vision techniques to avoid pedestrians dynamically while maintaining efficient path-following behavior.

**Check out the code we used to make it all happen as well as more details about our implementation on [Github](https://github.com/cvgjnh/self-driving-vehicle-controller)!**

---

## Technologies and Tools

- **Machine Learning Frameworks**: TensorFlow, OpenCV
- **Programming Languages**: Python
- **Simulation Tools**: Gazebo, ROS
- **Machine Learning Techniques**: Convolutional Neural Networks (CNN), Imitation learning
- **Computer Vision Techniques**: SIFT (Scale-Invariant Feature Transform)

---

## Gallery

<section class="section">
    <div class="container">
        <div class="columns is-multiline is-custom-gapless">
            <div
                class="column is-full-mobile is-half-tablet is-one-third-desktop is-one-third-widescreen is-one-third-fullhd">
                <figure class="image">
                    <img src="{{site.baseurl}}/assets/images/self-driving-vehicle/competition_diagram.png"
                        alt="Competition Layout">
                    <figcaption class="has-text-centered">The layout of the competition, including obstacles and locations of all parked vehicles.</figcaption>
                </figure>
            </div>

            <div 
                class="column is-full-mobile is-half-tablet is-one-third-desktop is-one-third-widescreen is-one-third-fullhd">
                <figure class="image">
                    <img src="{{site.baseurl}}/assets/images/self-driving-vehicle/vehicle_view.png" alt="Vehicle View">
                    <figcaption class="has-text-centered">Example camera view for vehicle.</figcaption>
                </figure>
            </div>

            <div
                class="column is-full-mobile is-half-tablet is-one-third-desktop is-one-third-widescreen is-one-third-fullhd">
                <figure class="image">
                    <img src="{{site.baseurl}}/assets/images/self-driving-vehicle/loss_accuracy.png"
                        alt="Loss Graph">
                    <figcaption class="has-text-centered">Loss graph of the trained model for character classification.</figcaption>
                </figure>
            </div>
            <div
                class="column is-full-mobile is-half-tablet is-one-third-desktop is-one-third-widescreen is-one-third-fullhd">
                <figure class="image">
                    <img src="{{site.baseurl}}/assets/images/self-driving-vehicle/pedestrian_crossing.png" alt="H-bridge Circuit">
                    <figcaption class="has-text-centered">Demonstration of pedestrian detection using frame differencing. 
                    </figcaption>
                </figure>
            </div>
        
       
        </div>
    </div>
</section>

---



Explore the project repository on [GitHub](https://github.com/cvgjnh/self-driving-vehicle-controller).
