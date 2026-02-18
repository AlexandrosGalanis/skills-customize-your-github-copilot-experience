
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build an interactive Hangman game in Python to practice string manipulation, loops, conditionals, and handling user input.

## 📝 Tasks

### 🛠️ Build the Hangman Game

#### Description
Create an interactive command-line Hangman game. The program should choose a secret word at random and let the player guess letters until they either reveal the whole word or run out of attempts.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list.
- Accept single-letter guesses and display the current word progress using underscores for unknown letters (e.g. _ a _ _ m _ n).
- Track and display the number of incorrect guesses remaining.
- End the game when the word is fully guessed or the player uses all attempts, showing a win or lose message.
- Handle repeated guesses gracefully (do not penalize the player twice for the same guess).

## 💡 Example Interaction

```
Welcome to Hangman!
Word: _ _ _ _ _ _
Guesses remaining: 6
Guess a letter: a
Good guess! Word: _ a _ _ _ _
Guess a letter: z
Incorrect. Guesses remaining: 5
...
Congratulations — you guessed the word: hangman
```

## 📎 Starter files

- See `starter-code.py` in this assignment folder for a minimal starting point.

## ✅ Skills Practiced

- String manipulation
- Loops and conditionals
- Basic I/O and program flow
- Random selection

If you'd like, I can also provide a reference implementation or expand the starter code with comments and tests.
