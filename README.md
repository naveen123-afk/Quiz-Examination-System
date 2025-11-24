# Quiz-Examination-System
Programming Quiz Game

This project is a simple Python-based quiz game that tests basic programming and computer science knowledge. The program selects 10 random questions from a question bank, checks the user’s answers, calculates a score, and records the final result in a leaderboard stored in a file called scores.txt.

Features

Randomly selects 10 questions from a list of 20.

Gives +10 points for each correct answer and -3 points for each incorrect answer.

Adds a bonus of +9 points after the quiz.

Saves the user's score and name to a file.

Displays a sorted leaderboard showing top scores.

Uses simple text input for answers (A, B, C, or D).

How the Game Works

The program starts by printing a welcome message.

Questions and answers are stored in lists.

The questions and answers are paired using the zip() function.

Ten random question-answer pairs are selected.

The user answers each question by typing the letter of their choice.

The program checks each answer and updates the score:

Correct answer: +10 points

Wrong answer: -3 points

After all questions, the program:

Adds a +9 bonus

Shows the final score

Asks for the user’s name

The score and name are saved to scores.txt.

The file is read, sorted in descending order, and shown as a leaderboard.

Project Files
quiz_game.py       # main program
scores.txt         # stores scores and player names (auto-created)
README.md          # documentation

Requirements

Python 3.x

No external libraries are required.
Only built-in Python modules are used.

How to Run

Make sure you have Python 3 installed.

Run the script by typing:

python quiz_game.py


Answer the questions as they appear.

Enter your name at the end to save your score.

Check the leaderboard printed by the program.

Code Summary

Questions are stored in a list.

Answers are stored in a matching list.

The program uses random.sample() to select 10 random questions.

Scores are calculated based on correct and incorrect answers.

Results are saved and displayed in sorted order.

Possible Future Improvements

Add a timer for each question.

Store questions in a JSON file.

Add multiple difficulty levels.

Add a percentage score display.

Create a graphical version.
