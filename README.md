# Forward-Kinematics-equations

Given:

•	L1 : Length of the first link (from the base to the first joint)

•	L2 : Length of the second link (from the first joint to the second joint)

•	θ1: Angle of the first link with the horizontal axis

•	θ2: Angle of the second link relative to the first link

Forward Kinematics Equations:

1.	Coordinates x and y of the end-effector:
   
x=L1⋅cos(θ1)+L2⋅cos(θ1+θ2)

y=L1⋅sin(θ1)+L2⋅sin(θ1+θ2)


Explanation of the Equations:

•	X and y are the coordinates of the position where the robotic arm will reach.

•	θ1  and θ2 are the angles of each link relative to the horizontal axis.

•	L1 and L2 are the lengths of the connected parts.

