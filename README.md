<center><h1>My first RayCaster with miniLibX</h1></center>

This project demonstrates ray casting using C programming language with the Minilibx library. Ray casting is a technique used in computer graphics for rendering 3D scenes by simulating the path of light rays.

## Overview

This repository contains a ray casting implementation in C using the Minilibx library. It showcases basic demos and examples to illustrate the ray casting concept.

![Ray Casting Demo](https://upload.wikimedia.org/wikipedia/commons/e/e7/Simple_raycasting_with_fisheye_correction.gif)


## Prerequisites

Before running the project, ensure you have the following:
- **C Compiler**: Install a C compiler such as GCC.
- **Minilibx Library**: Install and configure the Minilibx library. (Provide installation instructions or link to resources for Minilibx setup if needed.)
- **header file** :
-       `# include "/nfs/homes/arahmoun/Downloads/minilibx-linux/mlx.h"`  (path where your minilibx location)
-       `# include "/nfs/homes/arahmoun/Downloads/minilibx-linux/mlx_int.h"` (path where your minilibx location)

## Usagegit clone https://github.com/rahmoun03/cub_3

To use this project:
1. **Clone the Repository**: `git clone https://github.com/rahmoun03/cub_3d`
2. **Build the Project**: `cd cub_3d` and `make` 
3. **Run the Demos**: Execute the Cub3d program to see ray casting in action.

Example commands:
```bash
make            # Compile the project
./Cub3d maps/pro.cub
./Cub3d maps/flech.cub

