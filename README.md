# The Snake

A classic Snake game built with Python and Pygame using object-oriented programming.

## Features

- Keyboard-controlled snake movement
- Random apple generation
- Snake growth after collecting an apple
- Self-collision detection and game reset
- Screen-edge wrapping
- Separate game objects for the snake and apple
- Automated tests and code-style configuration

## Tech stack

- Python
- Pygame
- OOP
- pytest
- flake8

## Architecture

The game is built around a small object hierarchy:

- `GameObject` — base class for drawable game objects
- `Apple` — manages apple position and rendering
- `Snake` — manages movement, direction, body length and collision state
- `handle_keys()` — processes keyboard input
- `main()` — runs the game loop

## Run locally

```bash
git clone https://github.com/samedovv1/the_snake.git
cd the_snake

python -m venv venv
```

Activate the virtual environment:

```bash
# Windows
venv\Scripts\activate

# macOS / Linux
source venv/bin/activate
```

Install dependencies and run:

```bash
pip install -r requirements.txt
python the_snake.py
```

## Controls

- ↑ — move up
- ↓ — move down
- ← — move left
- → — move right

## Tests

```bash
pytest
```

## What this project demonstrates

This project demonstrates Python fundamentals, object-oriented design, event handling, game loops, state management, collision detection and working with a third-party library.
