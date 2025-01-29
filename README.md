# Robot-Walking-Simulator-main

## Robot-Walking-Simulator-main
This C program uses OpenGL (GLUT) to create a 3D robot walking simulation. Below is a simplified explanation of the key components:

Preprocessor Directives & Definitions

The #define statements enable various features like SPHERE, COLOR, LIGHT, etc.
Defines constants for robot parts, like torso, hip, arms, legs, etc.
OpenGL & GLUT Libraries

Uses GLUT (OpenGL Utility Toolkit) to create and manage the graphical display.
Includes GLUquadricObj *qobj for handling 3D quadric shapes.
3D Robot Model

The robot is constructed using display lists, defining body parts like:
Torso
Hip
Shoulders
Arms & Legs
Feet & Rocket Pod
Uses functions to render geometric shapes (boxes, octagons, cylinders, and spheres).
Motion Variables & Animations

Defines angles for various joints to animate movement.
Functions like RaiseLeg1Forward() and Elbow1Add() control limb movement.
animation_walk() function moves legs in a walking motion.
Lighting & Materials

Uses GL_LIGHTING to add illumination.
Different materials & colors are applied to parts like the torso, hip, and arms.
Keyboard & Mouse Controls

keyboard() function maps keys to robot movement.
Uses arrow keys to rotate the scene and letter keys to move arms, legs, and torso.
GLUT Menu

Right-click opens a menu to:
Start/stop walking animation.
Toggle wireframe mode.
Move different robot parts.
Main Function (main())

Initializes GLUT window (size: 1000x1000).
Registers display, reshape, keyboard, and menu functions.
Runs glutMainLoop() to keep rendering the simulation.
Summary
This program renders a 3D robot that can walk and move its limbs using OpenGL and GLUT. It includes lighting, animations, and interactive controls to simulate realistic movement. 🚀🤖
