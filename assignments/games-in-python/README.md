# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a playable command-line Hangman game in Python to practice string manipulation, loops, conditionals, and user input. The program should be user-friendly, validate input, and end with a clear win or lose message.

## 📝 Tasks

### 🛠️ Build the Hangman Game

#### Description
Implement a playable terminal Hangman game that randomly selects a word from a predefined list and allows a player to guess letters until they win or run out of attempts.

#### Requirements
Completed program should:

- Randomly select a secret word from a list of at least 20 words.
- Display the current progress as underscores and revealed letters (e.g., `_ _ a _ _`).
- Accept single-letter guesses (case-insensitive) and validate input (letters only, single character).
- Track and display guessed letters and the number of remaining incorrect attempts (e.g., 6 attempts).
- Prevent duplicate guesses from reducing remaining attempts.
- End with an appropriate win or lose message and reveal the secret word when the game finishes.

Example session:

```
$ python hangman.py
Welcome to Hangman!
Word: _ _ _ _ _
Guessed: 
Attempts left: 6
Enter a letter: a
Word: _ a _ _ _
Guessed: a
Attempts left: 6
...
```

### 🛠️ Optional: Bonus Features

#### Description
Add one or more enhancements to make the game more polished, challenging, or testable.

#### Requirements
Completed program should include at least one bonus feature, such as:

- Difficulty levels that change allowed attempts (Easy/Medium/Hard).
- Category-based word lists or loading words from an external file.
- ASCII-art hangman stages that progress with incorrect guesses.
- A replay option and/or simple scoring across rounds.
- Unit tests for core functions (e.g., word selection, input validation, guess handling).