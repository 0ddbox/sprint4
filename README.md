# Sprint 4
# Game Sound Effects – OOP Project

## Overview
This repository contains original sound effects created for our game project developed during our Object-Oriented Programming (OOP) course. The game was built using Java and LibGDX, with a focus on modular code, reusable components, and a cohesive audiovisual experience.

## Sound Files

| File Name                     | Description                                          |
|------------------------------|------------------------------------------------------|
| `menu selection 2.wav`       | A subtle highlight sound used when hovering/selecting in menus. |
| `selection 3.wav`            | A variation for selection to add audio diversity.   |
| `menu closing noise.wav`     | Plays when exiting or closing the menu interface.   |
| `save game.wav`              | A confirmation tone that signals successful saving. |
| `collision or wrong choice.wav` | Indicates invalid input or blocked interaction.  |
| `collision 2.wav`            | Secondary collision sound for variety and impact.   |

## How They Were Made
All sounds were created using **FL Studio**, a professional digital audio workstation. Each effect was custom-designed using layered instruments, automation clips, filters, and effects to create a consistent sound theme suited to the game's fantasy atmosphere.

- **Menu sounds**: Built with soft synths and precise volume envelopes to ensure clean, unobtrusive interaction feedback.
- **Collision sounds**: Designed using percussion samples and distortion effects for clear error signaling.
- **Save game tone**: Carefully shaped to feel conclusive and satisfying, confirming a successful action.

The sounds were exported and normalized to game-ready formats, keeping file size efficient while preserving clarity.

## Relevance to OOP Design
The integration of sound in our project demonstrates core Object-Oriented Programming principles:

- **Encapsulation**: Each sound effect is managed through a `SoundEffect` class that controls playback behavior.
- **Reusability**: A centralized `SoundManager` class loads and reuses sounds across different parts of the game.
- **Modularity**: Sounds can be changed or extended without altering unrelated parts of the codebase.
- **Feedback Loop**: Audio plays a key role in reinforcing user interactions and enhancing the overall experience.

By treating sound effects as modular objects in the codebase, we maintained clean design and flexibility while enhancing the playability and polish of the game.

## Credits
Sound design and production by Liam McSeveney  
Graphics & Sound Team – CR Java Game Development, Spring 2025  
Created in **FL Studio**
