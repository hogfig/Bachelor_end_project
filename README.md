# Bachelor end project

## Računalni vid u funkciji upravljanja robotskim sustavom ##
## Eng. Vision guided robotic system ##

Used harware:
* MeArm robotic arm
* Arduino board
* Logitech HD C270 camera
* Power suply

The robotic arm used in this project was a MeArm with 4 servo motors and 3 degrees of freedom. The matematical model of the arm is calculated and used to perform inverse kinematics. The object detection is implemented with a simple algorithm that finds red objects. Knowing the position of the camera relative to the ground, and the fact that the object and the robotic arm are both situated on the ground, it's posible to calculate the position and the angle of the object relative to the robotic arm. With the known position and the angle of the object, using inverse kinematics the object is fetched.

The code used in the project can be found in the final pages of the PDF document.
