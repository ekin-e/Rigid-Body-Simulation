# Rigid-Body-Simulation

## Features

### Box-Wall Interaction
In this interaction, a box which is an instance of the RigidBody class collides with a stationary wall, which is an immovable object. The collison is then handled using an impulse-based method. The box's position and angular velocity is updated which simulates the repsonse of hitting a stationary surface. The box can bounce from all 4 corners of the screen.

### Box-Box Interaction
This interaction involves 2 or more boxes (both instances of the RigidBody class) colliding with each other. The collison correctly gets detected by checking the overlap between the two boxes and resolving the collision. This simulates the response to a collision between 2 moving objects, including the transfer of momentum and angular momentum.


### User Interaction
Users can use the keyboard to control the direction of the applied force. Press the arrow keys to change the direction of the force.

Users can interact with the simulation using the mouse. When the mouse is pressed, users can click and drag one of the boxes in the simulation. This applies force to the box in the direction of whichever arrow key was pressed. The users can also interact with individual boxes, which means the force will be applied to the selected box. Click and drag the boxes to interact with them.
