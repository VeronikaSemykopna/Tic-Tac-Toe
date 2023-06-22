# Tic-Tac-Toe
 code implements a simple text-based Tic-Tac-Toe game
ode, the print_board() function is defined to print the Tic-Tac-Toe board. It takes the board as an argument and prints the board's current state, with rows separated by horizontal lines.

The check_win() function checks if a player has won the game. It iterates through the rows, columns, and diagonals of the board to check for a winning combination. If it finds a winning combination for the specified player, it returns True; otherwise, it returns False.

The play_game() function is the main function that allows players to take turns and plays the game. It initializes an empty Tic-Tac-Toe board, sets the current player to "X", and starts a game loop. Inside the loop, it prints the board, prompts the current player for their move, validates the move, updates the board, checks for a win or tie, and switches the current player. The game loop continues until a win or tie is detected.

To play the game, you can call the play_game() function. It will prompt the players to enter their moves by specifying the row and column numbers (both ranging from 0 to 2) of their desired cell. The game will continue until there is a winner or a tie, and the final result will be displayed on the screen.
