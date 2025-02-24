# CodeAlpha_Hangman
# Hangman Game

## Description
This is a simple text-based Hangman game implemented in Python. The game selects a random word from a predefined list, and the player must guess the word one letter at a time. The player has a limited number of incorrect guesses before the game is lost.

## Features
- Random word selection from a predefined list
- Letter-by-letter guessing
- Display of guessed letters and word progress
- Limited incorrect guesses before losing
- Text-based interface

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/hangman-game.git
   ```
2. Navigate to the project directory:
   ```sh
   cd hangman-game
   ```
3. Run the game:
   ```sh
   python hangman.py
   ```

## How to Play
1. The game will randomly select a word and display it as underscores (_ _ _ _).
2. You will be prompted to guess one letter at a time.
3. If the letter is in the word, it will be revealed in the correct position(s).
4. If the letter is incorrect, you lose a life.
5. You have a limited number of incorrect guesses before the game ends.
6. Win by guessing the complete word before running out of attempts!

## Example Gameplay
```
Welcome to Hangman!
Word: _ _ _ _ _
Guess a letter: a
Correct! Word: _ a _ _ _
Guess a letter: e
Incorrect! You have 5 attempts left.
...
```

## Requirements
- Python 3.x

## Contributing
If you want to contribute to this project, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.

