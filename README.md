# ⚫🔴 Linja Game - Simplified AI Implementation in Python

This repository hosts a simplified implementation of the abstract strategy game **Linja** by Steffen Spiele. Developed in Python (Jupyter Notebook), 
this project focuses on an AI-driven approach to simulate gameplay using the **minimax algorithm**.

## Game Overview

Linja is an abstract, race-based board game where two players race to move all their pieces toward their respective home spaces. Each turn, players 
make a two-step move to advance their pieces. Players aim to reach their home space, scoring points based on the final positions of their pieces. 

For complete rules, please refer to [The Abstract Rat - Linja](https://www.theabstractrat.com/reviews/linja).

## Key Features

- **Minimax AI**: Implements the minimax algorithm for decision-making, with a utility function to evaluate board states based on the game's scoring criteria.
- **Scoring Mechanism**: Points are awarded as follows:
  - 5 points per piece that reaches the home space.
  - 3, 2, or 1 point(s) respectively for pieces in the next closest rows.
  - Pieces further back score no points.
- **Simple Graphic Display**: A visual board layout updates each turn to reflect the pieces' movements and game progression.
- **2 game modes available**: _Player vs. AI_ or _AI vs. AI_ (for automated match simulations).

---

**Asignatura:** Sistemas Inteligentes, Ingeniería Informática, UBU

**Curso:** 2023/2024  
