Components of the Game
A square board with a series of numbered squares arranged in m x m grid.
A dice to be rolled usually uses a six-faced die.
Each player uses different color tokens in order to represent them.
Rules of the Game
Players take turns rolling the die and move their token forward by the number that appears on the top of the die. For example, if a player rolls a 3, they move three squares forward.
If a player lands on a square with the base of a ladder, then they must climb the ladder to the square which is at the top of the ladder.
If a player lands on the square in which there is a mouth of a snake then the player must slide down to the square which is at the snake’s tail.
Players take the turn clockwise and the game terminates until one player reaches the final square. If a player rolls a number that counts past the final square, then the player must wait until their next turn to try again.
The first player to reach the final square is declared the winner.

Implementation
Defining a function to roll a six-faced die we will use rand() here in order to generate the random integer value in each roll of die.
Defining a function to decide the move of the player based on the number that appeared on the top of the die. newPosition is the sum of the current position and the number on top of the die.
newSquare, the square where the player lands is basically the sum of newPosition and the board[new position] .
If newSquare is greater than the final value of the square board then try again else return newSquare.
Initialize the players in the main function further check for the moves and return the winner.
