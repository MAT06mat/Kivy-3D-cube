# Kivy-3D-cube

Example of 3D cube with Kivy in Python.

## Description

This project demonstrates how to create a 3D cube using the Kivy framework in Python. Kivy is an open-source Python library for developing multitouch applications. This example showcases basic 3D rendering and interaction without using OpenGL or shaders.

## Requirements

- Python 3.x
- Kivy

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/Kivy-3D-cube.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Kivy-3D-cube
    ```
3. Install the required dependencies:
    ```sh
    pip install kivy
    ```

## Usage

Run the `main.py` file to start the application:
```sh
python main.py
```

## main.py

The `main.py` file contains the code to create and display a 3D cube using Kivy. Below is a brief overview of the main components:

- **FaceColors Class**: Defines the colors for each face of the cube using notation (U, R, F, D, L, B).
- **CubeWidget Class**: Handles the 3D cube's properties and rendering.
  - **angle**: ListProperty to store the rotation angles of the cube.
  - **scale**: NumericProperty to store the scale of the cube.
  - **rotate_on_x, rotate_on_y**: BooleanProperties to control rotation on the x and y axes.
  - **on_touch_down, on_touch_move, on_touch_up**: Methods to handle mouse interactions for rotating the cube.
  - **update**: Method to update the cube's rotation and redraw it.

## License

This project is licensed under the MIT License.
