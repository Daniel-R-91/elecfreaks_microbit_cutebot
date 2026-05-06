Elecfreaks Microbit Cutebot code

Please see main file for the code.

Please note that this code was done in Microsoft Make code for the Smart Cutebot specifically and is just to demonstrate how to create a code for a right-wall hugging maze solving logic for this specific robot model.

When the robot is placed in a maze and turned on, it starts to move forward. As soon as it detects a wall in front of it, it turns right to check if there is another wall there. If not, it continues forward and applies the same logic. If there was a wall to the right as well, it would turn 180 degrees to check the other side, then if there is a wall there too it would turn back to its original starting position.

This is basically a simple right wall hugging maze solving logic for robots: 

Go forward as long as you can
If you hit a wall → turn right
If you can’t go forward but right is blocked → turn left until you can move forward
Always prefer turning right when there’s a choice
