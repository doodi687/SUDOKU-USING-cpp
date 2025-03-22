Sudoku Master
Sudoku Game

🎮 Project Overview
Sudoku Master is a feature-rich C++ implementation of the classic Sudoku puzzle game, developed as a project at the Department of Computer Science and Engineering, MBM University, Jodhpur. This console-based game provides a complete Sudoku experience with multiple difficulty levels, puzzle generation, solving assistance, and performance tracking.

✨ Features
🧩 Multiple difficulty levels (Easy, Medium, Hard, Expert)
🔄 Automatic puzzle generation with unique solutions
⏱️ Real-time timer to track solving speed
💾 Save and load game functionality
🔍 Hint system for when you get stuck
✅ Solution verification
📊 Performance statistics tracking
🎯 Challenge mode with competitive scoring
🌈 Customizable console colors and UI elements
🚀 Installation
bash
# Clone the repository
git clone https://github.com/doodi687/sudoku-master.git

# Navigate to the project directory
cd sudoku-master

# Compile the source code
g++ -o sudoku main.cpp game.cpp board.cpp solver.cpp ui.cpp -std=c++17

# Run the game
./sudoku
🎲 How to Play
Sudoku is played on a 9x9 grid. The goal is to fill each cell with digits from 1 to 9 such that:

Each row contains all digits from 1 to 9 without repetition
Each column contains all digits from 1 to 9 without repetition
Each 3x3 sub-grid contains all digits from 1 to 9 without repetition
Controls
Key	Action
Arrow Keys	Navigate the board
1-9	Enter a number
0 or Delete	Clear a cell
H	Get a hint
S	Save game
L	Load game
V	Verify solution
N	New game
Q	Quit game
🖥️ Game Screenshots
Main Menu Gameplay Statistics

🧠 Technical Implementation
The game is implemented using modern C++ and follows object-oriented design principles. Key components include:

Core Classes
C++
class SudokuBoard {
    // Manages the 9x9 game board and game state
};

class SudokuGenerator {
    // Generates valid puzzles with unique solutions
};

class SudokuSolver {
    // Implements backtracking algorithm to solve puzzles
};

class GameUI {
    // Handles user interface and input processing
};

class GameStats {
    // Tracks player performance and statistics
};
Algorithms
Puzzle Generation: Backtracking with symmetry constraints
Puzzle Solving: Optimized backtracking with constraint propagation
Difficulty Rating: Cell removal with solution uniqueness verification
Hint System: Constraint-based analysis to provide helpful hints
📊 Performance Metrics
The game tracks various performance metrics to help you improve your Sudoku skills:

Average completion time per difficulty level
Success rate percentage
Personal best times
Hint usage statistics
Solve streak counters
🔜 Future Enhancements
Graphical user interface using SFML/SDL
Online leaderboards
Custom puzzle import
Advanced solving techniques tutorial
Mobile port
🧪 Testing
The project includes comprehensive unit tests for all core components:

bash
# Run tests
./run_tests.sh
👥 Contributors
Vishal Doodi - Lead Developer
Department of Computer Science and Engineering
MBM University, Jodhpur
📝 Project Information
Version: 1.0.0
Last Updated: March 22, 2025
License: MIT
🙏 Acknowledgments
Dr. Alok Singh for guidance and mentorship
MBM University Computer Science Department for resources and support
All testers who provided valuable feedback during development
