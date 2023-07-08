# GoFish Card Game

### Overview

This project is an object-oriented C++ implementation of the GoFish card game. Further info can be found at: 
https://en.wikipedia.org/wiki/Go_Fish

# How to launch the game

### Prerequisites

In order to compile and run the game, you need to install g++-12 along with CMake. The program is designed for compiling using C++20. 

If you work on linux, in order to install g++-12 and cmake, run following commands:

```
sudo apt-get update
sudo apt-get install g++-12
sudo apt-get install cmake
```

Make sure to set g++-12 as your default g++ version, using:

```
sudo update-alternatives --install /usr/bin/g++ g++ /usr/bin/g++-12 100
```

### Compilation

Next go to the project directory, create build directory, and build the project using following commands:

```
cd Gofish
mkdir build
cd build
cmake ..
make
```

You can launch the created program using

```
./GoFish
```