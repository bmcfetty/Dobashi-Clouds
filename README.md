My final project for COMP308 Computer Graphics at Victoria University.

It is an implementation of the paper "A Simple, Efficient Method for Realistic Animation of Clouds" by Yoshinori Dobashi, Kazufumi Kaneda, Hideo Yamashita, Tsuyoshi Okita, and Tomoyuki Nishita. A link to the paper can be found here: http://evasion.imag.fr/~Antoine.Bouthors/research/dea/sig00_cloud.pdf

It requires OpenGL and glut to compile.

So far only sections 4.1 Growth Simultation, 4.2 Cloud Extinction, 4.5 Controlling Cloud Motion Using Ellipsoids have been implemented. With 4.4 Fast Simulation Using Bit Field Manipulation Functions partially implemented.

There are controls implemented:
	p pauses the animation
	r resets and starts the animation with new random values
	1 toggles the bounding box for the simulation
	2 toggles the ellipsoids which control the position of cloud growth and extinction
