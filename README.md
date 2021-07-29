# Game if coditation
Imagine an infinite two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, live or dead. Every cell interacts with its eight neighbors, which are the cells that are directly horizontally, vertically, or diagonally adjacent.
At each step in time (tick), the following transitions occur:
Rule:
# Any live cell with fewer than two live neighbors dies, as if by loneliness.
# Any live cell with more than three live neighbors dies, as if by overcrowding.
# Any live cell with two or three live neighbors lives, unchanged, to the next generation.
# Any dead cell with exactly three live neighbors comes to life.
