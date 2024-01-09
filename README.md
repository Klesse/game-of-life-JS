# 🌲🌻 Conway's Game of Life - Javascript and p5

This code reproduces the conway's game of life with javascript and the graphic library p5.js.

## The game

The game consists in individuals and generations. In this version, each individual (live cell) is a black rectangle and 
the white ones are dead cells. Each frame of the game represents the generations, that consists 
in individuals spread in the grid.

At each generation the game changes by some defined rules, and the next one is shown, and so on for each 
generation (frame).

More details about this game can be seen [here](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life).

## Rules

1. Any live cell with fewer than two live neighbours dies, as if by underpopulation.
2. Any live cell with two or three live neighbours lives on to the next generation.
3. Any live cell with more than three live neighbours dies, as if by overpopulation.
4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction. 

## Author

[Pedro Malandrin Klesse](https:/www.github.com/Klesse)
