+++
title = 'Pneumagami: A Pneumatically Actuated Origami-Inspired Robotic Arm' 
draft = false
+++

<!--more-->

The Pneumagami is an origami-inspired robotic arm with air pouch actuators, designed by PhD candidate Mustafa Mete with input from previous master’s students. My main contribution to the project was sensor integration and the development of a control algorithm.

# Pneumatically Actuated Module

A key innovation is the stacking of multiple origami submodules, where only the first layer is powered. The upper and middle layers extend passively, reducing the need for expensive linear valves and minimizing the arm’s weight.

{{< figure src="/img/3RDA_1st_layer.gif" alt="Alt text for the image"  width="50%" class="center" >}}

# Passive Extensions

The animation below demonstrates the arm’s motion after adding the passive modules.

{{< figure src="/img/passive.gif" alt="Alt text for the image"  width="50%" class="center" >}}

# Pneumatic Gripper

The following animation showcases the pneumatic gripper in action.

{{< figure src="/img/gripper.gif" alt="Alt text for the image"  width="50%" class="center" >}}

# Inverse Kinematic Model

The controller focuses on managing the positions of the three actuated legs in the first module. An inverse kinematic model was developed to calculate the leg positions required to achieve the desired end-effector position.

{{< figure src="/img/inv_kin.gif" alt="Alt text for the image"  width="100%" class="center" >}}