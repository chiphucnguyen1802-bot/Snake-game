# 🐍 Snake Game (Python + Pygame)

A simple **Snake game** written in Python using **Pygame**.  
This console + graphical game demonstrates basic game development concepts such as loops, collision detection, grid systems, and modular code design.

---

## 🎮 How to Play
1. Run the game in terminal.
2. Use arrow keys to control the snake:
   - Up Arrow → move up
   - Down Arrow → move down
   - Left Arrow → move left
   - Right Arrow → move right
3. Eat the red apples to grow and gain points.
4. Avoid:
   - Hitting the walls
   - Colliding with yourself
5. Game over occurs on collision. Press **Space** to restart.

---

## 📁 Files
- `main.py` – main Python file to run the game  
- `snake.py` – contains Snake game logic and class  
- `config.py` – contains settings like colors, screen size, FPS  
- `README.md` – this file

---

## ▶️ Run
1. Make sure you have **Python 3** installed.
2. Install **Pygame** if not installed:

```bash
pip install pygame
🧠 How It Works

SnakeGame class in snake.py handles:

Snake movement

Apple spawning

Collision detection (walls and self)

Score tracking

Resetting the game

main.py handles:

Rendering the game grid

Drawing snake and apple

Capturing keyboard events

Main game loop

Game speed increases slightly with higher score to increase difficulty.

✨ Features

Start menu with Press Space to Start

Score display in real-time

Smooth movement using Pygame clock

Snake grows when eating apple

Restart game after Game Over

Modular code design for readability

🧠 Future Improvements

Add sound effects when eating apple

High score system

Snake skins or graphical improvements

Multiple levels or obstacles
Author

Nguyen Chi Phuc, 2025
