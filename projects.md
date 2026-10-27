---
layout: default
title: Research
description: "Research projects in humanoid robotics, robot control, wearable robotics and soft sensing."
---

<p class="eyebrow">Selected work</p>

# Research projects

<p class="lead">From dynamics, actuators, and feedback control to learned policies deployed on physical robots.</p>

## Current focus · Humanoid robotics

### Learning-based locomotion and sim-to-real

Developing reinforcement-learning methods for humanoid locomotion with an emphasis on physical deployment. The work connects simulation fidelity, actuator dynamics, feedback interfaces, and robust behavior on hardware.

**Key themes:** locomotion RL · system identification · domain randomization · sim-to-real.

### Coordinated locomotion and manipulation

Exploring how learning-based lower-body control can coordinate with model-based upper-body control, particularly when a humanoid has different actuator characteristics across its joints.

**Key themes:** balance · whole-body coordination · model-based control · precise manipulation.

### Actuator modeling and real-time integration

Characterizing drivetrain behavior and integrating learned policies with low-level control software. These are essential system-level considerations for reliable and reproducible robot performance.

**Key themes:** actuator dynamics · real-time control · hardware debugging · simulation interfaces.

> Current KIMM research is described at the level that is appropriate for a public portfolio. Detailed results and demonstrations can be added as they are cleared for release.

## Motion planning and numerical optimization

At the Agency for Defense Development (ADD), my research included nonlinear model predictive control and numerical optimization. Selected conference contributions include [MPPI-based navigation under limited observations]({{ '/publications' | relative_url }}), [multi-vehicle deployment with NMPC]({{ '/publications' | relative_url }}), and QP-based engineering design.

## Wearable robot control · KAIST EXO Lab

### MPC-based stride-to-stride reference generation

{% include youtube.html id="DeFXXFtqL-Y" title="MPC-based stride-to-stride reference generation" %}

Studied model predictive control for one-stride reference trajectories under modeling errors and external disturbances. The formulation considered zero-moment-point stability and gait-phase transitions.

### Learning human motion with limited robot degrees of freedom

{% include youtube.html id="wcGt7EAkdVg" title="Human motion transfer to a wearable robot" %}

Explored transferring human walking styles to wearable robots using [Adversarial Motion Priors](https://arxiv.org/abs/2104.02180), subject to joint, energy, and wearer-safety constraints.

### Robust control for wearable robots

{% include youtube.html id="u0uSIhfIuNE" title="Robust wearable robot control" %}

Investigated learning-based and model-based control for systems subject to nonlinear, time-varying disturbances from a human wearer.

## Soft sensing and human–robot interaction

### Pneumatic mechanomyography for hand gesture recognition

![Hand gesture recognition accuracy chart](images/gesture_static/GesturesAccuracy.png)

Developed a tendon-observation approach to wrist gesture recognition using pneumatic mechanomyography (pMMG). In the reported evaluation with 10 participants and five-fold cross-validation, 28 gestures were classified with **98.0% accuracy**, compared with **93.1%** for the evaluated eight-channel sEMG baseline.

[Read the paper in IEEE Transactions on Industrial Informatics](https://ieeexplore.ieee.org/document/10136753).

### Robust gesture recognition during arm motion

{% include youtube.html id="spRBrlzH1nE" title="Gesture recognition during dynamic arm movement" %}

Studied the effects of arm movement, sensor placement, and out-of-distribution gestures on classification robustness.

### Soft sensing for gait monitoring

{% include youtube.html id="vO7Zg8ciqf0" title="Soft sensor gait analysis" %}
{% include youtube.html id="fRwCSk-NRls" title="Real-time gait analysis" %}

Developed and evaluated soft sensing approaches for real-time gait-phase and motion-state assessment.

## Selected earlier course project

### Momentum Frame · Learning physics from momentum information

{% include youtube.html id="tmLDXB6z8Mc" title="Momentum Frame demonstration" %}

In KAIST CS570, explored a neural surrogate for material-point-method (MPM) simulation using noise-to-noise learning, reconstruction loss, adversarial objectives, and a [CoordConv layer](https://arxiv.org/abs/1807.03247).

[Technical skills →]({{ '/skills' | relative_url }}) · [Complete publications →]({{ '/publications' | relative_url }})
