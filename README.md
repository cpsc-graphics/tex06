# Tutorial Exercise 6

## Introduction

The main objective of this tutorial exercise is to explore how modern 3D graphics pipelines handle geometery and texture data, and various transformations (e.g. modeling, viewing and projection) that are needed to peform rendering operations efficiently on the GPU. 
The starter code for this exercise is provided in the [sfml-starter-with-opengl-3d](https://github.com/cpsc-graphics/sfml-starter-with-opengl-3d) repository.

## Student Exploration Exercises

There is **no missing code** for this exercise.

During the tutorial, your TA will cover key concepts related to the design of the starter repository. Please ensure you thoroughly understand how this pipeline operates.

Compilie and run the provided executables in the starter repo. Please ensure that you understand how the world coordinate system is setup for the two example programs. Perform the following exploration tasks.

1. **Change the camera:** In either the sphere or cube example, move the camera backwards and observe how the rendering changes. Ensure that the program is behaving as expected.
2. **Rotate about a different axis** Change the axis of rotation (for one of the examples); ensure that the result is as expected.
3. **Scale texture coordinates** Run the sphere example with the checkerboard texture. The directions of the checks follow the spherical parameterization used for the surface of the sphere. Scale the $u$ and $v$ texture coordinates uniformly by a factor of 2 or 3. Observe what happens to the rendering.
