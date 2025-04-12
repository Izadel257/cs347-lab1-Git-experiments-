# Shot'm

This is our plan for the game we named `Shot'm`, a 2D platformer shooting game

## Learning Goals

1. General Game Dev Concepts:
- Understand 2D game physics (collisions, gravity, movement)
- Learn about game loops, frame updates, and delta time
- Master state management for enemies, levels, and player actions

2. whatEngine-Specific:

We will be using Godot (GDScript) because it is open source and supports a lot more languages than Unity.
Goals:
- Understand GDScript syntax and Godot node system
- Learn how signals and scenes work
- Get comfortable with Godot’s built-in animation and physics systems
3. Asset & Art:
- Basic pixel art or sprite editing (Krita, GIMP)
- Efficient asset sourcing and attribution (OpenGameArt.org, Pixabay)

## Core Features

1. Player Mechanics:
- Move (left/right), jump (with gravity), shoot (in direction)
- Health and damage system
- Weapon upgrades / power-ups

2. Enemy System:
- Basic AI (follow player, patrol, shoot)
- Multiple enemy types with different health and speed

3. Level System:
- Scene-based or dynamically loaded levels
- Level completion (goal point or defeat all enemies)
- Difficulty progression: enemies, hazards, terrain complexity (might remove terrain complexity and simplify the game a lot more)
4. Extras (If we have time):
- UI: health bar, ammo count, level indicator
- Pickups: health, ammo, speed boost, new weapons
- Save/load level progress
- Audio (background music, SFX for shooting, enemies, jumps)


## Architecture Plan

GameManager
 - UI
 - Player
 - Enemies
 - LevelManager
 - Pickups

### Systems Breakdown:
- Input System – movement, jump, shoot
- Physics & Collision – ground detection, enemy hits, pickups
- Enemy AI – finite state machines (patrol, chase, attack) 
- Health Manager – for both player and enemies
- Level Manager – tracks level number, load/transition
- Game Manager – overall state, UI updates, game loop
- Audio Manager – handles SFX and music (This is an extra)

## Development Strategy

We are counting weeks from week 3 (so week 1 is technically week 3)
Phase 1 – Setup & Core Mechanics (Week 1–2)

✅ Choose engine: Godot
- Set up project structure, player prefab/scene
-  Implement player movement and shooting
- Basic ground + platforms + collisions
- Set up one enemy with basic movement & collision detection
Phase 2 – Game Logic & Systems (Week 3–4)

- Implement health system for player and enemies
- Build AI states (patrol, chase, attack)
- Add hitboxes, enemy projectiles, damage
- Add pickups and power-ups (health boost, weapon change)
Phase 3 – Level Design & Progression (Week 5–6)

- Build multiple levels using tilemaps
- Add increasing difficulty (more enemies, faster projectiles, traps)
- Create transitions between levels
Phase 4 – Polish & Presentation (Week 7–8)

- Add visual and sound effects
- Add main menu, pause screen, win/lose screens
- Save/load system (optional)
- Playtesting, feedback, bug fixes

## Worries

1. None of us is familiar with the technology. It is going to be a new experience for the both of us but really exciting

## Communication
It is just me and Reece and we talk a lot on the phone and in person. We are planning on meeting at the very least once every week, in person. 
