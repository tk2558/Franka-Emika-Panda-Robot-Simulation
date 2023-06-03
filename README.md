# Franka-Emika-Panda-Robot-Simulation

The objective of this project is to implement a controller in order to get a robot to go and pick up
two red blocks and drop them in the green bowl. The robot in question is a model of the Frank-Emika
Panda robot which possesses 7 revolute joints and therefore it has 7 degrees of freedom. The position of
the green bowl defined in spatial frame coordinates is (-0.3, 0.55, 0.65). Meanwhile the positions of the
two red blocks are (0.15, 0.67, 0.65) and (0.35, 0.58, 0.65) respectively. The
Pybullet library for python will be used in order to create a simulation of the movement of the robot.
