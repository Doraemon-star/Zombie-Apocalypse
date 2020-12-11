# Zombie-Apocalypse
In this simulation, the positions of the zombies and humans will be restricted to a grid.
Zombie can only move up, down, left, or right
Humans can move in 8 directions.
 If zombie catches human, the zombie enjoys some delicious brains, but human continues to live.
Apocalpse class : encapsulates the core mechanisms of this simulation and that interacts with a GUI.
It is a sub-calss of the Grid class and inherits the Grid clas methods
  Passable cells --- EMPTY, impassable cells --- FULL
   Include 2 lists, one for zombies and one for humans.
    each list entry is cell indices of the form (row, col)
