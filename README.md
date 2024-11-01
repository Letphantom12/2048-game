2048 game using the Tkinter library for the graphical user interface.

The game initializes with two tiles (usually 2s).
Players can move tiles using arrow keys:
Tiles compress and merge according to 2048 rules.
If a player creates a tile with the value 2048, a win message is displayed.
The game ends when there are no valid moves left.
The game updates the display and score after each move.

Contains methods to handle the game logic, including:
reverse(): Reverses the rows of the grid.
transpose(): Transposes the grid (flips rows and columns).
compressGrid(): Moves non-zero tiles to the left, filling gaps.
mergeGrid(): Merges adjacent tiles of the same value.
random_cell(): Places a new tile (2) in a random empty cell.
can_merge(): Checks if any tiles can be merged.
paintGrid(): Updates the display based on the current grid state.
