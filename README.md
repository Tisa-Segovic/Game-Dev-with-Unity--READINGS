# Game-Dev-with-Unity-Project-1

For this week's assignment, I created a simple version of a Rube Goldberg Machine. This was my very first time using unity, so I primarily focused on exploring the built-in capabilities of the Unity Game Engine.

I started by creating several 3D objects, including a cube, a sphere, a capsule and a plane. Different shapes were arranged in dirrent positions, however, the next thing that I focused on was the hierarchy of the created objects. Since this Rube Goldberg Machine had several moving components, I organized the objects according to how they were moving through the Rube Goldberg Machine. The next thing that I decided on was that certain objects should be sub-grouped together, so for example, the "wooden sticks" on the wall that are sorrounded by a "wooden frame" will all be grouped, each stick by its respective number (how they appear in order on the wall), under the "frame". This really helped in visually simplyfying the hierarchical order of objects.


After that, I started working on making certain objects move naturally, and other objects being static. When it came down to walls, polls, and bridges, they all had to be static, while other objetcs, like the balls and spheres had to move. The movement had to obey the laws of physics, so I used the RigidBody Component added to the objects that were moving. The other objects were made static, so that the balls could roll on them.
