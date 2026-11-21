# 🧟 Top-Down Zombie Survival Shooter

![Python](https://shields.io)
![Pygame](https://shields.io)
![Genre](https://shields.io)
![Platform](https://shields.io)

**Name:** Samanta Rahman  
**Student ID:** 11230321566  

---

## 🎮 1. Game Overview
**Top-Down Zombie Survival Shooter** is a 2D action survival game developed using Python and Pygame. The player is placed in a dangerous arena where zombies attack from all four directions. Players must move around, aim with the mouse, and shoot down approaching zombies to survive as long as possible and achieve the highest score.

---

## 🎯 2. Game Objectives
- Survive as long as possible against endless zombie waves.
- Eliminate zombies by shooting them to earn points.
- Avoid direct physical contact with zombies to protect player health.
- Survive increasingly difficult levels as zombie speed and spawn rates rise.
- Beat the saved high score.

---

## 🕹️ 3. Controls & Gameplay

| Key / Input | Action |
| :--- | :--- |
| **W / A / S / D** | Move the player Up, Left, Down, and Right |
| **Mouse Movement** | Aim the weapon in 360 degrees |
| **Left Mouse Click** | Shoot bullets towards zombies |
| **SPACE** | Start the game from the Start Menu |
| **P** | Pause or Resume the game |
| **R** | Restart the game after Game Over |
| **ESC** | Quit / Exit the game |

---

## ⚔️ 4. Core Gameplay Mechanics
- **Player Movement:** The player moves smoothly in four directions inside the 800x600 graphical window boundaries.
- **Shooting System:** Using trigonometry (`atan2`), the gun barrel rotates smoothly toward the mouse pointer and fires bullets on left click.
- **Zombie AI Behavior:** Zombies spawn randomly from the top, bottom, left, and right edges of the screen and continuously chase the player.
- **Collision Detection:** Uses Euclidean distance (`math.hypot`) to detect bullet hits on zombies (increasing score) and zombie attacks on the player (reducing health).
- **Health Management:** The player starts with 100 health points displayed on a live health bar; when health reaches zero, the game ends.

---

## 🚀 5. Game Features
- Interactive 2D graphical window built with Python Pygame.
- Keyboard-controlled player movement and mouse-controlled aiming/shooting.
- Multiple zombie spawn directions with intelligent chasing behavior.
- Real-time bullet movement and circular collision detection system.
- Dynamic health bar above the player and live Score & Level tracking.
- Progressive difficulty levels (zombie speed and spawn rate increase over time).
- Start Menu with clear on-screen instructions.
- Pause (`P`) and Resume functionality.
- Game Over screen with Final Score, Restart (`R`), and Exit (`ESC`) options.
- Persistent High Score storage using a text file (`highscore.txt`).

---

## 💻 6. Technologies & Tools

| Technology / Tool | Purpose |
| :--- | :--- |
| **Python 3** | Main programming language |
| **Pygame** | 2D graphics rendering, window management, and input handling |
| **Math Module** | Calculating aiming angles, movement vectors, and distances |
| **Random Module** | Spawning zombies at random border coordinates |
| **File Handling** | Saving and loading high scores locally (`highscore.txt`) |
| **VS Code** | Development environment |
| **GitHub** | Version control and project hosting |

---

## 🧠 7. Computer Graphics Concepts Implemented
- **2D Coordinate System:** Positioning and translating objects across the `(x, y)` screen plane.
- **Rendering:** Drawing the player, zombies, bullets, and health bar using geometric primitives (`circle`, `line`, `rect`).
- **Animation:** Continuous movement of zombies and bullets through a frame-based game loop.
- **Vector Mathematics:** Calculating movement direction and normalizing diagonal movement speed.
- **Distance Calculation:** Measuring Euclidean distance between circular objects.
- **Collision Detection:** Detecting interactions between bullets, zombies, and the player.

---

## 🖼️ 8. Game Screenshots

### Start Menu
![Start Menu](screenshots/start-menu.png)

### Gameplay
![Gameplay](screenshots/gameplay.png)

### Game Over
![Game Over](screenshots/game-over.png)
