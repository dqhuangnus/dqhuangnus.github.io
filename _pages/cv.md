---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D.**, University College London (UCL), London, UK &mdash; Feb 2026 &ndash; present
  * CRISP group, UCL East
  * Supervisor: Dr. Lorenzo Jamone
  * Research: tactile sensing for contact-rich robot manipulation
* **M.Sc. in Robotics**, National University of Singapore, Singapore &mdash; Aug 2024 &ndash; Jun 2025
  * GPA: 4.5/5.0
  * Courses: Machine Learning in Robotics, Robot Vision and AI, Robot Kinematics, Robot Dynamics and Control
* **B.Eng. in Automation**, Beihang University, Beijing, China &mdash; Sep 2020 &ndash; Jun 2024
  * GPA: 3.69/4.0
  * Courses: Automation Theory, Pattern Recognition and Intelligent Systems, Guidance and Control, Mathematical Modelling
  * Thesis: Path Integration Algorithm Based on Grid Cell Bio-intelligence

Research experience
======
* **Imitation Learning for Robotic Manipulation** &mdash; Aug 2024 &ndash; May 2025
  * National University of Singapore; Supervisor: Assoc. Prof. Chew Chee Meng
  * Developed imitation learning techniques for robotic manipulation with sequence models (RNN, LSTM, GRU, Decision Transformer)
  * Collected a dataset of expert demonstrations and evaluated models on accuracy, generalization and fidelity to expert behaviour
  * Developed a new model building on existing architectures for better performance in object-dense scenes

* **Robot Arm Grasping with Reinforcement Learning** &mdash; Sep 2024 &ndash; Nov 2024
  * National University of Singapore; Supervisor: Asst. Prof. Guillaume A. Sartoretti
  * Built a 6-DOF robot arm in MuJoCo with an RGB camera and tactile sensors for grasping in unstructured environments
  * Designed a DDPG agent with CNN visual encoding and a reward scheme favouring successful, efficient grasps

* **Path Integration Algorithm Based on Grid Cell Bio-intelligence** &mdash; Dec 2023 &ndash; Jun 2024
  * Beihang University; Supervisor: Assoc. Prof. Yuzhu Guo
  * Simulated rodent grid-cell path integration to reduce accumulated IMU error in inertial navigation, with LSTM-based error compensation
  * Reduced navigation error to 0.0062 m (holistic method) and 0.10 m (segmented method); published at ISAICS 2024

* **Liver Image Segmentation Based on CNN** &mdash; Mar 2023 &ndash; Jun 2023
  * Beihang University; Supervisor: Prof. Yang Li
  * Trained a U-Net on the LiTS dataset with a weighted Dice + BCE loss
  * Achieved 97.12% accuracy, 82.34% sensitivity, 99.87% specificity and 0.94 AUC

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Awards & honors
======
* Second Prize, Chinese Mathematics Competitions (CMC) &mdash; Nov 2021
* Third Prize, National English Competition for College Students &mdash; May 2021

Skills
======
* Programming & tools: Python, MATLAB, ROS, MuJoCo
* Languages: Chinese (native), English (advanced)
