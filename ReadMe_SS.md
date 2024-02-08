# Asteroids Project

## Overview

This project is a simple implementation of an asteroids game/simulation, where the player controls a ship navigating through space, avoiding asteroids. The project is structured into main components: the game logic (`asteroids.c`), ship movement mechanics (`move_ship.c`), and shared definitions (`asteroids.h`).

## Getting Started

### Prerequisites

To compile and run this project, you will need a C compiler (such as `gcc`) and standard development tools (`make`, etc.) installed on your system.

### Compilation

To compile the project, you can use the following command in the terminal from the project directory:

Copy code

`gcc -o asteroids asteroids.c move_ship.c -lSomeLibrary` 

Note: Replace `-lSomeLibrary` with any specific libraries your project depends on, such as graphical libraries if applicable.

### Running the Game

After compilation, you can run the game using:

bashCopy code

`./asteroids` 

## Project Structure

-   `asteroids.c`: Contains the main game loop, asteroid handling, and collision detection.
-   `move_ship.c`: Manages the ship's movement, including acceleration and rotation.
-   `asteroids.h`: Includes definitions and global variables shared between different parts of the project.

## Contributing

Contributions to the project are welcome. Please feel free to fork the repository, make your changes, and submit a pull request.

