# Tic Tac Toe in C

Welcome to the Tic Tac Toe game! This simple console-based implementation allows two players to compete in the classic game. Follow the instructions below to get started.

## Features
- Two-player mode.
- Intuitive interface to play the game.
- Displays the game board after each move.
- Checks for a winner or a draw.

---

## How to Play
1. **Start the Program**  
   Compile the C code and run the executable in your terminal or preferred environment.

2. **Player Turns**  
   - The game alternates between Player 1 (X) and Player 2 (O).
   - Players choose their moves by entering the corresponding number on the game board.

3. **Game Board**  
   The game board is a 3x3 grid. Each cell is represented by numbers (1–9) for easy selection:

   ```
     1 | 2 | 3
    ---|---|---
     4 | 5 | 6
    ---|---|---
     7 | 8 | 9
   ```

4. **Winning Conditions**  
   - A player wins by placing three of their marks (X or O) in a row, column, or diagonal.

5. **Draw**  
   - If the board is full and no one has won, the game ends in a draw.

6. **Restart**  
   Restart the game by re-running the program.

---

## How to Compile and Run
1. Open a terminal and navigate to the directory containing the source file.
2. Compile the program using a C compiler, for example:
3. Run the compiled program:

## Code Structure
The program contains:
- **Main Function**: Initializes the game and handles the game loop.
- **Functions**:
  - `Board()` - Displays the current game board.
  - `checkWin()` - Determines if a player has won or if it's a draw.
  - `mark()` - Updates the game board with the player’s move.

---

## Example Output

```
Player 1 (X) - Enter your move: 5
     X |   |  
    ---|---|---
       |   |  
    ---|---|---
       |   |  

Player 2 (O) - Enter your move: 1
     X |   |  
    ---|---|---
       |   |  
    ---|---|---
     O |   |  

Player 1 wins! Congratulations!
```

---

## Requirements
- A C compiler
- Compatible with any terminal supporting standard input and output.

---

## Contributing
Feel free to enhance the program by:
- Adding an AI opponent.
- Introducing a graphical interface.
- Improving code efficiency.

---

Enjoy the game! 🎉
