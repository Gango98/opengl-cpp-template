# Opengl C++ template
This repo contains a template workspace to bootstrap your OpenGL projects

## How to run this project

To run this template you should have installed the g++ C++ compiler

Basic setup:

1. Clone this repo
2. Open a terminal in this repo
3. Compile with `g++ -I ./include -L ./lib ./src/main.cpp ./src/glad.c -lglfw3dll -o main.exe`
4. Run with `./main.exe`

With GLM:

1. The compile command doesn't change

With Dear ImGui:

1. Add `./include/imgui/*.cpp` to the command. Compile with `g++ -I ./include -L ./lib ./src/main.cpp ./src/glad.c ./include/imgui/*.cpp -lglfw3dll -o main.exe`

## Made this by yourself

Basic setup:

1. Download GLFW pre-compiled binaries from [here](https://www.glfw.org/download.html)
2. Download GLAD from [here](https://glad.dav1d.de/). Make sure to select the following options: Language: C/C++, Specification: OpenGL, API (gl): Version 3.3, Profile: Core. Then press "Generate" and download the file glad.zip.
3. Create a folder for your workspace
4. Copy files that you just dowloaded in your workspace following the structure of this repo. Note: copy only the files relative to your system
5. Create a file main.cpp in ./src folder and write your OpenGL code. This repo contains a sample code from [learnopengl.com](https://learnopengl.com)

Add GLM:

1. Download GLM from [here](https://glm.g-truc.net/0.9.8/index.html). Press "Downloads", select the latest version and download lathe zip file
2. Add glm folder in the ./include folder

Add Dear ImGui:

1. Follow instructions [here](https://github.com/ocornut/imgui)
