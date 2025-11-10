# Aero Dash — Canvas Edition

## Overview
**Aero Dash** is a 2D arcade-style **falling-block dodger game** built using **HTML5 Canvas and JavaScript**.  
The goal is to move the spaceship catcher to **collect green blocks** and **avoid red blocks**.  
The game becomes progressively harder as the falling speed and spawn rate increase over time.

This project demonstrates:
- Rendering and animation using the **Canvas 2D API**
- **Keyboard and touch-input controls**
- **Moveable objects** with collision detection
- **Score tracking** and **Best Score** persistence with `localStorage`
- A clear **game loop** driven by `requestAnimationFrame()`

---

## How to Run the Game
1. Download or clone the repository.
2. Open the project folder in **VS Code**.
3. Open `index.html` in a browser:
   - Recommended: Right-click → **Open with Live Server** (VS Code extension).

---

## Controls

| Action | Keys / Input |
|-------|--------------|
| Move Left / Right | **A** / **D** or **←** / **→** |
| Move Up / Down | **W** / **S** or **↑** / **↓** |
| Touch / Mobile Control | **Drag** finger on the canvas to move the ship |
| Start / Restart Game | Press **Enter** or click **Start** |

---

## Game Features

| Feature | Description |
|--------|-------------|
| Canvas Rendering | The ship, falling blocks, background, and UI are drawn using the Canvas API. |
| Player Movement | Smooth continuous movement using keyboard or touch-drag input. |
| Falling Blocks | Randomized spawn timing, speed, and block types. |
| Collision Detection | Checks overlap between the player's hit area and each block. |
| Score System | Green blocks increase score. Red blocks end the game. |
| Difficulty Scaling | Spawn rate gradually increases, making the game harder. |
| Best Score Saving | Highest score is stored using `localStorage` and loads automatically. |

---

## Repository
https://github.com/RLTB-Rommel/aero_dash

---

## Learning Reflection
Through this project, I learned how to:
- Use the HTML5 Canvas API for rendering animated objects.
- Structure a real-time **game loop** using `requestAnimationFrame()`.
- Handle **keyboard and touch input** smoothly.
- Implement **collision detection** and dynamic difficulty scaling.
- Use `localStorage` to maintain persistent game data across sessions.

This experience helped strengthen my understanding of interactive graphics, game logic structure, and responsive input handling.

---

## (Optional for Submission) Gameplay Video Link
*([https://youtu.be/1xJGOuOUxfc])*