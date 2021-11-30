# About the game
Tic-tac-toe is a two-player game, that is played on a 3×3 square grid. Each player occupies a cell in turns, with the objective of placing three marks in a horizontal, vertical, or diagonal pattern. One player uses cross 'X' as his marker, while the other uses a naught

# Steps
# Step 1: Tic-tac-toe Design
If a player has to mark a particular box, he must enter the corresponding number shown in the grid. Suppose, we wish to occupy the center block, then we will input 5 in the terminal.

# Step 2: Store information using data structures
The core of any game is the game mechanics behind it. Since this is a fairly easy game to create, the mechanics involved are simple too.

At any instant of time, we need two crucial information:

Status of the grid – We must have a data structure that stores each cell’s state, that is, whether it is occupied or vacant.
Each player’s moves – We must somehow have the knowledge of each player’s past and present moves, that is, the positions occupied by 'X' and 'O'.

# Step 3: Game Loop
Every game, has some kind of game loop, which runs until some player wins or the game ends in a draw. In tic-tac-toe, each loop iteration refers to a single move any player makes.

# Step 4: Handle player input
We create a try block, in case a player enters some unintended value. Such an event must not stop the game, therefore, we handle the exception of ValueError and continue with our game.

# Step 5: Update information
According to the player input, we need to update the information for the smooth functioning of the game.
The values list updates the cell occupied according to the current player. The player position adds the position just taken by the current player.

# Step 6: Check win or draw
After each move, we have to check whether any player won the game or the game has been drawn.

# Step 7: Switch the current player
Since each player only moves once at a time, therefore after every successful move, we have to swap the current player.

# Step 8: Enter player names
It is mandatory for any scoreboard to display each player names.

# Step 9: Store game-related information
The information like the current player, the choice of players (take cross or naught), the available options (cross and naught), and the scoreboard need to be stored.

# Step 10: Design scoreboard
The scoreboard is stored as a dictionary, where keys are the player names and values are their win number.

# Step 11: Outer Game Loop
We need another game loop, for managing multiple matches of Tic-tac-toe. Each match, the current player chooses his mark ('X'or 'O')

# Step 12: Handle and Assign Player Choice
Each iteration, we have to handle and store current player’s choice.

# Step 13: Execute the match
After storing all the necessary information, it is time to execute an independent match and store the winning mark.

# Step 14: Update the scoreboard
We need to update the scoreboard after each match of Tic-tac-toe

# Step 15: Switch the choosing player
It is a generous idea, that each player must have the opportunity to choose which mark they want. To do so, we swap the value in cur_player

# Acknowledgements 
https://www.askpython.com/python/examples/tic-tac-toe-using-python
