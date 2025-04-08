# Tic Tac Toe in C++

A console-based implementation of the classic Tic Tac Toe game for two players, written in C++.

## Features

- Simple text-based interface
- Two-player (X and O) turn system
- Real-time board display
- Win condition detection for:
  - Rows, columns, and diagonals
- Input validation (accepts numbers 1-9)
- Clear player turn indication

## Code Structure

```cpp
tic_tac_toe.cpp
├── Draw()            // Renders the game board
├── input()           // Handles player moves
├── toggleplayer()    // Switches between X and O
├── win()             // Checks all victory conditions
└── main()            // Game loop and control flow
```

## How to Play

1. Clone the repository:
```bash
git clone https://github.com/yourusername/tic-tac-toe-cpp.git
```
2. Compile and Run:
```bash
g++ tic_tac_toe.cpp -o tictactoe
./tictactoe
```
3. Game instructions:
- Players alternate turns, entering numbers 1-9
- The board corresponds to numpad positions:
```
 1 | 2 | 3
-----------
 4 | 5 | 6
-----------
 7 | 8 | 9
```
- First player to get 3 marks in a row wins!

## Compilation Notes

Tested With:
- g++ (MinGW) on Windows
- clang++ on macOS
- g++ on Linux

No external dependencies required.

