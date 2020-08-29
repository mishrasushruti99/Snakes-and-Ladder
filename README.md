# CPPND: Capstone Snake Game

This is an extended verion of the starter repo for the Capstone project. I have added the following features:
* Ability to pause/resume the game.
* Random obstacles with the ability to change every time a player eats the food.
* A GUI to let the player know how to start, resume and pause the game.

<img src="snake_game_new.gif"/>

In this project, I build my own C++ application or extend this Snake game, following the principles of OOPS in c++.

## Dependencies for Running Locally
* cmake >= 3.7
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* SDL2 >= 2.0
  * All installation instructions can be found [here](https://wiki.libsdl.org/Installation)
  * Note that for Linux, an `apt` or `apt-get` installation is preferred to building from source.
* SDL_ttf >= 2.0
  * All installation instructions can be found [here](https://www.libsdl.org/projects/SDL_ttf/)
  * Not that for Linux, using `sudo apt-get install libsdl2-ttf-dev` for installation is preferred to building from source.
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./SnakeGame`.

## Meets Rubric

1. The project demonstrates an understanding of C++ functions and control structures.
2. The project uses Object Oriented Programming techniques.
3. Classes use appropriate access specifiers for class members.
4. Class constructors utilize member initialization lists.
5. Classes abstract implementation details from their interfaces.
6. Classes encapsulate behavior.
7. The project makes use of references in function declarations.
