# Blackjack-project
A simple, text-based Blackjack game implemented in Python. This command-line game allows you to play a classic game of Blackjack against the computer. The game follows the standard rules of Blackjack, where the goal is to get as close to 21 as possible without going over.

## Introduction

This project is a basic implementation of the popular card game Blackjack, also known as 21. The game is designed to be played in the terminal or command prompt, making it an easy and fun way to practice Python programming concepts such as functions, loops, conditionals, and list operations.

Our Blackjack Game House Rules
The deck is unlimited in size.
There are no jokers.
The Jack/Queen/King all count as 10.
The Ace can count as 11 or 1.
Use the following list as the deck of cards:
cards = [11, 2, 3, 4, 5, 6, 7, 8, 9, 10, 10, 10, 10]

The cards in the list have equal probability of being drawn.
Cards are not removed from the deck as they are drawn.
The computer is the dealer.

## Features

- **Random Card Dealing:** Cards are dealt randomly from a standard deck.
- **Blackjack Logic:** The game correctly handles the rules of Blackjack, including the special case for a Blackjack (an Ace and a 10-value card).
- **User Input:** The user can decide whether to "hit" (get another card) or "stand" (end their turn).
- **Computer AI:** The computer will automatically draw cards until it reaches a score of 17 or higher.

## How to Run

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/blackjack-game.git
   cd blackjack-game
