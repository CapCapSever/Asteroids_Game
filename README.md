# Asteroids Game

A classic Asteroids arcade game built with Python and Pygame.
I didn't vibecode this for real guys, this is my real effort eventhough it is not that great ^^

## Controls

| Key | Action |
|-----|--------|
| W / S | Move forward / backward |
| A / D | Rotate left / right |
| SPACE | Shoot |

## Setup

```bash
uv sync
```

## Running

```bash
uv run python main.py
```

## Requirements

- Python 3.13+
- [uv](https://github.com/astral-sh/uv)
- pygame 2.6.1

## Project Structure

```
├── main.py            # Game loop and entry point
├── constants.py       # Game constants (speeds, sizes, etc.)
├── circleshape.py     # Base class for circular game objects
├── player.py          # Player ship (triangle)
├── asteroid.py       # Asteroid objects (split into smaller ones)
├── asteroidfield.py  # Spawns asteroids from screen edges
├── shot.py           # Projectile fired by player
└── logger.py         # State/event logging for debugging
```
