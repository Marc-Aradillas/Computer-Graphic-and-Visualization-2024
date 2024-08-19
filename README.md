# Computer-Graphic-and-Visualization-2024
CS-330 Computer graphics and visualizations course taught by Professor Phillip Enkema. The course provided a deep understanding of the use of OpenGL and best practices used in the industry, The repository is for a final project simulating a project task for a client.


# 3D Scene Visualization Project

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

## Setup and Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/3d-scene-visualization.git
    cd 3d-scene-visualization
    ```

2. **Build the project:**

    Use your preferred C++ compiler or IDE to compile the project. Ensure that all dependencies (GLFW, GLM, stb_image) are correctly linked.

    Example using g++:

    ```bash
    g++ -o 3dscene main.cpp SceneManager.cpp ShaderManager.cpp -lGL -lGLU -lglfw
    ```

3. **Run the executable:**

    ```bash
    ./3dscene
    ```

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

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with any improvements, bug fixes, or new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

