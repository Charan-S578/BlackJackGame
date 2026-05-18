# BlackJack Game ♠️♥️♣️♦️

A simple command-line BlackJack game developed in Python where the player competes against the computer. The game follows basic Blackjack rules including card dealing, score calculation, Ace handling, and automatic dealer turns.

---

## Features

* Random card dealing system
* Blackjack detection
* Automatic score calculation
* Ace value adjustment (11 → 1)
* Computer dealer logic
* Interactive command-line gameplay
* Replay option after each game

---

## Technologies Used

* Python 3
* Random Module

---

## Game Rules

1. Both the player and computer receive two cards.
2. The goal is to get as close to 21 as possible without going over.
3. Number cards count as their value.
4. Face cards (J, Q, K) count as 10.
5. Ace can count as 11 or 1 depending on the score.
6. Blackjack = Ace + 10-value card.
7. The computer keeps drawing cards until its score reaches at least 17.

---

## How to Run the Project

### Step 1: Clone the Repository

```bash id="0d8s4g"
git clone <your-github-repo-link>
```

### Step 2: Navigate to the Project Folder

```bash id="8v2w7n"
cd blackjack-game
```

### Step 3: Run the Python File

```bash id="4d0xk9"
python main.py
```

---

## Project Structure

```bash id="5m1c2y"
blackjack-game/
│
├── main.py
└── README.md
```

---

## Sample Gameplay

```bash id="1j7xk0"
Your cards: [10, 7], current score: 17
Computer's first card: 9

Type 'y' to get another card, Type 'n' to pass: y

Your final hand: [10, 7, 3], final score: 20
Computer's final hand: [9, 8], final score: 17

You Win.
```

---

## Learning Outcomes

This project helps in understanding:

* Python functions
* Loops and conditionals
* Lists and list operations
* Random module usage
* Game logic implementation
* Score comparison algorithms

---

## Future Improvements

* Add betting system
* Add multiple players
* Create GUI version using Tkinter or Pygame
* Add card graphics and animations
* Store game history and scores

---

## Author

Developed by [Charan S]

