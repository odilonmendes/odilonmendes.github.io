---
layout: archive
title: "Teaching & Academic Activities"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

### Teaching Philosophy and Academic Engagement

The integration between theoretical rigor and practical experimental application guides the academic and educational activities developed alongside undergraduate and graduate Engineering programs at the **Federal University of Ceará (UFC)** and the **Federal Institute of Education, Science and Technology of Ceará (IFCE)**.

A multidisciplinary background — spanning Mechatronics Engineering, Telecommunications Engineering, Electrical Engineering, and Aeronautical Safety (ITA) — provides students and mentees with a holistic perspective on complex engineering and STEM challenges.

---

### Courses & Topics of Interest

* **Smart Grid and Forecasting:** High-spatial-resolution, rapid-update mesoscale weather forecasting for transmission corridors, spanning remaining useful life (RUL) estimation algorithms, dynamic thermal rating, and georeferenced risk maps.
* **Classical and Modern Control Systems:** Mathematical modeling in time and frequency domains, predictive control with transport delay (dead-time systems), state-space control, and robust/fractional-order control.
* **Computer Vision & Digital Image Processing:** Spatial filtering, mathematical morphology, segmentation, and machine learning for medical and industrial images.
* **Automation & Robotics:** Forward and inverse kinematics of robotic manipulators, electromechanical actuation, and real-time systems.
* **Metaheuristic Optimization:** Bio-inspired algorithms (PSO, Swarm Intelligence, Genetic Algorithms) applied to complex engineering problems.

---

### Recorded Courses and Activities

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
