# wordlegame_java

A simple implementation of the popular word-guessing game Wordle. This Java-based game challenges players to guess a hidden five-letter word in up to six attempts. It provides feedback after each guess, indicating whether letters are correct, in the correct position, or present in the word but in a different position.

Features
• Game Setup: Select a word number (up to 255) from a hidden list for
    each game session.
• Interactive Guessing: Players input their guesses, and the program
    provides feedback using symbols:
    - * for correct letters in the right position.
    - ! for correct letters in the wrong position.
    - X for incorrect letters.
• File Integration: Reads words from a file containing 255 hidden words.
• Case Insensitivity: Converts user input to lowercase to ensure uniform comparisons.
• User Feedback: After six guesses, the program displays if the player won or lost.

Getting Started
1. Setup: Clone the repository and import the project into your preferred IDE (e.g., Eclipse).
2. Run: Execute the main class to start the game.
3. Play: Follow on-screen prompts to make guesses until you find the hidden word or use all six attempts.

Future Improvements
Additional features like dictionary validation and multi-game sessions can make this Wordle implementation even more enjoyable.