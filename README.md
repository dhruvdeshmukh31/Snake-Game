Project Title: Python Snake Game by dhruv deshmukh 25MIM10205
Overview
This project is a classic Snake Game implemented in Python, designed as part of the VIT Bhopal “Build Your Own Project” assignment. It features modular code with clear separation of game engine, graphics, and configuration components. The game allows users to control a snake to eat food and grow without colliding with boundaries or itself.

Features

	•	Smooth snake movement with arrow key controls
	•	Real-time score updating
	•	Variable difficulty settings and game configurations
	•	Error handling for invalid moves
	•	Modular design and clear code documentation

Technologies Used

	•	Python 3.x
	•	Pygame library for graphical interface and event handling
	•	Git for version control

Installation & Setup

Prerequisites
	
  •	Python 3.x installed on your system
	•	Pygame library (install via pip)
  Usage
	•	Use arrow keys to control the snake’s direction
	•	Eat food to increase the score and snake length
	•	Avoid collisions with the snake body or window edges
	•	The game ends when a collision occurs

  
Testing

Unit tests are provided for key game modules:
pytest tests/

Project Structure

snake-game/
├── README.md
├── statement.md
├── requirements.txt
├── src/
│   ├── main.py
│   ├── game_engine.py
│   ├── graphics.py
│   ├── config.py
│   └── player.py
├── tests/
│   ├── test_game_engine.py
│   └── test_graphics.py
├── docs/
│   ├── architecture_diagram.png
│   ├── use_case_diagram.png
│   └── workflow_diagram.png
└── assets/
    └── images/
<img width="1461" height="827" alt="Screenshot 2025-11-25 at 00 20 44" src="https://github.com/user-attachments/assets/0a9f6560-2d63-4c3a-8819-8eb925d7da21" />
