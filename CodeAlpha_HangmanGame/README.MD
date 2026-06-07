# Text-Based Hangman Game

A simple, interactive command-line Hangman game written in Python. The player must guess a hidden word one letter at a time before running out of attempts.

## Features

* **Predefined Word Bank:** Randomly selects a secret word from a predefined list of programming terms.
* **Attempt Tracking:** Players are allowed a maximum of 6 incorrect guesses before it's "Game Over".
* **Input Validation:** Ensures the user only enters a single alphabetical character per turn.
* **Duplicate Guess Prevention:** Remembers previously guessed letters and warns the user if they try the same letter twice.
* **Progress Display:** Dynamically updates to show correctly guessed letters and remaining blank spaces.

## Prerequisites

To run this game, you need to have Python installed on your computer. 
* Python 3.x (Download from [python.org](https://www.python.org/))

## How to Run the Game

1. Download or copy the script and save it as `hangman.py`.
2. Open your terminal or command prompt (or use the integrated terminal in VS Code).
3. Navigate to the folder where you saved the file.
4. Run the script using the following command:
```bash
   python hangman.py
