# Rubik's Cube 3D Simulation

The Rubik's Cube is a classic puzzle game that has captivated people for decades. In this project, we present a 3D simulation of the Rubik's Cube using various computer graphics techniques. Our goal was to create an interactive and visually appealing simulation that accurately represents the mechanics of the Rubik's Cube.

## Introduction

The Rubik's Cube simulation allows users to manipulate the cube's faces to solve the puzzle. We utilized programming languages such as C++, and graphics libraries like OpenGL and GLSL to develop the simulation.We also implemented several algorithms for cube manipulation, such as the basic layer-by-layer method. The project aims to offer a digital alternative to the physical Rubik's Cube, providing advantages such as ease of manipulation and infinite variations.

## Computer Graphics Concepts Used

### 1. 3D Modeling
We modeled the Rubik's Cube as a 3D object composed of smaller cubes, each representing a face of the cube.

### 2. Transformations
Various transformations such as translation, rotation, and scaling were used to manipulate the Rubik's Cube in 3D space.

### 3. Animation
Animation techniques were employed to create dynamic effects, such as rotating the cube's faces and controlling the windmill blades.

### 4. User Interaction
User interaction was implemented to allow users to control the simulation, including rotating faces, changing rotation speed, and solving the cube automatically.

### 5. Texturing
Texturing techniques were used to apply colors to the individual cubes of the Rubik's Cube, creating a realistic representation of its color scheme.

## User Defined Functions

1. `output(int x, int y, const char* string)`: Display text on the screen using bitmap fonts.
2. `polygon(int a, int b, int c, int d, int e)`: Draw a polygon with a line loop and a filled polygon.
3. `colorcube1()`, `colorcube2()`, ..., `colorcube27()`: Draw individual cubes that make up the Rubik's cube.
4. `speedmeter()`: Draw a speed meter to control the rotation speed.
5. `transpose(char a)`: Transpose the values of arrays based on the input character.
6. `topc()`, `frontc()`, `rightc()`, `leftc()`, `backc()`, `bottomc()`: Update arrays after a rotation of the corresponding face.
7. `spincube()`: Idle callback function to rotate the Rubik's cube.
8. `motion(int x, int y)`: Handle mouse motion events and rotate the cube.
9. `mouse(int btn, int state, int x, int y)`: Handle mouse button events and store initial mouse coordinates.
10. `keyboard(unsigned char key, int x, int y)`: Handle keyboard events for rotating faces, changing rotation speed, and solving the cube.
11. `myreshape(int w, int h)`: Reshape callback function to set up the viewport and projection matrix.
12. `mymenu(int id)`: Menu callback function to handle menu events and perform corresponding actions.

## Code File

You can find the code file for this project [here](rubik's_cube/rubik's_cube/Code.cpp).

## Future Potential

1. Incorporating machine learning algorithms to generate new and challenging Rubik's Cube configurations.
2. Adding multiplayer functionality to allow users to compete against each other.
3. Configuring the program to solve the cube automatically.
