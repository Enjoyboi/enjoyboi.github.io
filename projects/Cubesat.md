---
layout: project
type: project
image: img/Cubesat/HSFL.png  # Ensures a square crop for the home screen
title: "Ke Ao: A Low-Cost 1U CubeSat for Aerospace Education and Research"
date: 2025
published: true
labels:
  - Aerospace
  - CubeSat
  - Satellite Engineering
summary: "Ke Ao is a 1U CubeSat developed by the VIP Aerospace Technologies class at the University of Hawaiʻi to demonstrate AI-powered Earth imaging and low-cost spaceflight hardware."
---


<img class="img-full" src="../img/Cubesat/HSFL.png">

### Overview  
The **Ke Ao CubeSat** is a **1U satellite** developed by **Team Laniākea** as part of the **VIP Aerospace Technologies program** at the **University of Hawaiʻi at Mānoa**. The project aims to demonstrate **low-cost, student-led satellite design and AI-powered image recognition** in space. Ke Ao's primary mission is to **capture images of the Hawaiian Islands from orbit** and use **machine learning algorithms** to autonomously identify them. This aligns with the growing trend of **onboard AI processing** in small satellites, reducing the need for bandwidth-heavy data transmissions.

Another key objective of this mission is to **prove that CubeSats can be developed for under $10,000**, significantly lower than the industry standard of $100,000 or more. By leveraging **commercial off-the-shelf (COTS) components**, in-house fabrication at the **Hawaiʻi Space Flight Laboratory (HSFL)**, and collaboration with **Firefly Aerospace for launch**, Ke Ao serves as a proof-of-concept for cost-effective satellite development. The project also contributes to Hawaii’s aerospace workforce development, preparing students for careers in space engineering.

### My Role in the Project  
As part of the **software development team**, my role focused on **implementing and testing flight software for Ke Ao's onboard computer (OBC) and ground station systems**. I was responsible for **cleaning, documenting, and finalizing the Artemis COSMOS Teensy Flight Software** while assisting in the transition to **F Prime (F’) for future mission control software**. Additionally, I contributed to the **development of GNU Radio for signal processing**, which is critical for establishing **uplink and downlink communication** between the CubeSat and the ground station.

I worked alongside my team to **debug and restructure** various parts of the software, ensuring that it met the standards for **safety-critical systems in aerospace applications**. My contributions accounted for **a significant portion of the software team's efforts**, particularly in **documenting the “Life of a Packet”**, organizing **development kits**, and **testing code on FlatSat hardware**. Furthermore, I co-hosted a **GNU Radio workshop** and a **Git workshop** to help onboard new team members.

### Lessons Learned  
This project gave me invaluable experience in **real-world aerospace software development**, particularly in **satellite flight systems, embedded programming, and RF communications**. I learned how to **develop software for extreme environments**, where efficiency and reliability are crucial. Additionally, working with **GNU Radio** and **F Prime (F’)** exposed me to industry-standard tools for satellite communications and mission control.

Beyond technical skills, I gained **project management and teamwork experience** by collaborating with mechanical, avionics, and fiscal management teams. I also learned the importance of **documentation and knowledge transfer**, as CubeSat development often spans multiple semesters with different student contributors. This experience has solidified my interest in **space systems engineering** and has prepared me for future work in **aerospace and embedded systems**.

### Project Components  
The **Ke Ao CubeSat** consists of multiple subsystems:  

- **Avionics & Electrical Power System (EPS)**: Solar panels, power distribution, and batteries.  
- **Mechanical Systems**: Structural frame, antenna deployment, and thermal management.  
- **Software & On-Board Computer (OBC)**: Flight software for telemetry, command handling, and AI image recognition.  
- **Communications (COMMS)**: RF communication via **Astrodev Lithium-3 radio** and **LoRa RFM98 radio** for inter-satellite networking.  
- **Payload**: Camera module for Earth imaging and AI processing of images onboard.

### Current Status  
As of **Spring 2024**, the team has **completed 68% of hardware integration** and **33% of software development**. Key milestones achieved include:
- Assembling and testing the **solar panel system**.
- Verifying **Lithium-3 radio communication** through wired testing.
- Completing **software restructuring and documentation** for the flight software.
- Conducting workshops for **GNU Radio, Git, and satellite software development**.

Challenges this semester included **hardware delivery delays**, which impacted the overall timeline. However, the project is still on track for a future **test launch with Firefly Aerospace**.

### References  
- [Ke Ao Project - VIP Aerospace Technologies](https://www.hsfl.hawaii.edu)  
- [Artemis CubeSat Kit](https://www.hsfl.hawaii.edu/artemis-cubesat-kit-2/)  
- [NASA F Prime (F') Framework](https://nasa.github.io/fprime/)  
- [GNU Radio for Space Communications](https://www.gnuradio.org/)  

### Repository  
Source: <a href="https://github.com/myusername/ke-ao"><i class="large github icon "></i>myusername/ke-ao</a>  
