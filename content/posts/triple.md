+++
title = 'Haptic Interface for Restoring Sensation After Nerve Damage' 
draft = false
+++

Damage to the sciatic nerve from surgery or an accident can cause loss of foot sensation, leading to walking difficulties and frequent tripping. My team and I aim to solve this by recreating foot sensation on the patient’s forearm.

<!--more-->

# system overview 

{{< figure src="/img/sys_overview.png" alt="Alt text for the image" width="120%" class="center" >}}

# Main subsystems

## The pneumatic sleeve 


To provide haptic feedback, we used air pouches that apply pressure on the forearm. These soft robotics actuators are mounted on a sleeve worn by the user.

{{< figure src="/img/air_pouches.png" alt="Alt text for the image" width="50%" class="center" >}}

## The diaphragm system

To pressurize the air pouches, we developed a diaphragm system actuated by a servo motor, avoiding bulky compressors or refillable gas canisters. The system includes 3D-printed components for the rack and frame, with silicone-cast joints and diaphragms.

{{< figure src="/img/diaphragm.png" alt="Alt text for the image" width="50%" class="center" >}}

# Foot Position Feedback

The pneumatic actuators respond to foot position, allowing the user to sense foot placement and avoid tripping. The animation below demonstrates the working principle of our haptic device.

{{< figure src="/img/footfound.gif" alt="Alt text for the image" width="100%" class="center" >}}