# E05b-Physics
Exploring 2D physics and collisions.

In *main1.py*, we spawn 20 balls on the screen in random positions. Then we will apply gravity to them, finally having them rest at the bottom of the scene.

In *main2.py*, we spawn 20 balls again and apply gravity to them. Now we have made them able to bounce, by simply flipping it's dy components when it collides with the ground. The application of friction will make sure they don't bounce infintely.

*main3.py* implements the worst, most-naive version of collision physics using the built-in sprite collision detection. Assuming all the animal heads have the same mass, lines 51-60 exchange the velocities in a very naive simple way. This is explained better in comments on
lines 52-55.

