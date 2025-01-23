# Hangman Game

## Description

This is a simple text-based Hangman game written in Python. The program selects a random word from a predefined list, and the player guesses one letter at a time to uncover the word. The game sets a limit of 6 incorrect guesses.

## How to Play

1. Run the `hangman.py` script.
2. The game will display the initial state of the hangman and the word to be guessed as underscores.
3. Guess one letter at a time by typing it and pressing Enter.
4. If the guessed letter is in the word, it will be revealed in the correct positions.
5. If the guessed letter is not in the word, the hangman will start to appear.
6. You have 6 incorrect guesses before the hangman is fully drawn.
7. The game ends when you either guess the word correctly or run out of tries.

## Requirements

- Python 3.x

## Running the Game

1. Clone this repository.
2. Navigate to the repository directory.
3. Run the game using the following command:
   ```sh
   python hangman.py
