# Road Rush Game for Micro:bit

## Overview

The **Road Rush** game is a simple game developed for the BBC micro:bit platform. The objective is to control a car on a road by avoiding obstacles. The player uses the micro:bit buttons to move the car left or right to avoid incoming obstacles.

This game demonstrates basic interaction with the micro:bit's LED matrix, buttons, and timing functions.

## Features

- **Button A**: Moves the car to the left.
- **Button B**: Moves the car to the right.
- **LED Matrix**: Displays the player's car and the incoming obstacles.
- **Game Logic**: The game ends when the car collides with an obstacle.
- **Score**: Tracks the number of successful obstacles avoided.

## Prerequisites

- BBC micro:bit device
- [Micro:bit Editor](https://makecode.microbit.org/) or similar IDE for writing code

## Installation

1. Go to the [MakeCode Editor](https://makecode.microbit.org/) or open your preferred development environment for the micro:bit.
2. Copy and paste the provided code into the editor.
3. Save the file as a `.hex` file.
4. Connect your micro:bit to your computer via USB.
5. Drag and drop the `.hex` file onto the micro:bit's storage device.
6. The game should now be ready to play on your micro:bit!

## Game Instructions

1. Press **Button A** to move the car left.
2. Press **Button B** to move the car right.
3. Avoid the obstacles coming down the road.
4. The game ends if the car collides with an obstacle.
5. A simple score is displayed after the game ends.

## Code Description

The game uses the micro:bit's LED matrix to display the road and obstacles. The player's car is represented by a lit LED at the bottom of the screen, while obstacles come down from the top. The game runs in an infinite loop, checking for button presses to move the car and for collisions with obstacles.

## Contributing

Feel free to fork this repository, submit issues, and propose changes via pull requests. If you have any suggestions or improvements, don't hesitate to contribute!


## Acknowledgments

- Thanks to the micro:bit team for providing an excellent platform for educational games and projects.
- Special thanks to the community for their inspiration and support.
