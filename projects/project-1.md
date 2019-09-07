---
layout: project
type: project
image: images/drone1.jpg
title: Drone Traffic Profiling and Protocol Reverse Engineering
permalink: projects/drone1
# All dates must be YYYY-MM-DD format!
date: 2015-07-01
labels:
  - Drone
  - Security
summary: My team developed a robotic mouse that won first place in the 2015 UH Micromouse competition.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
  <img class="ui image" src="../images/micromouse-robot-2.jpg">
  <img class="ui image" src="../images/micromouse.jpg">
  <img class="ui image" src="../images/micromouse-circuit.png">
</div>

<description of drone fingerprinting. why?>

For this ongoing project, I was assigned the task of modifying preexisting python2 code and updating the ayntax to reflect python3. Because I learned how to parse through a json file that details packet information and use the NumPy and the Matplotlib librares to arrange and plot packet data.

Here is some code that illustrates how we read values from the line sensors:

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).



