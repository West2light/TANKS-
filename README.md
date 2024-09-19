![image](https://github.com/user-attachments/assets/479080f0-82c4-47cc-ba0e-d2a62f49b191)
# TANKS - 3D Two-Player Desert Battle Game

Welcome to **TANKS**, a simple 3D tank battle game built in Unity, set in the desert. This game supports two-player local multiplayer where players control tanks, trying to destroy each other using strategic movement and shooting.

## Game Overview

In **TANKS**, each player controls a tank on a desert battlefield. The goal is to destroy the opponent's tank by hitting them with shells while avoiding their fire. The game is fast-paced, and the desert terrain offers obstacles to hide behind, creating strategic opportunities for attack.

### Features

- **Two-player local multiplayer** on the same keyboard.
- **Desert environment** with dynamic obstacles and terrain.
- **Basic tank controls**: movement and shooting mechanics.
- **Tank health system**: Each tank has a limited amount of health.
- **Destructible environment**: Some objects in the desert can be destroyed by shells.
- **Simple 3D graphics** optimized for smooth gameplay.

## Controls

### Player 1 (Blue Tank)
- **Move**: `W`, `A`, `S`, `D` keys.
- **Shoot**: Press the `Spacebar` to fire a shell.

### Player 2 (Red Tank)
- **Move**: Arrow keys (`↑`, `↓`, `←`, `→`).
- **Shoot**: Press the `Enter` key to fire a shell.

### Objective

- Each player aims to destroy the opponent's tank by hitting them with shells. The game ends when one tank’s health reaches zero, and the remaining tank is declared the winner.

## Getting Started

### Prerequisites

- Unity version 2021.3.x or later.
- Basic knowledge of Unity and C# scripting.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/TANKS-3D-Desert-Battle.git

2. Open the project in Unity:
   - Launch Unity Hub, select **Open**, and navigate to the project directory.

3. Once the project is loaded, click the **Play** button in Unity's editor to start the game.
- **Assets/**
  - **Scripts/**: Contains the game logic scripts, such as player movement, shooting, health management, and game state control.
  - **Prefabs/**: Includes prefabs for tanks, shells, and other environmental objects.
  - **Scenes/**: Contains the main game scene set in a desert environment.
  - **Materials/**: Includes textures and materials used for the tanks and desert terrain.
  - **Audio/**: Holds sound effects for shooting, explosions, and ambient desert sounds.
  - **UI/**: Contains the in-game UI elements, including health bars and score tracking.

## Future Features

- Add more power-ups (e.g., speed boosts, extra damage).
- Create new desert environments with different layouts and obstacles.
- Implement AI tanks for single-player mode.
- Add visual effects (dust, smoke) and enhanced particle effects for explosions.
