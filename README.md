Overview
This project is a 2D version of the popular game Clash of Clans, implemented in Python3 using Object-Oriented Programming (OOP) concepts. The game allows players to build and upgrade their own villages, train armies, and engage in battles with other players.

Features

hurt.py
- This file defines classes for different types of huts in the game.

- Hut class: Represents a general hut with attributes like x and y coordinates and health.

- Th class (inherits from Hut): Represents a special type of hut.

- Can class (inherits from Hut): Represents another special type of hut with an additional damage attribute.

input.py
- This file contains classes and functions for handling user input.

- Get class: A callable class to get a single character of input from the user.

- AlarmException class: A custom exception class for handling timeouts during input.

= alarmHandler function: A function to handle timeouts during input.

- input_to function: Takes user input with a specified timeout.

king.py
- This file defines a class for the King character in the game.

- King class: Represents the player's character with attributes like x and y coordinates, health, damage, and speed.

game.py
- This is the main game file that brings everything together.

- Imports: Import necessary classes and modules.

- Constants: Define constants like the size of the game grid.

- Initialization: Create instances of classes and set up the initial game state.

- Troop class: Represents a troop with attributes for position, health, damage, and speed.

- attack function: Handles attacks on various game entities based on their positions and health.

- defense function: Handles defensive actions based on the position of the player's character and other entities.

- distance function: Calculates the distance between two points.

- Main game loop: Continuously takes input from the user and updates the game state accordingly. It also handles win/lose conditions and prints the game grid with various entities.

Requirements
Python 3.x


How to Run

1. Clone this Repository:
```
git clone https://github.com/Nirmalakadali/clashofclans.git
cd clashofclans
```

2.Run the game :
```Python3 game.py```