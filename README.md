📝 Programming Quiz Game

A simple and interactive Python-based quiz game that tests users on basic programming concepts.
It randomly selects questions, calculates the score, applies bonuses, and maintains a persistent leaderboard stored in scores.txt.

🚀 Features

🎯 Randomized Questions – Each quiz session selects 10 random questions.

🧠 Multiple-Choice Format – Easy A/B/C/D input system.

⭐ Scoring System

+10 points for each correct answer

−3 points for each incorrect answer

+9 bonus points at the end

🏆 Leaderboard – Automatically saves and displays high scores.

📂 Persistent Storage – Scores are saved in scores.txt.

🖥 Beginner-Friendly Python Code – Simple and easy to understand.

📌 How It Works

The program displays a welcome banner.

Randomly selects 10 questions from the question bank.

The user answers each question (A/B/C/D).

The score is calculated and bonus added.

User enters their name.

Score is saved in scores.txt.

The leaderboard is displayed, sorted by highest score.

📁 File Structure
📦 Programming-Quiz-Game
 ┣ 📜 quiz.py           # Main quiz script
 ┣ 📜 scores.txt        # Stored high scores
 ┗ 📜 README.md         # Project documentation

▶ How to Run

Make sure Python is installed on your system.

python quiz.py


The game will start instantly and prompt you with questions.

💡 Requirements

Python 3.6+

No external libraries required (only built-in modules)

📝 Customization

You can easily modify the quiz by:

Adding new questions to Questions list.

Updating or changing answer options.

Adjusting scoring rules.

Changing number of questions asked.

🏅 Leaderboard Format

score | name

Example:

89     |   Alice
72     |   Mark
54     |   Rahul

🤝 Contribution

Pull requests and improvements are welcome!
You may add:

GUI interface

Difficulty levels

Category-based question selection

📜 License

This project is free to use, modify, and distribute.
