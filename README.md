# Opengl C++ template
This repo contains a template workspace to bootstrap your OpenGL projects

## How to run this project

To run this template you should have installed the g++ C++ compiler

1. Clone this repo
3. Open a terminal in this repo
5. Compile with `g++ -I ./include -L ./lib ./src/main.cpp ./src/glad.c -lglfw3dll -o main.exe`
4. Run with `./main.exe`

## Made this by yourself

1. Download GLFW pre-compiled binaries from [here](https://www.glfw.org/download.html)
2. Download GLAD from [here](https://glad.dav1d.de/). Make sure to select the following options: Language: C/C++, Specification: OpenGL, API (gl): Version 3.3, Profile: Core. Then press "Generate" and download the file glad.zip.
3. Create a folder for your workspace
4. Copy files that you just dowloaded in your workspace following the structure of this repo. Note: copy only the files relative to your system
5. Create a file main.cpp in ./src folder and write your OpenGL code. This repo contains a sample code from [learnopengl.com](https://learnopengl.com)
