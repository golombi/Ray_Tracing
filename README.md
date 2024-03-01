# Ray_Tracing
A C++ OpenGL Rendering Software for a 3D scene descripted in an input text file. It supports Spheres, Planes, Spot/Directional Light Sources, Camera Location, Reflective and Transparent Objects, Phong Reflection and Shadowing.

Project link:
https://github.com/neta-segal/BasicEngine2

This project is an implementation by Neta Segal and I for the second assignment in the course "Computer Graphics". 
We completed the project in just 3 days and studies the material as we went, in a fruitful and agile collaboration.

I derived the needed formulas for calculating the intersection point of a light ray passing from the camera through each pixel on the screen with a sphere or plane and wrote the subsequent code.
I also implemented the Phong Model with directional light, Reflection as a recursive call, Transparency as light refraction using Snell's law (A transparent sphere has two refraction points with each ray passing through and a plane has one).

She implemented Shadowing and The Phong Model for spotlights.

We also helped each other face challenges as expected.

Note: The Phong Reflection Model takes into account Ambient light along with the contribution of color of each light source in a way that's dependent of the location of the camera and the angle between the ray and the normal to the object at that point (Diffuse and Specular components).
