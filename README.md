# Endless Road Runner in C

A **Crossy Road**-inspired terminal game developed in **C** as a first-semester university project.

## Overview

Crossy Road is a simple terminal-based game where the player controls a frog attempting to cross a series of roads, avoiding cars, trees, and a chasing stork. The game is built using **C** and utilizes the **PDCurses library** for terminal rendering.

## Features

- **3-level gameplay**: Progress through 3 levels by reaching the end of each.
- **Obstacles**: Increasing difficulty over time, friendly and enemy cars.
- **Simple controls**: Use the keyboard to navigate.
- **Time tracking**: Saves high scores to a leaderboard.

## Controls

- **Arrow keys**: Move the player up, down, left, and right.
- **Esc**: Exit the game.

## Project Structure

```
endless-road-runner-c/       # Root project folder
├── CrossyRoad/              # Game folder
│   ├── CrossyRoad.c         # Main game logic
│   ├── CrossyRoad.vcxproj   # Visual Studio project file
│   ├── CrossyRoad.vcxproj.filters # Visual Studio project filters
│   ├── config.txt           # Game settings
│   ├── curses.h             # PDCurses header file
│   ├── game_state.txt       # Game progress saves
│   ├── leaderboard.txt      # High scores storage
│   └── pdcurses.lib         # PDCurses library file
├── .gitignore               # Git ignored files
├── .gitattributes           # Git attributes
└── README.md                # Project documentation
```

## License

This project is open source, and licensed under the MIT License, see the [LICENSE](LICENSE) file for details.

