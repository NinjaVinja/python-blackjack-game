# 🃏 Python Blackjack Game

A simple command-line Blackjack game built with Python. This project simulates the classic Blackjack card game where you play against the computer.

## 📌 Features

- Random card dealing
- Blackjack detection
- Automatic Ace (11 → 1) conversion
- Computer follows Blackjack dealer rules
- Score calculation
- Win/Lose/Draw detection
- Play multiple rounds

---

## 🛠️ Technologies Used

- Python 3
- Random Module

---

## 📂 Project Structure

```
python-blackjack-game/
│
├── main.py        # Main game logic
├── art.py         # ASCII logo
├── README.md
├── LICENSE
└── .gitignore
```

---

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/yourusername/python-blackjack-game.git
```

### Navigate into the project

```bash
cd python-blackjack-game
```

### Run the game

```bash
python main.py
```

---

## 🎮 Game Rules

- Both the player and the computer receive two cards.
- Number cards are worth their face value.
- Face cards (J, Q, K) are worth 10.
- Ace counts as 11 unless it would cause the hand to exceed 21, in which case it counts as 1.
- A Blackjack is an Ace and a 10-value card as the first two cards.
- The computer keeps drawing cards until its score reaches at least 17.
- The player can choose to draw additional cards or stand.

---

## 📷 Example Gameplay

```
Your cards: [10, 7], Current score: 17
Computer First card: 9

Type 'y' to get another card, Type 'n' to pass: n

Your final hand: [10, 7], final score: 17
Computer final hand: [9, 8], final score: 17

Draw
```

---

## 🚀 Future Improvements

- Card suits (♠ ♥ ♦ ♣)
- Multiple decks
- Betting system
- Player balance
- Split and Double Down
- Graphical User Interface (Tkinter or Pygame)
- Difficulty levels

---

## 📖 Learning Objectives

This project demonstrates:

- Functions
- Lists
- Loops
- Conditional Statements
- Random Module
- Game Logic
- Score Calculation
- User Input Handling

---

## 👨‍💻 Author

**Taha Ahmad**

GitHub: https://github.com/NinjaVinja

---

## 📄 License

This project is licensed under the MIT License.
