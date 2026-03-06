# 📘 Assignment: Games in Python

## 🎯 Objective

Build a complete Hangman game in Python. In this assignment, you will practice loops, conditionals, string manipulation, and user input while creating a fun, interactive program.

## 📝 Tasks

### 🛠️ Build the Core Game Loop

#### Description
Set up the main structure of the Hangman game, including selecting a secret word, tracking guesses, and running the game loop until the game is over.

#### Requirements
Completed program should:

- Randomly choose a word from a predefined list.
- Initialize game state variables such as guessed letters, incorrect guesses, and maximum incorrect attempts.
- Repeatedly display the current progress of the word using placeholders (for example: `_ _ _ _ _`).
- Continue the loop until the player guesses the full word or runs out of attempts.

### 🛠️ Handle Input and End Conditions

#### Description
Add player interaction and game outcomes so the game feels complete and user-friendly.

#### Requirements
Completed program should:

- Prompt the user to guess one letter at a time.
- Validate and process guesses, updating correct letters and incorrect guess counts.
- Show how many incorrect guesses remain after each turn.
- Display a clear win message when the player guesses the word.
- Display a clear lose message with the secret word when attempts are exhausted.
