# GTS

An open-world third-person action game built with Godot Engine, designed and optimized for Android devices.

![Gameplay](Assets/1.jpg)

## Overview

GTS is a mobile-first 3D action game developed from the ground up using Godot Engine 4.6.1. The project combines a fully custom character system, mobile touch controls, urban environment design, and performance-focused architecture to deliver a smooth open-world experience on Android hardware.

## Features

### World Design
The game world is structured as a multi-zone open city, composed of modular street sections (Part 1 City, City2, City3) connected through a central scene management system. The environment includes dynamic lighting, real-time shadows, and a stylized urban setting with detailed building geometry and street-level art.

![City Environment](Assets/2.jpg)

### Character System
The player character is built on a fully rigged 3D skeleton with a complete animation pipeline driven by AnimationPlayer and AnimationMixer. Locomotion, combat, and reaction animations are blended for fluid transitions between states, including running, jumping, and melee actions such as punch and head hit responses.

![Character Controller](Assets/3.jpg)

### Mobile Controls
A custom touch input system replaces traditional controllers, built around a virtual joystick for movement and dedicated touch screen buttons for run, jump, and combat actions. The control layout is designed for responsiveness and clarity on a wide range of screen sizes.

![Touch Controls](Assets/4.jpg)

### Camera and Physics
A SpringArm3D-based third-person camera system provides smooth, collision-aware framing of the player character at all times. Physics interactions are handled through a dedicated CollisionShape3D setup, ensuring accurate movement and interaction with the environment.

### Performance Optimization
A dedicated Performance Manager script governs runtime optimization, allowing the game to maintain stable frame rates across a range of Android devices despite the complexity of the open-world environment.

### Heads-Up Display
The in-game HUD integrates a real-time minimap alongside core gameplay indicators, giving players constant spatial awareness as they navigate the city.

![HUD and Minimap](Assets/5.jpg)

## Technical Stack

| Component | Technology |
|---|---|
| Engine | Godot Engine 4.6.1 |
| Scripting | GDScript |
| Platform | Android |
| Rendering | Godot 3D (Forward+ Mobile) |
| Animation | AnimationPlayer, AnimationMixer |
| Camera | SpringArm3D |
| Input | Virtual Joystick, TouchScreenButton |

## Architecture

The project follows a modular scene-based architecture. The player scene encapsulates the character rig, collision shape, camera system, and animation controller as independent, reusable components. The world is split into discrete city sections loaded and managed through a central control scene, allowing for scalable level design as the project grows. UI and gameplay logic are kept separate from world geometry, with the HUD and control scenes operating independently of the environment scenes.

## Roadmap

Development is ongoing, with the following systems planned for upcoming releases:

- Combat mechanics and enemy AI
- Mission and storyline progression
- Expanded city zones and points of interest
- Additional character animations and combat states
- Save and progression system

## Team

**Developer:** Paras Sharma
**Team:** Zerox Team

## License

This project is currently in active development. Licensing details will be added in a future update.
