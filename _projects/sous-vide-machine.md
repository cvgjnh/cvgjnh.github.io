---
title: Sous Vide Machine
layout: project
image: ../assets/images/sous-vide-machine/setup.jpg
link: /projects/sous-vide-machine/

---

## Overview

I designed and built a DIY sous vide machine from scratch, combining embedded systems programming, hardware design, and 3D printing to create a functional and intuitive device. The machine controls the temperature of water in a slow cooker by switching on and off an outlet in order to precisely cook food in a water bath.

<!-- One major challenge in controlling the temperature was the slow response time of water temperature to turning the power on or off. This resulted in large fluctuations of  (add stuff about the algorithm evolution and possibly Excel sheet graphs-->

### Key Features:
- **Accurate Temperature Control**: A thermistor, waterproofed using hot glue and heat shrink, provides real-time feedback to a control system, ensuring stable water temperature within 0.5 °C of the target.
- **User-Friendly Interface**: An I2C OLED display paired with a joystick allows users to easily set the temperature and cooking time.

---

## Technologies and Tools

- **Microcontroller**: Arduino
- **Programming**: C++
- **Hardware**: Thermistor, relay module, OLED display, joystick
- **Fabrication**: 3D printing
- **Development Environment**: VS Code, PlatformIO

---
<!-- ## Future Improvements

- Experiment with using 
--- -->

## Gallery

<section class="section">
    <div class="container">
        <div class="columns is-multiline is-custom-gapless">
            <div
                class="column is-full-mobile is-half-tablet is-one-third-desktop is-one-third-widescreen is-one-third-fullhd">
                <figure class="image">
                    <img src="{{site.baseurl}}/assets/images/sous-vide-machine/setup.jpg"
                        alt="Machine Setup">
                    <figcaption class="has-text-centered">The sous vide machine in action.</figcaption>
                </figure>
            </div>

            <div 
                class="column is-full-mobile is-half-tablet is-one-third-desktop is-one-third-widescreen is-one-third-fullhd">
                <figure class="image">
                    <img src="{{site.baseurl}}/assets/images/sous-vide-machine/oled.jpg" alt="OLED GUI">
                    <figcaption class="has-text-centered">OLED GUI for selecting time and temperature using the joystick.</figcaption>
                </figure>
            </div>

  
        
       
        </div>
    </div>
</section>
