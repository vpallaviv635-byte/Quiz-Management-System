# Quiz-Management-System

INTODUCTION:

The Quiz Management System is a Python-based application that uses MySQL as its database. The system allows administrators to manage quiz questions and enables players to participate in quizzes across different difficulty levels. Scores are calculated automatically based on the player's performance.

FEATURES:

Admin Functions

- Add new quiz questions
- Modify existing questions
- Delete questions
- Manage questions for Easy, Medium, and Hard levels

Player Functions

- Choose a difficulty level
- Answer multiple-choice questions
- Get a second chance for incorrect answers
- View final score after completing the quiz

TECH STACK:
- Python
- MySQL
- MySQL Connector

DATABASE SETAILS:

Database Name: Quizz

Tables:

- easylevel
- mediumlevel
- hardlevel

Each table stores:

- Question Number
- Question
- Options (A, B, C)
- Correct Answer
- Alternate Question
- Alternate Options
- Alternate Correct Answer

Scoring System

Attempt| Score
First Correct Answer| 2 Points
Second Correct Answer| 1 Point
Incorrect Answer| 0 Points

PROJECT STRUCTURE:

Quiz_Project/

├── quiz.py

└── README.md

CONCLUSION:
This project demonstrates the integration of Python with MySQL to create an interactive quiz application. It provides efficient quiz management and an engaging experience for users through multiple difficulty levels and a scoring mechanism.
