STONE PAPER SCISSORS GAME
=========================

Overview
--------
This project is a command-line implementation of the classic Stone Paper Scissors game using Python. The game allows users to play multiple rounds against the computer while tracking game statistics and storing match history for analysis.

The project demonstrates the practical use of NumPy for randomization and Pandas for data handling and analysis.

Features
--------
- Play multiple rounds against the computer.
- Random computer choices generated using NumPy.
- Match history stored in a Pandas DataFrame.
- Automatic tracking of wins, losses, and draws.
- Win rate calculation.
- Export match history to a CSV file.
- Analyze gameplay statistics using Pandas.

Technologies Used
-----------------
- Python 3
- NumPy
- Pandas

Project Structure
-----------------
stone_paper_scissors.py
README.txt
sps_history.csv (generated after gameplay)

How It Works
------------
1. The user enters the number of rounds to play.
2. For each round:
   - The user selects Stone, Paper, or Scissors.
   - The computer randomly selects a move using NumPy.
   - The winner is determined based on game rules.
3. Results are stored in a Pandas DataFrame.
4. At the end of the game:
   - Match history is displayed.
   - Statistics are calculated.
   - Results are saved to a CSV file.

Game Rules
----------
- Stone beats Scissors.
- Scissors beats Paper.
- Paper beats Stone.
- Identical choices result in a Draw.

Installation
------------
Install the required libraries:

pip install numpy pandas

Running the Project
-------------------
Execute the Python file:

python stone_paper_scissors.py

Example Gameplay
----------------
Round 1
Choose Stone, Paper, or Scissors: Stone

Computer: Scissors
Result: Win

Round 2
Choose Stone, Paper, or Scissors: Paper

Computer: Paper
Result: Draw

Statistics Generated
--------------------
- Total Wins
- Total Losses
- Total Draws
- Win Percentage
- Most Frequently Chosen Moves
- Match History Table

Sample Data Output
------------------
Round | Player Choice | Computer Choice | Result
------------------------------------------------
1     | Stone         | Scissors        | Win
2     | Paper         | Paper           | Draw
3     | Scissors      | Stone           | Lose

CSV Export
----------
After the game ends, all match records are saved automatically to:

sps_history.csv

This file can be used for additional analysis and visualization.

Learning Outcomes

- Working with NumPy arrays.
- Using NumPy's random module.
- Creating and manipulating Pandas DataFrames.
- Performing basic data analysis.
- Exporting data to CSV files.
- Implementing game logic in Python.


Author
------
Developed as a beginner-friendly Python project to practice NumPy, Pandas, and programming fundamentals.
