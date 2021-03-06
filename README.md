## A simulation of the assignment using Javascript



#### Better viewed in Desktop site..


## It is an infinite, two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, live or dead. Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:

### Any live cell with fewer than two live neighbors dies, as if by loneliness.
### Any live cell with more than three live neighbors dies, as if by overcrowding.
### Any live cell with two or three live neighbors lives, unchanged, to the next generation.
### Any dead cell with exactly three live neighbors comes to life.


The initial pattern constitutes the seed of the system. The first generation is created by applying the above rules simultaneously to every cell in the seed; births and deaths occur simultaneously, and the discrete moment at which this happens is sometimes called a tick. Each generation is a pure function of the preceding one. The rules continue to be applied repeatedly to create further generations.