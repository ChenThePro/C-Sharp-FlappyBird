# 🐤 FlappyBird (Unity - C#)

> **A Unity Remake of the Classic Flappy Bird Game**

---

## 🧭 Table of Contents

- [Introduction](#-introduction)
- [Features](#-features)
- [Technology Stack](#-technology-stack)
- [Installation](#-installation)
- [Usage](#%EF%B8%8F-usage)
- [Visuals](#%EF%B8%8F-visuals)
- [Game Overview](#-game-overview)
- [Code Structure](#-code-structure)
- [Credits](#-credits)
- [Contributors](#-contributors)
- [License](#-license)

---

## 📘 Introduction

**FlappyBird** is a Unity-based clone of the classic mobile game, developed as part of a self-learning journey into game development using **C#** and modern **game engines** like **Unity** and **Unreal Engine**.

This project was a hands-on experiment in understanding how 2D games are built — from scripting physics and input, to handling collisions, animations, and scoring.

> _"I had a blast building this! It was fun experimenting with Unity, learning about components, the scene editor, game objects, and scripting logic in C#."_

---

## ✨ Features

- 🎮 Fully playable Flappy Bird clone
- 🚀 One-button control with real-time physics
- 💥 Collision detection with ground and pipes
- 🏆 Score display and high-score tracking
- 🌄 Seamless scrolling backgrounds
- 🔊 Sound effects and game feedback

---

## 🛠 Technology Stack

| Component         | Tool / Language     |
|------------------|---------------------|
| Engine           | Unity (2021 or newer) |
| Language         | C#                  |
| Physics & Input  | Unity built-in      |
| Audio            | Unity Audio Sources |
| UI               | Unity UI System     |
| Tutorial Source  | Game Maker's Toolkit (YouTube)

---

## 💾 Installation

### Requirements

- Unity Hub and Unity Editor (2021.x or compatible)
- Git (optional, for cloning)
- Compatible platform: Windows, macOS, or Linux

### Setup

This repository is dedicated solely to the project's scripts. The full project can be found at the source repository here.
[Game Maker's Toolkit repository](https://github.com/Britishgaming/GMTK-Unity-Tutorial)

```bash
# Clone the repository
git clone https://github.com/Britishgaming/GMTK-Unity-Tutorial
```
1. Open Unity Hub.
2. Click **Open Project** and select the cloned folder.
3. Press **Play** in the Unity Editor to start the game.

---

## ▶️ Usage

- Press **Spacebar** or tap the screen to make the bird flap.
- Avoid hitting the pipes or the ground.
- Try to beat your high score every time you play!

---

## 🖼️ Visuals

![Gameplay](assets/screenshots/game.png)
![Game Over](assets/screenshots/lose.png)

---

## 🎮 Game Overview

- The bird continuously falls due to gravity.
- Pressing the **space key** makes it flap upward.
- Pipes are generated at intervals and scroll toward the player.
- Hitting a pipe or the ground ends the game.

---

## 🧠 Code Structure

| Script Name       | Description                                 |
|------------------|---------------------------------------------|
| `Bird.cs`         | Handles gravity, input, and collision logic |
| `PipeSpawner.cs`  | Spawns pipes at regular intervals           |
| `Pipe.cs`         | Moves pipes and destroys off-screen ones    |
| `GameManager.cs`  | Manages game states (start, end, restart)   |
| `ScoreManager.cs` | Tracks and displays the player's score      |

---

## 🙌 Credits

- **Tutorial Source**: [Game Maker's Toolkit on YouTube](https://www.youtube.com/@GMTK)
- **Inspiration**: The original *Flappy Bird* by .GEARS Studio

---

## 👨‍💻 Contributors

- **Chen Shor** – Developer  
  Built for fun and learning game development in Unity and C#

---

## 📄 License

**MIT License**  
This project is open for educational and personal use. Attribution is appreciated.
