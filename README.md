<div align="center">

# GTS

### Open World Third Person Action Game for Android

![Godot](https://img.shields.io/badge/Engine-Godot%204.6.1-478CBF?style=flat-square&logo=godotengine&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=flat-square)

</div>

<br>

![Gameplay](Assets/Images/1.jpg)

GTS is a third person open world action game built entirely from scratch in Godot Engine, designed and optimized specifically for Android. Every core system — the world, the character, the controls, the camera, the performance — has been built and tuned by hand.

<br>

## The City

A multi-zone urban environment built from modular street blocks, with dynamic lighting and real-time shadows. The world is split into independent zones rather than one large scene, so it can scale as new areas are added.

![City Environment](Assets/Images/2.jpg)

<br>

## The Character

A fully rigged character driven by a layered animation system using AnimationPlayer and AnimationMixer. Movement, jumping, running, and combat reactions blend smoothly into one another instead of snapping between states.

![Character](Assets/Images/3.jpg)

<br>

## Touch Controls

A complete custom input system built for mobile from the ground up — a virtual joystick for movement and dedicated touch buttons for run, jump, and combat, tuned to feel responsive on different screen sizes.

![Touch Controls](Assets/Images/4.jpg)

<br>

## Camera and HUD

A SpringArm3D camera keeps the player framed and collision-aware at all times. The HUD includes a live minimap so the player always has spatial awareness while moving through the city.

![HUD and Minimap](Assets/Images/5.jpg)

<br>

## Tech Stack

- Engine: Godot Engine 4.6.1
- Scripting: GDScript
- Rendering: Forward+ Mobile Pipeline
- Animation: AnimationPlayer, AnimationMixer
- Camera: SpringArm3D
- Input: Custom Virtual Joystick, TouchScreenButton
- Physics: CollisionShape3D
- Optimization: Custom Performance Manager

<br>

## Project Structure

The player is a self-contained scene combining the rig, collider, camera, and animation controller. The city is split into independent zone scenes connected through a central control layer, allowing new districts to be added without affecting existing ones. UI and HUD logic are kept separate from world logic, keeping them portable across scenes.

<br>

## Roadmap

- Combat system and enemy AI
- Mission structure and story progression
- New city zones and landmarks
- Expanded combat animation set
- Save and progression system

<br>

## Team

**Developer:** Paras Sharma
**Team:** Zerox Team

<br>

<sub>GTS is in active development. This README will be updated as the project grows.</sub>
