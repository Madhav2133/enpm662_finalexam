# ENPM 662 - Introduction to Robot Modelling
## Final Exam

### Problem-5: Humanoid Robot [8 pts] 
A humanoid robot with legs equipped with wheels combines the advantages of bipedal locomotion with the efficiency of wheeled movement, creating a versatile and highly functional machine. 

Create a URDF package for a humanoid robot with legs equipped with wheels.

The dimensions of the robot are arbitrary and can be adjusted as needed to fit the intended application.
The robot's design features 14 degrees of freedom (DOF) [4 pts] distributed as follows:

Wheels: 2 DOF for independent control of forward/backward movement and omnidirectional steering.

Ankles: 2 DOF to allow tilting and rotational adjustments for balance and dynamic movement. 

Knees: 2 DOF for bending and extending to support walking, crouching, and transitioning to wheeled mode. 

Hips:2 DOF to enable forward/backward motion and lateral adjustments during walking or wheeled
transitions. 

Shoulders: 2 DOF per arm, allowing forward/backward and lateral movements. 

Elbows: 2 DOF per arm for bending and rotation, ensuring dexterity and precision in tasks. 

Wrist: 1 DOF for rotational control, enhancing object manipulation. 

Neck: 1 DOF for rotational motion, enabling the robot
to turn its head for improved situational awareness. 

Include a position controller for all joints to ensure
precise and coordinated movements across the robot's articulated structure. 

Additionally, equip the robot's head with a lidar sensor to enable environment mapping and obstacle detection, enhancing its navigational capabilities.

The project should incorporate both Gazebo [2 pts] and RViz simulations [2 pts]. In Gazebo, demonstrate that the robot is successfully spawned and remains stable in a zero-gravity environment. In RViz, ensure the sensor data is visualized accurately. There is no requirement to animate or move the robot in this task. For this task, you will collaborate with your teammates from Project 2 to seek assistance and effectively tackle the problem (you can use the same cad models).
