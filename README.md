# scenery

# OpenGL Graphics Project

## Overview
This project is an interactive OpenGL-based graphical application that allows users to draw and manipulate different shapes, such as trees, houses, clouds, birds, and boats. The project includes various drawing tools and a palette for selecting elements.

## Features
- **Drawing Tools**: Users can draw objects like trees, houses, clouds, birds, flowers, and more.
- **Palette Selection**: Click on an item in the palette to select a drawing mode.
- **Custom Brushes**: Grass, water, and eraser tools are available.
- **Mouse Interaction**: Left-click to draw objects, and use the rubber tool to erase them.
- **Full-Screen Mode**: The application runs in full-screen mode with a resolution of 1366x768.

## Technologies Used
- **OpenGL**: For rendering 2D graphics.
- **GLUT (OpenGL Utility Toolkit)**: Handles window creation and user interactions.
- **C/C++**: Programming language used for development.

## Installation
### Prerequisites
- Install OpenGL and GLUT on your system.
- Ensure you have a C++ compiler that supports OpenGL (such as MinGW for Windows).

### Compilation
To compile the project, use the following command:
```sh
 g++ project.cpp -o project -lglut -lGL -lGLU
```



## Controls
- **Left Click**: Select drawing tool or draw an object.
- **Mouse Drag**: Draw brush-based elements like grass and water.
- **Palette Click**: Choose an item from the palette to change the drawing mode.

## Future Improvements
- Implement a save feature for storing drawn images.
- Add more customization options for shapes and colors.
- Improve user interface for better interaction.

