# Stellar Journey Project
 Stellar Journey is a game i coded using python. This project was my final exam for the Fundamentals of Programming course i have done at the Faculty of Mathematics and Computer Science of Babes-Bolyai University.

In this Stellar Journey game, the player controls the USS Endeavour spaceship and has the goal of eliminating all Blingon ships from a sector of the galaxy. The game is played in a number of turns, as described by the following rules:
1. When the game is started, display the sector of the galaxy according to the following rules:
   a. The game takes place on a 8x8 grid, having marked rows (1-8) and columns (A-H)
   b. 10 stars are randomly placed in the sector.
   c. The player's ship, the USS Endeavor, starts in a random square of the grid that has no stars. The ship is represented as ### E ###.
   d. Three Blingon ships are placed randomly on empty squares of the grid. They must not overlap each other, the player's ship or a star. The player can only see the ships that are adjacent to the Endeavor.

2. The game is played in a number of turns. Each turn, the player can give one of the following commands:
   a. ## warp <coordinate> (e.g. warp G5) ##. This command moves the ship to the new coordinate. The new coordinate must be on the same column, row or diagonal as the starting position. In case a star is in the way, you can't warp to that position. In case ## Endeavor ## would land on an enemy ship, the Endeavor is destroyed and the game is over.
   b. ## fire <coordinate> ##. Destroy the Blingon ship at the given coordinates. The ##fire## command only works for ships adjacent to the player's ship.
   c. ##cheat##. This displays the playing grid, with remaining Blingon ships revealed.

3. Every time a Blingon ship is destroyed, the remaining ones reposition randomly on the grid.
4. The player wins by destroying all enemy ships.

# How to run
Simply run the start.py file and follow the instructions.
