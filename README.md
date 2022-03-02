# Multithreaded Advection Calculations
 Multithreaded program to simulate the movement of a cloud of material in the atmospheric boundary layer
 
 The wind in the Atmospheric Boundary Layer can be approximated as a horizontal velocity
which depends only on height (z) and zero vertical velocity. The horizontal velocity as a function
of height vx(z) can be represented by a logarithmic profile

![Capture](https://user-images.githubusercontent.com/61834317/156339787-1997b82b-550b-4be8-80d4-d70335e76bca.PNG)

where u* is a parameter called the “friction velocity”, z0 is a parameter called the “roughness
length”, and  = 0.41 is a constant called Von Karman’s constant.

![initial](https://user-images.githubusercontent.com/61834317/156339365-61764dab-9bb0-4c15-9996-3f4f6b992b2e.png)
![final 22](https://user-images.githubusercontent.com/61834317/156339387-85834f45-3247-4d4d-8d44-863c895bd56f.png)
![final 23](https://user-images.githubusercontent.com/61834317/156339396-39cb7aa0-c5c6-40d5-8d4a-ebe01e6a1b6f.png)
![average](https://user-images.githubusercontent.com/61834317/156339404-002b5bdf-b962-44e8-9cfd-9751b0c08ad3.png)
