🗳️ Online Voting App
📌 Overview

This is a fully functional Online Voting Application built with HTML, CSS, and JavaScript.
It allows users to create polls, cast votes, and view results — while preventing duplicate votes.

🚀 Features
✅ Core Features

Create polls with multiple options

Vote on active polls (one vote per user per poll)

View results with real-time vote counts and percentages

🔒 Security

Prevents duplicate votes using simulated user IDs

Input validation and error handling

🎨 User Interface

Three tabs: Create Poll, Vote, Results

Responsive design (desktop & mobile)

Smooth animations and interactive elements

💾 Data Storage

Uses localStorage to simulate a database

Stores poll questions, options, and votes persistently

JSON serialization for structured data

🛠️ Technology Stack

Frontend: HTML, CSS, JavaScript (ES6)

Storage: localStorage (simulated database)

📂 Project Structure
online-voting-app/
│── index.html        # Main HTML file
│── style.css         # App styling
│── script.js         # Voting logic (VotingSystem class)
│── README.md         # Documentation

📖 Usage Instructions

Create Poll

Enter a question and at least two options

Submit to create a new poll

Vote

Select an option from available polls

Submit your vote (restricted to one vote per poll per user)

View Results

See real-time results with progress bars and percentages

📸 Screenshots

Create Poll Tab

Vote Tab

Results Tab

(Add screenshots here)

🔮 Future Enhancements

Backend integration with real database (MySQL/MongoDB)

User authentication system

Admin dashboard for managing polls
