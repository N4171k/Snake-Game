# Console Snake Game

This is a simple console-based Snake game implemented in C++. The game features basic functionality where the player controls the snake to eat fruit, which increases the snake's length and the player's score. The game ends if the snake collides with the walls or itself.

## Features

- Console-based interface
- Randomly spawned fruit
- Growing snake tail
- Score tracking
- Game over on collision with walls or self

## Getting Started

### Prerequisites

- A C++ compiler (e.g., GCC, MinGW)
- Windows OS (due to usage of conio.h and windows.h libraries)

### Compilation

To compile the game, you can use a C++ compiler. Here is an example using `g++`:

```sh
g++ -o snake_game snake_game.cpp
