# 3D Scene Visualization Project

## Reflection and Insights

### Design Approach
My approach to designing software focuses on modularity and clarity. During this project, I prioritized creating a clean structure that separated different aspects of the 3D scene—such as object management, lighting, and camera controls—into distinct modules. This helped ensure that the code was both manageable and scalable. Working on this project honed my skills in scene organization and shader management, skills which I plan to carry into future projects.

### Development Process
I adopted an iterative development process, regularly testing small chunks of code to ensure each part worked correctly before moving on. This strategy helped me quickly identify and resolve issues. Throughout the milestones, I developed a deeper understanding of OpenGL’s intricacies, particularly in terms of how different components interact within a 3D space. The process also reinforced the importance of detailed planning and incremental progress in software development.

### Application of Skills
The knowledge and skills I gained from working on computational graphics and visualizations are invaluable for both my educational and professional pathways. Understanding the fundamentals of 3D rendering, lighting models, and texture mapping has broadened my technical capabilities and opened up new avenues for creating visually rich applications. These skills are directly applicable to roles in game development, simulation design, and any field that benefits from immersive visualizations.

## Overview

This repository contains the code for a 3D scene visualization project developed using C++ and OpenGL. The project replicates a real-world scene using low-polygon 3D models, accurately projected textures, and custom lighting. It includes camera navigation controls for an interactive experience. The project was created as part of the CS 330 - Computational Graphics and Visualization course.

## Features

- **3D Objects:** Includes low-polygon representations of real-world objects using basic shapes like cylinders, spheres, and planes.
- **Texturing:** Applied high-resolution, royalty-free textures to the objects to enhance realism.
- **Lighting:** Implemented multiple light sources with ambient, diffuse, and specular components using the Phong shading model.
- **Camera Navigation:** Provides horizontal, vertical, and depth navigation using keyboard and mouse controls, with the ability to switch between perspective and orthographic views.

## Requirements

To run this project, you will need the following:

- C++ Compiler (GCC, Clang, or MSVC)
- OpenGL 3.3 or higher
- GLFW
- GLM (OpenGL Mathematics)
- stb_image library for texture loading


## Usage

- **Navigation:**
  - `WASD`: Move forward, backward, left, and right.
  - `QE`: Move up and down.
  - `Mouse`: Change the orientation of the camera.
  - `Scroll Wheel`: Adjust the camera movement speed.
  - `1`: Front orthographic view.
  - `2`: Side orthographic view.
  - `3`: Top orthographic view.
  - `4`: Perspective view.

- **Interaction:**
  - The scene can be explored by moving the camera around the objects using the controls described above.
  - Lighting dynamically affects the objects based on the camera's position and movement.

## Project Structure

- **src/**: Contains the source code for the project.
  - `main.cpp`: Entry point for the application.
  - `SceneManager.cpp`: Manages the preparation and rendering of the 3D scene.
  - `ShaderManager.cpp`: Handles shader programs and their application to objects.
- **textures/**: Contains texture images used in the project.
- **shaders/**: Contains vertex and fragment shader programs.

## References

- OpenGL Documentation: [https://www.opengl.org/documentation/](https://www.opengl.org/documentation/)
- GLFW Library: [https://www.glfw.org/](https://www.glfw.org/)
- GLM Library: [https://glm.g-truc.net/0.9.9/index.html](https://glm.g-truc.net/0.9.9/index.html)
- stb_image Library: [https://github.com/nothings/stb](https://github.com/nothings/stb)

