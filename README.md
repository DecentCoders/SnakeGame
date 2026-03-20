# Snake Game | Beginner C++ Console Project
[![C++](https://img.shields.io/badge/C++-Standard-00599C?logo=c%2B%2B&logoColor=white)](https://isocpp.org/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-DecentCoders/SnakeGame-181717?logo=github)](https://github.com/DecentCoders/SnakeGame)
[![Template Repo](https://img.shields.io/badge/Template-Use_this_repo-2ea44f)](https://github.com/DecentCoders/SnakeGame/generate)
[![Last Commit](https://img.shields.io/github/last-commit/DecentCoders/SnakeGame)](https://github.com/DecentCoders/SnakeGame/commits/main)
[![Top Language](https://img.shields.io/github/languages/top/DecentCoders/SnakeGame)](https://github.com/DecentCoders/SnakeGame)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A classic, fully playable console-based Snake game built entirely with standard C++. This is a beginner-friendly practice project designed to teach core C++ programming fundamentals, published as a **public template repo** so you can easily fork, clone, or use it as a starting point for your own C++ learning projects. Created and maintained by DecentCoders (Hridoy Hawladar) as part of hands-on C++ practice.Took help from online resources such as kimi.ai, w3schools and others.

## 🎮 Core Game Features
This implementation includes all classic Snake game mechanics with a polished final build:
- Smooth, responsive snake movement controlled with keyboard arrow keys
- Random food spawning to grow the snake and increase your score
- Real-time score tracking as you play
- Collision detection for both window walls and the snake's own body
- Continuous game loop for seamless, uninterrupted gameplay
- Runs directly in the Windows console with no extra setup required
- No external libraries, frameworks, or dependencies needed

## 📚 What This Project Teaches
This is a hands-on learning project for anyone new to C++. Building and modifying this game will help you master:
- Core C++ syntax, including variables, loops, conditionals, and arrays
- How to build a functional real-time game loop
- Console input handling for responsive user controls
- Basic game logic and collision detection implementation
- How to compile C++ source code into a runnable executable
- Fundamental code structure and organization for C++ projects

## 🛠️ Tech Stack
This project uses only native, standard C++ to keep it simple and beginner-friendly:
- Pure standard C++ (compatible with all common Windows C++ compilers)
- Windows console API for input handling and screen rendering
- No external dependencies, frameworks, or installations required to play or build

## 📁 Project Structure
Here's a simple breakdown of every file in the repository:
```
SnakeGame/
├── .vscode/                # VS Code editor configuration files for local development
├── basic.cpp               # Main, complete C++ source code for the Snake game
├── basic.exe               # Pre-compiled Windows executable to run the game instantly
├── tempCodeRunnerFile.cpp  # Temporary development file for testing code snippets
├── tempCodeRunnerFile.exe  # Compiled test file from development
└── README.md               # Project documentation (this file)
```

## 🚀 How to Run the Game
You don't need any prior C++ experience to play the game — it works right out of the box with two simple options:

### Option 1: Instant Play (No Setup Required)
1. Download the `basic.exe` file from this repository
2. Double-click the file to launch the game
3. The game will open directly in your Windows console, and you can start playing immediately

### Option 2: Compile the Source Code Yourself (For Learning/Modification)
If you want to edit the game code or learn how C++ compilation works:
1. Install a C++ compiler (MinGW for Windows, or Visual Studio are both great beginner options)
2. Clone or download this repository to your local machine
3. Open your terminal or command prompt in the project folder
4. Compile the source code with this command:
   ```bash
   g++ basic.cpp -o basic.exe
   ```
5. Run the newly compiled `basic.exe` file to launch the game

## 🎮 Game Controls
| Key | Action |
|-----|--------|
| Arrow Keys (↑ ↓ ← →) | Move the snake up, down, left, or right |
| Close Console Window | Exit the game |

## 📋 Use This Repo as a Template
This is a public template repository! You can use it to create your own copy of the project in seconds, no forking required:
1. Click the **Use this template** button at the top of the GitHub repo page
2. Name your new repository and set your preferred visibility
3. Clone your new repo to your local machine
4. Start editing the code, adding new features, and learning C++!

## 🔮 Future Improvements
This is a foundational project with lots of room to add new features as you learn more C++:
- Saved high score system that persists between game sessions
- Adjustable difficulty levels with customizable snake speed
- Colorful console UI for the snake, food, and game border
- Pause/resume functionality during gameplay
- Game over screen with a built-in restart option
- Sound effects for eating food and game over events
- Borderless game mode option

## 🤝 Contributing
This is a beginner-focused learning project, and contributions are more than welcome! Whether you're fixing a bug, adding a small new feature, or improving the code for better readability, feel free to get involved:
1. Fork the repository
2. Create a feature branch for your changes (`git checkout -b feature/new-snake-feature`)
3. Commit your changes with a clear, descriptive message (`git commit -m 'Add pause functionality'`)
4. Push to your branch (`git push origin feature/new-snake-feature`)
5. Open a Pull Request to this repo

## 📄 License
This project is open source and available under the [MIT License](LICENSE). You're free to use, modify, and distribute the code for your own learning or personal projects.

##  Acknowledgements
This project was built as a hands-on way to learn and practice C++ fundamentals. A big thank you to the beginner C++ learning community and free online resources that guided the implementation of core game mechanics.
