# Bubble-Shooter
In this project i used C++ to create a game, Bubble shooter. The aim is to clear all the bubbles. Destroy the bouncing bubbles by splitting them using bullets, but don’t let them touch you.

 compile the  code using

s++ main.cpp

and run the program using

./a.out


bubble.h
This file implements the class Bubble, which uses Circle from simplecpp graphics to represent the bubble in the game. The position of the bubble updates at every time step based on its velocity. I initialized the position and velocity of multiple bubbles. The bubble bounces against the two vertical borders of the window.

bullet.h
This file implements the class Bullet, which uses Rectangle from simplecpp graphics to represent the bullet in the game. The position of the bullet updates at every time step based on its velocity.

shooter.h
This file implements the class Shooter, which uses shapes from simplecpp graphics to represent the shooter in the game. In this case, we use a circle and a rectangle to represent the head and body of the shooter. Based on user input, the shooter can move left/right and also shoot bullets.

main.cpp
This file consists of the game simulation loop implemented using events.  use the following keys for user interaction

a: move shooter left
d: move shooter right
w: shoot 1 bullet
q: quit
The main function keeps track of the bullets and bubbles in the game using a vector.



