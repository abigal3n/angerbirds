A small physics simulation project that allows the user to launch a 2D "bird" up with a simulated mass and realistic gravity, this little game programmed in lua utilizes actual physics concepts like force vectors, parabolic motion due to gravitational acceleration, and newtons first law to help me better understand the concepts in my introductory physics courses!

Features and concepts:
- Force vectors and Geometry: Game calculates a force vector to act on the bird dependent on the distance and angle of the users click from the bird
- Newtons First Law: F=ma, game then calculates an x and y acceleration for the bird by dividing the force components calculated above by the simulated mass of the bird, the acceleration is then applied to the current bird velocity components.
- Reaction Forces: When the bird collides with the ground it has a reaction force applied to it via the collision, given the earth ground has a much larger simulated mass than the bird a large reaction force (and acceleration is exerted on the bird) causing its vertical velocity to drop dramatically, sometimes the bird even bounces!
- Friction: A simulated coefficient of friction is added between the ground and the bird and once the bird hits the ground a frictional force is calculated counteracting its existing horizontal velocity, that frictional force than causes an acceleration that is applied to the bird velocity eventually slowing it to a stop.

If you are reading this thank you for your interest in my little physics passion project! :)
