# Space Shooter Game

## **Description**

*Space Shooter* is a thrilling arcade-style game developed with Pygame. Players pilot a spaceship to fend off waves of enemy ships, aiming to survive and achieve the highest score. The game incorporates strategic shooting, dodging enemy lasers, and managing health to progress through increasingly challenging levels.

---

## **Features**

- **Player Controls**: Smooth spaceship movement and laser shooting using keyboard inputs.
- **Enemy Waves**: Dynamic enemy spawning with varied ship types and behaviors.
- **Scoring System**: Tracks player progress and achievements based on performance.
- **Health and Lives**: Visual health bars and life counters to monitor player status.
- **Sound Effects**: Engaging laser and explosion sound effects enhance gameplay.
- **Background Music**: Immersive soundtrack for an exciting experience.
- **Increasing Difficulty**: Progressive challenge with faster and tougher enemies.

---

## **Requirements**

- Python 3.x
- Pygame library

---
## **Code Structure**

- **`game.py`**: Main script containing the game loop, event handling, and rendering logic.
- **Classes**:
  - **`Ship`**:
    - Base class for all ships (player and enemies).
    - Manages properties such as health, movement, and shooting.
  - **`Player`**:
    - Inherits from `Ship`.
    - Adds features like a health bar and enhanced shooting capabilities.
  - **`Enemy`**:
    - Inherits from `Ship`.
    - Implements unique movement patterns and behaviors for enemy ships.
  - **`Laser`**:
    - Manages laser properties, including movement, collision detection, and rendering.
