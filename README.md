# AI-Based Tic Tac Toe Game 🎮

**AI-Based Tic Tac Toe Game**! This project is a simple yet engaging implementation of the classic game, enhanced with an unbeatable AI using the **MiniMax algorithm**.

---

## 🎯 Features

- **Interactive Gameplay**: Play as `X` against an intelligent AI opponent (`O`).
- **Unbeatable AI**: The AI makes optimal moves to challenge your skills.
- **Dynamic User Interface**:
  - Highlights the winning combination.
  - Displays the winner or announces a tie.
  - Offers a convenient replay option.
- **Modern Styling**: Responsive design with a clean and intuitive interface.
![image](https://github.com/user-attachments/assets/a1607897-700a-4600-bbf1-74c947f493fe)
---
## 📚 About the Minimax Algorithm
The minimax algorithm is a recursive decision-making algorithm commonly used in two-player games like Tic Tac Toe, Chess, and Checkers. The goal of the algorithm is to minimize the possible loss in a worst-case scenario.

Here’s how it works in this game:

Game Tree:

The algorithm simulates all possible moves for both the human player (X) and the AI (O), creating a tree of game states.
Scoring:

Each end state is scored:
+10 if the AI wins.
-10 if the human wins.
0 for a tie.
Decision Making:

The AI assumes the human player will always play optimally (minimizing the AI's score).
It selects the move that maximizes its score while minimizing the human player’s score.
Recursive Calculation:

The algorithm evaluates all possible outcomes recursively until it reaches the game’s end state.
The minimax algorithm ensures the AI is unbeatable because it explores all possible moves and chooses the one that guarantees the best result.


![image](https://github.com/user-attachments/assets/f7bd788e-0908-4e56-a443-195cdf06f33a)
![image](https://github.com/user-attachments/assets/189e2620-9ba1-40ac-89c5-c2a04fcc9150)
---
## 🛠️ Technologies Used

- **HTML**: Markup for the game structure.
- **CSS**: Styling for the layout and animations.
- **JavaScript**: Game logic, event handling, and AI algorithm.

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/SreeDatta21/AI-Based-TicTacToe.git
