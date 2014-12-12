Final-P2: Rotation of a Pendulum
========

This problem asks for a program to model the rotation of a pendulum. Deliverables include
a graph of the pendulum's position when it's stable (equilibrium), and an unstable position.

The following is the dimensionless differential equation used in the program.

d^2 phi/ d tau^2 + (1 - a/l*omega^2*sin(omega*tau))*sin(phi) = 0 

By choosing Omega=150, we get stability:
Angle vs Time
-----
![alt text](https://github.com/AndrewWong-Phys2200/Final-P2/blob/master/stable.png)

By choosing Omega=140, we get instability:
Angle vs Time
-----
![alt text](https://github.com/AndrewWong-Phys2200/Final-P2/blob/master/unstable.png)

In this figure, the pendulum continuously rotates.

The critical Omega value when the pendulum transitions from unstable to stable is about ~145.
