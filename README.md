# ♟️ Othello (Reversi) AI Game & Tournament Framework

An AI-driven implementation of the classic **Othello (Reversi)** board game in Python, featuring various intelligent agents (such as Minimax, Alpha-Beta Pruning, and Heuristic Search) along with a tournament framework to evaluate agent performance.

---

## 📌 Features

* **Game Engine (`game/`):** Complete Othello game logic, board state management, move validation, and flip mechanics.
* **AI Agents (`agents/`):** Implementation of automated agents using Search Algorithms, Game Theory heuristics, and decision-making strategies.
* **Tournament System (`tournament.py`):** Automated framework for running matches and tournaments between different AI strategies to benchmark performance.

---

## 📁 Repository Structure

```text
Othello-Game/
├── agents/             # AI agent implementations (Minimax, Heuristics, Random, etc.)
├── game/               # Core game logic, rules, and board presentation
├── main.py             # Single game / Interactive mode runner
├── tournament.py       # Tournament framework to test agents against each other
├── README.md           # Project documentation
└── __pycache__/        # Compiled Python cache files
