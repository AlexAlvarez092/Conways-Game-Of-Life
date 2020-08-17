# Conways-Game-Of-Life (Python implementation)
Conways’s Game Of Life is a Cellular Automation Method created by John Conway. This game was created with Biology in mind but has been applied in various fields such as Graphics, terrain generation,etc..

![screenshot](https://media.geeksforgeeks.org/wp-content/uploads/life_game.gif)

## How the game works
Because the Game of Life is built on a grid of nine squares, every cell has eight neighboring cells,as shown in the given figure. A given cell (i, j) in the simulation is accessed on a grid [i][j], where i and j are the row and column indices, respectively. The value of a given cell at a given instant of time depends on the state of its neighbors at the previous time step. Conway’s Game of Life has four rules.

1. If a cell is ON and has fewer than two neighbors that are ON, it turns OFF
2. If a cell is ON and has either two or three neighbors that are ON, it remains ON.
3. If a cell is ON and has more than three neighbors that are ON, it turns OFF.
4. If a cell is OFF and has exactly three neighbors that are ON, it turns ON.

So since we know how it works, the next thing we need to figure it out that how to make it work.

## Approach
1. Initialize the cells in the grid.
2. At each time step in the simulation, for each cell (i, j) in the grid, do the following:
  a. Update the value of cell (i, j) based on its neighbors, taking into account the boundary conditions.
  b. Update the display of grid values.
  
After we done here lets get our hands on code.
  
## Requirements
1. **numpy:** For 2D array (matrix) manipulation.
2. **matplotlib^:** For update the simulation or in easy words to make stuffs move.
3. **argparse:** To pass command line arguments in the code

## How to execute
`python 'filename.py' --grid-size 32 --interval 500 --glider`

## Reference links
1. Book *Python Playground: Geeky Projects for the Curious Programmer*
2. [docs-numpy](https://docs.scipy.org/doc/numpy-dev/user/quickstart.html)
3. [docs-matplotlib](https://matplotlib.org/users/pyplot_tutorial.html)
