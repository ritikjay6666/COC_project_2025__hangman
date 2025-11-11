Hangman Game — C Project (Single Word Version)
A classic Hangman word-guessing game built in C using a single secret word, loops, functions, and character arrays.
Created for the Clash of Coders Capstone Project to demonstrate structured programming, logic building, and clean code practices.

🚀 Project Overview
The game uses a fixed secret word (CLASH) that the player must guess one letter at a time.
The player gets 6 lives and loses one life on every incorrect guess.
The game ends when the word is fully guessed (Win ✅) or lives run out (Lose ❌).

🧠 Concepts Used
🔹 C Programming
Character Arrays
for & while loops
if/else statements
Separate functions for game logic
printf() and scanf()
String handling (string.h)
Character case handling (ctype.h)
🔹 Logic Skills Demonstrated
Iterative checking of letter positions
Pattern matching
Decision making using conditions
State tracking (lives, guesses, progress)
📌 Features
✔ One fixed secret word
✔ Progress display using underscores (_ _ _ _ _)
✔ Case-insensitive user input
✔ Modular and readable code
✔ Well-commented for academic review
✔ No randomization (as required)

🧩 Game Rules
The word starts hidden with underscores
Guess one letter at a time
Correct guesses reveal letters
Wrong guesses reduce lives (6 total)
Win by completing the word before lives = 0
