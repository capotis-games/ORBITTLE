# 🌀 ORBITTLE

> **Everything moves. Nothing behaves.**

ORBITTLE is a 2D puzzle-physics game where you don't directly control the main character.

**You control gravity.**

Change the direction of gravity to guide Bitt through increasingly challenging rooms filled with physics, switches, boxes, portals, orbit mechanics and chaotic interactions.

---

## 🎮 About the Game

In ORBITTLE, Bitt is affected by the environment and by the direction of gravity.

Instead of moving Bitt directly, you change gravity between four directions:

- ⬆️ Up
- ⬇️ Down
- ⬅️ Left
- ➡️ Right

Use gravity to:

- Move Bitt around each room
- Push and move objects
- Activate switches
- Open doors
- Reach the exit
- Collect stars
- Use portals
- Interact with Orbit Cores
- Solve physics-based puzzles

Every room is designed as a small standalone challenge.

Sometimes the solution is simple.

Sometimes changing gravity once completely changes everything.

---

# ⭐ Features

- 🌀 Gravity-based gameplay
- 🧩 Physics-based puzzles
- 🎯 Skill-based challenges
- ⭐ Collectible stars
- 📦 Interactive physics objects
- 🔘 Switches and doors
- 🪐 Orbit Core mechanics
- 🌀 Teleportation portals
- 🟢 Slime mechanics
- 🚀 Moving platforms
- 💥 Chaotic physics interactions
- 🌪️ Chaos Mode
- 💾 Local save system
- 🎮 Keyboard controls
- 📱 Mobile controls
- 🌈 Colorful cartoon-style visuals
- 🔊 Game audio and sound effects
- 🌍 Multiple worlds and levels

---

# 🌎 Worlds

ORBITTLE is designed around several worlds, each introducing new mechanics.

### WORLD 1 — LEARNING TO FALL

Learn the basics of gravity and movement.

### WORLD 2 — BOUNCE

Physics become more important.

### WORLD 3 — ORBIT

Discover Orbit Cores and orbital movement.

### WORLD 4 — PORTALS

Use teleportation to solve more complex rooms.

### WORLD 5 — CHAOS

Multiple mechanics collide.

---

# ⭐ Level System

Each level can contain up to three stars:

- ⭐ Complete the level
- ⭐ Complete it using fewer gravity changes
- ⭐ Collect all physical stars

Your progress is saved locally.

---

# 🌪️ Chaos Mode

Chaos Mode combines different gameplay modifiers and room elements to create unpredictable challenges.

Possible modifiers include:

- BOUNCY
- SLOW GRAVITY
- TURBO
- DOUBLE ORBIT
- SLIPPERY
- HEAVY BOXES

Each run can provide a different challenge.

---

# 🎮 Controls

## PC / Mac

| Action | Control |
|---|---|
| Gravity Up | `W` / `↑` |
| Gravity Down | `S` / `↓` |
| Gravity Left | `A` / `←` |
| Gravity Right | `D` / `→` |
| Restart | `R` |
| Pause | `ESC` |

## Mobile

ORBITTLE includes an on-screen directional control system designed for touchscreens.

---

# 🧪 Beta

**ORBITTLE is currently in Beta.**

The game is still under development, so you may encounter:

- Bugs
- Performance problems
- Incomplete features
- Temporary placeholder content
- Changes to gameplay
- Levels that are still being balanced

Some platforms may have compatibility or performance issues during the Beta.

If you encounter a problem, please report it through the project's issue tracker.

---

# 🛠️ Built With

- **Godot 4.7**
- **GDScript**
- 2D physics
- Godot UI system
- Godot animation system

No external game engine plugins are required.

---

# 💻 Running the Project

## Requirements

- Godot **4.7**
- A computer capable of running Godot 4.7

## Open the project

1. Clone or download this repository.
2. Open Godot 4.7.
3. Select **Import**.
4. Select the project's `project.godot`.
5. Open the project.
6. Press **Play**.

---

# 📁 Project Structure

```text
ORBITTLE/
│
├── project.godot
├── README.md
│
├── scenes/
│   ├── main/
│   ├── menus/
│   ├── levels/
│   ├── objects/
│   └── ui/
│
├── scripts/
│   ├── managers/
│   ├── objects/
│   ├── player/
│   ├── levels/
│   └── ui/
│
├── data/
│
├── audio/
│
├── shaders/
│
└── localization/
