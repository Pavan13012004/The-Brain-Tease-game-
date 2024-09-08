# The Brain Tease game

## Hangman Game

This is a simple text-based Hangman game implemented in Python. The game randomly selects a word, and the player attempts to guess it by suggesting letters within a limited number of attempts.

## Features

Random word selection from a predefined list.
Player can guess one letter at a time.
Tracks guessed letters to prevent repeated guesses.
Displays the current state of the word (with guessed letters and underscores for missing ones).
Limited number of incorrect guesses (6 attempts).
Victory and loss conditions:
Win: Player successfully guesses the word.
Lose: Player runs out of attempts, and the correct word is revealed.


## How to Play
The game randomly chooses a word from the list of words.
The player is prompted to guess a letter.
If the guessed letter is in the word, it is revealed in its correct position(s).
If the guessed letter is not in the word, the number of attempts decreases.
The game continues until either:
The player guesses the entire word correctly (win).
The player runs out of attempts (loss).
Requirements
Python 3.x
random module (comes with Python's standard library)


## How to Run

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/hangman-game.git
Navigate to the project directory:

bash
Copy code
cd hangman-game
Run the game:

bash
Copy code
python hangman.py


## Code Overview

Word List: The game uses a predefined list of words, from which one is randomly chosen for each game.
Gameplay Logic:
The player is given 6 attempts to guess the word.
Correct guesses reveal the letters in their respective positions.
Incorrect guesses reduce the remaining attempts.
End of Game:
The player wins by guessing all letters of the word.
The player loses if they run out of attempts without guessing the word.


## Example

plaintext
Copy code
Welcome to Hangman!
Word: _ _ _ _ _ _
Attempts left: 6
Guess a letter: a
Correct guess!
Word: a _ _ _ _ _
Attempts left: 6
Guess a letter: e
Incorrect guess!
Attempts left: 5
