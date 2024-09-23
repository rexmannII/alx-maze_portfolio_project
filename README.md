# The Maze Project

The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!

The Maze was written in C ussing SDL2 library. Deveploment was performed using Ubuntu 24.04 - gcc (Ubuntu 11.3.0-1ubuntu1~22.04) 11.3.0 as at the time of doing this project.

# About SDL2 

Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and lots more.

# Installation
You can install and set up the SDL2 which enables you develop the The Maze buy practicing and following simple guide lines the links provided below:
1. https://lazyfoo.net/tutorials/SDL/index.php

2. https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/misc/2021/1/9da3b82dc0bcfea07858b70956de47f0e2db2dad.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240917%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240917T153801Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=22e821e96fef59bdf6b94e371bca859bf6293e651fa85338a31e4e095525de03

3. https://permadi.com/1996/05/ray-casting-tutorial-table-of-contents/#google_vignette

4. https://lodev.org/cgtutor/raycasting.html

# How to USE: 
* Execute ./maze or type make run 
* Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
* Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)

# Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```

# Flowchart
![The Maze Flow Chart](https://i.imgur.com/t0MxNni.png)

# A Demo of the Concept
[![The Maze Demo](https://i.imgur.com/5Ss7s1S.png)](https://www.youtube.com/embed/6T2N8gNUTQ8)

# Author:

Rex Ejike Onyegbule <https://github.com/rexmannII>
