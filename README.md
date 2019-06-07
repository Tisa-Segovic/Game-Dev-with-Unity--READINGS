# Game-Dev-with-Unity-Project-1

For this week's assignment, I created a simple version of a Rube Goldberg Machine. This was my very first time using unity, so I primarily focused on exploring the built-in capabilities of the Unity Game Engine.

I started by creating several 3D objects, including a cube, a sphere, a capsule and a plane. Different shapes were arranged in dirrent positions, however, the next thing that I focused on was the hierarchy of the created objects. Since this Rube Goldberg Machine had several moving components, I organized the objects according to how they were moving through the Rube Goldberg Machine. The next thing that I decided on was that certain objects should be sub-grouped together, so for example, the "wooden sticks" on the wall that are sorrounded by a "wooden frame" will all be grouped, each stick by its respective number (how they appear in order on the wall), under the "frame". This really helped in visually simplyfying the hierarchical order of objects.

I used the plane objects in order to create the regular plane (almost imitating the ground), where other objects were placed onto. I manipulated the Directional Light, in order to make the overall scene appear more dark, almost as if the Rube Goldberg Machine process was taking place at dawn. I also further manipulated the Main Camera, in order for it to capture the overall process of the Rube Goldberg Machine from one corner.


After that, I started working on making certain objects move naturally, and other objects being static. When it came down to walls, polls, and bridges, they all had to be static, while other objetcs, like the balls and spheres had to move. The movement had to obey the laws of physics, so I used the RigidBody Component added to the objects that were moving. The other objects were made static, so that the balls could roll on them.


The main challenge was to make the objects more naturally, meaing that the objects had to be alligned well. For example, a rolling ramp had to be perfectly below another rolling ramp and above another, in order for the ball to bounce from one ramp onto another, slowly sliding down. I also had to pay attention to the width and rotation (angle-wise) in which the ramps were positioned. This had to be done for all the static elements, making it quite a learning process. I have spent a lot of time learning how to use different views/ perspectives (left, right, up, & down) for how to position each object correctly.
