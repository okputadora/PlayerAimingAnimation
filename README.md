# PlayerAimingAnimation
prereq: Make sure you have the animation rigging package installed (you need to enable preview packages to see it)

First, I created a  player object (ybot@happywalk) that serves as a container for the player mesh/animations, the weapon transform, and two rig layer poses (one for running around with the gun down, and one for aiming the gun).

![character structure](./characterstructure.png)

Each of the Riglayer pose objects have a "Rig" component with a single "weight" value. By changing the value of weight from a script, I can transition smoothly between different poses. 


<video width="320" height="240" controls>
  <source src="./poseweight.mp4" type="video/mp4">
</video>