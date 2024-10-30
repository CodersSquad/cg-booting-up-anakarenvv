[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/swKMSSMl)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16850826&assignment_repo_type=AssignmentRepo)
# Computer Graphics Booting Up

## Let's start with ModernGL

This lab stands to prepare the moderngl development environment. Below the steps and requirements for initial coding tasks. Please make sure to edit the python provided files; for dependencies, you can add the files you need.

1. Install moderngl and its dependencies
2. Make sure that the following programs run
    - [`01_hello_world.py`](./01_hello_world.py)
    - [`06_multiple_objects.py`](./06_multiple_objects.py)
    - [`09_models_and_images.py`](./09_models_and_images.py)
        - _Modify this program to change the box's texture to a correctly aligned TEC logo_
3. Document how to execute the 3 programs in the section below.

* For documentation and missing dependencies, follow these links:
    - https://github.com/moderngl/moderngl
    - https://moderngl.readthedocs.io/

## How to run your program

```
# CG Booting Up - Anakarenvv

## Technologies Used

- **Python 3.12.2**
- **Pygame**: For creating the game window and handling user input.
- **ModernGL**: For rendering 3D graphics using OpenGL.
- **PyWavefront**: For loading OBJ files and their associated materials.
- **Pillow**: For handling image loading and manipulation.

## Project Structure
CG-BOOTING-UP-ANAKAREN │ ├── 01_hello_world.py ├── 06_multiple_objects.py ├── 09_models_and_images.py ├── auto.obj ├── logo.png ├── material.lib └── README.md


1. install the requirmente packages:
    pip install pygame moderngl pywavefront Pillow numpy glm

Note: Ensure that the OBJ files and texture images are in the same directory as the Python scripts.

- If you encounter any errors related to missing files, ensure that the paths to your OBJ files and texture images are correct.
- Make sure you have all the necessary dependencies installed.
- If the model appears incorrectly, check the OBJ file for any unsupported statements or materials.

You may take a look on:
https://docs.python.org/3/library/venv.html
```

## Grading Policy

- 25% - `01_hello_world.py` is running with no errors
- 25% - `06_multiple_objects.py` is running with no errors
- 25% - `09_models_and_images.py` is running with the requested change (TEC logo texture)
- 25% - Documentation on how to run your programs
