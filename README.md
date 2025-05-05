# 🧠 Minesweeper AI Agent 🎯

This repository contains an AI agent capable of playing the game of Minesweeper intelligently using logical inference and knowledge representation. It is a project from the CS50's Introduction to Artificial Intelligence with Python course.

## 📁 Contents

* `minesweeper.py`: Contains the core logic and structure of the Minesweeper game and the AI agent.
* `runner.py`: A visual interface to run and watch the AI agent play the Minesweeper game interactively using Pygame.

---

## 🗂️ File Descriptions

### `minesweeper.py`

This file implements:

* 🧩 The `Minesweeper` class: manages the game board, bomb locations, and basic game mechanics.
* 🧾 The `Sentence` class: represents logical statements about the board, used by the AI to reason.
* 🤖 The `MinesweeperAI` class: holds knowledge of the game, adds new logical inferences, and decides safe or random moves.

This script focuses on the backend logic and can be used independently for testing the AI decision-making process.

### `runner.py`

This script uses Pygame to create a GUI for the Minesweeper game. It runs the game loop, handles mouse events, and visualizes the AI's progress. It is useful for observing how the AI interacts with the game board step by step.

---

## 🛠️ How to Run

### Prerequisites

Make sure you have Python 3 installed and the Pygame library:

```bash
pip install pygame
```

### ▶️ Run the Game with AI

```bash
python runner.py
```

This will launch a window showing the Minesweeper board and the AI playing the game.

---

## 🙏 Acknowledgements

This project is part of CS50's Introduction to Artificial Intelligence with Python by Harvard University.

---

## 📜 License

This repository is open source and available under the MIT License.
