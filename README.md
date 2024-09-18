
# Tic Tac Toe Game in C++

This project is a simple command-line Tic Tac Toe game developed in C++ for two players. The game board is a 3x3 grid, and players take turns placing their markers (X or O) until one of the players wins by aligning three markers in a row, column, or diagonal, or until all slots are filled, resulting in a tie.

## How to Play

1. At the start of the game, Player 1 chooses their marker (X or O), and Player 2 automatically gets the other marker.
2. Players take turns entering a number (1-9) corresponding to the slot where they want to place their marker.
3. The first player to align three markers horizontally, vertically, or diagonally wins.
4. If all slots are filled without a winner, the game ends in a tie.

## Instructions

1. Clone or download the project files.
2. Open a terminal and navigate to the project directory.
3. Compile the code using the following command:

    ```
    g++ tictactoe.cpp -o tictactoe
    ```

4. Run the game:

    ```
    ./tictactoe
    ```

5. Follow the on-screen instructions to play the game.

## Game Rules

- The board consists of 9 slots numbered from 1 to 9.
- Players alternate turns, placing their chosen marker (X or O) in an available slot.
- The game ends when one player aligns three of their markers or when all slots are filled.

## Future Improvements

- Add a graphical interface for a better user experience.
- Implement a single-player mode with AI.
