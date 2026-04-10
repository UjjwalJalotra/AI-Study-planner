# AI-Study-planner
AI_Study_Planner_Vityarthi

A smart command-line based study planner developed in Python that helps students manage their daily study routine efficiently using an AI-inspired prioritization approach.

---

Author

Name: Ujjwal Jalotra
Registration No.: 25BAI10118

---

Features

* Intelligent subject prioritization using a scoring algorithm
* Efficient time allocation based on difficulty, importance, and urgency
* Automatic generation of daily study schedule
* Simple and beginner-friendly CLI interface
* Easily extendable for advanced AI/ML integration

---

How It Works

Each subject is assigned a priority score using the formula:

priority = (difficulty * 0.4) + (importance * 0.4) + (1/days_left * 0.2)

Parameters:

* Difficulty (1–5): Level of complexity of the subject
* Importance (1–5): Weightage or significance
* Days Left: Remaining time before the exam

Based on this score, the planner distributes the available study hours proportionally among subjects.

---

Installation

1. Clone the repository

git clone https://github.com/your-username/AI_Study_Planner_Vityarthi.git
cd AI_Study_Planner_Vityarthi

2. Run the program

python main.py

No external libraries are required (pure Python).

---

Usage

1. Enter the number of subjects
2. Provide details for each subject:
   * Subject Name
   * Difficulty (1–5)
   * Importance (1–5)
   * Days left for exam
3. Enter total study hours available per day
4. Get your personalized study plan instantly

---

Example

=== AI Study Planner ===

Enter number of subjects: 3

Subject name: Data Structures

Difficulty: 5

Importance: 5

Days until exam: 2

Subject name: Environmental Studies

Difficulty: 2

Importance: 3

Days until exam: 6

Subject name: Digital Logic Design

Difficulty: 4

Importance: 4

Days until exam: 3

Total study hours per day: 7

Today's Study Plan:
Data Structures: 3.1 hours
Digital Logic Design: 2.5 hours
Environmental Studies: 1.4 hours

---

Project Structure

AI_Study_Planner_Vityarthi/
│
├── main.py        # Main logic of the planner
└── README.md      # Documentation file

---

Future Enhancements

* Integration with AI APIs (OpenAI, Gemini, etc.)
* Performance tracking and progress analytics
* GUI version using Tkinter or PyQt
* Database integration (SQLite/MySQL)
* Web or mobile application version

---

Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Implement your changes
4. Submit a pull request

---

License

This project is open-source and available under the MIT License.


