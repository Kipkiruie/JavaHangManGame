# Java Hangman Game

A simple console-based implementation of the classic Hangman game written in Java. Players attempt to guess a hidden word one letter at a time while trying to avoid making too many wrong guesses!

---

## Features

- **Interactive Gameplay**: Guess letters to reveal the hidden word.
- **Hangman Art**: Visual representation of the Hangman progress with each wrong guess.
- **Win/Lose Conditions**:
  - Win by guessing the word before making 6 wrong guesses.
  - Lose after 6 wrong guesses, ending the game with a "GAME OVER" message.

---

## How to Play

1. Run the program.
2. The hidden word will be represented as underscores (`_`).
3. Guess one letter at a time:
   - If the letter is in the word, it will be revealed in the correct position(s).
   - If the letter is not in the word, the Hangman progresses closer to completion.
4. Continue guessing until:
   - All letters are revealed (You win!), or
   - The Hangman is fully drawn (You lose!).

---

## Prerequisites

- **Java Development Kit (JDK)**: Java 8 or higher.
- **IDE or Command Line**: Any environment to run Java programs (e.g., IntelliJ IDEA, Eclipse, or terminal).

---

## How to Run

1. Copy the code into a file named `Main.java`.
2. Compile the file:
   ```bash
   javac Main.java
