CS452-LAB6
==========
Jeffrey Kopra

For this lab the important factor that is different from all the other labs is creating a light so that when pointed at a object, casts a shadow.  In order to do this effect we must follow the following steps:
	- use glLight() to create a light object
	- create material properties for the light to effect as well as provide normals
	- position the lighting to highlight the object
	- next we must come up with a target and MVP matrix for the shadow map
	- set up a texture to portray the depth from the point of view of the lights
	- manipulate the MVP matrix to follow the light's point of view and send to shader
	- finally render the scene from the camera's point of view