# 🐍 Snake AI Demo

## Overview

**Snake AI Demo** is a modern version of the classic Snake game, built with **Python** and **Pygame**.  
This project demonstrates how a simple AI agent ⚡ can automatically control the snake to eat apples 🍎 while avoiding walls and its own body.

- Grid-based gameplay on a 20x20 board
- Apples 🍎 spawn in a safe zone, avoiding corners and edges for smoother AI performance
- The snake 🐍 grows longer after eating apples
- Game ends if the snake 🐍 hits the wall 🧱 or itself

---

## Features

### 1. AI-Controlled Snake ⚡
- **Greedy path selection**: AI moves the snake 🐍 in the direction that reduces the distance to the apple 🍎
- **Collision avoidance**: prevents hitting walls 🧱 or the snake’s body 🐍
- **Fallback logic**: if the preferred path is blocked, AI selects an alternative safe direction
- Demonstrates how a simple AI ⚡ can outperform human players

### 2. Manual Play 🎮
- Control the snake 🐍 using arrow keys
- Press **Space 🔄** to restart after game over
- Real-time score ⭐ display on the screen

---

## Installation 🛠️

1. Ensure **Python 3.x** is installed  
2. Install Pygame:

```bash
pip install pygame
