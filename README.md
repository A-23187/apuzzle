# apuzzle
An n-puzzle game written in bash
 
## Installation
 ```bash
 curl -s https://raw.githubusercontent.com/A-23187/apuzzle/master/apuzzle -o apuzzle && chmod +x apuzzle
 ```
  
## Usage
  ```bash
  ./apuzzle
  ```

  If you want to skip the level prompt, you can run it with the `-l` option.
  ```bash
  ./apuzzle -l n # n is positive and not greater than 9
  ```

  You can specify the keys used to move the tile with the `-k` option in left-down-up-right order. And in any case, it's always possible to move the tile via the 4 arrow keys
  ```bash
  ./apuzzle -k hjkl # vim-style keys
  ```

  When you have successfully resolved a puzzle, you will see `Good!`. Then you can now press `n` to enter the next puzzle, press `m` to enter the menu, and press `e` to exit the game.

## Reference
[Solvability of the Tiles Game](https://www.cs.bham.ac.uk/~mdr/teaching/modules04/java2/TilesSolvability.html)

