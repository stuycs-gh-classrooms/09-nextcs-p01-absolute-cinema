[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/PX83n--N)
# NeXtCS Project 01
### Name0: Derek Yang
### Name1: Seongjae Oh
---

### Overview
Your mission is create either:
- Life-like cellular automata [life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life), [life-like](https://en.wikipedia.org/wiki/Life-like_cellular_automaton), [demo](https://www.netlogoweb.org/launch#https://www.netlogoweb.org/assets/modelslib/Sample%20Models/Computer%20Science/Cellular%20Automata/Life.nlogo).
- Breakout/Arkanoid [demo 0](https://elgoog.im/breakout/)  [demo 1](https://www.crazygames.com/game/atari-breakout)
- Space Invaders/Galaga

This project will be completed in phases. The first phase will be to work on this document. Use markdown formatting. For more markdown help [click here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) or [here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)


---

## Phase 0: Selection, Analysis & Plan

#### Selected Project: Geometric Shape Invaders

### Necessary Features
What are the core features that your program should have? These should be things that __must__ be implemented in order to make the program useable/playable, not extra features that could be added to make the program more interesting/fun.

- Movable enemies
- Movable player
- Movable projectiles
- Killable enemies
- Point system

### Extra Features
What are some features that are not essential to the program, but you would like to see (provided you have time after completing the necessary features. Theses can be customizations that are not part of the core requirements.

- EXP system
- Upgrades
- Player moves in all directions
- Enemies moves in all directions
- Multiple abilities
- Screen to rebind keystorkes to different abilities
- 

### Array Usage
How will you be using arrays in this project?

1D Array:
- Store bullets, enemies, other stuff currently on screen

2D Array:
- Work in progress


### Controls
How will your program be controlled? List all keyboard commands and mouse interactions.

Keyboard Commands:
- WASD to Move
- QERF for abilities
- Space to Pause/Resume

Mouse Control:
- Mouse movement: Points your ship in that direction
- Mouse pressed: Fire


### Classes
What classes will you be creating for this project? Include the instance variables and methods that you believe you will need. You will be required to create at least 2 different classes. If you are going to use classes similar to those we've made for previous assignments, you will have to add new features to them.

ALIEN
- Instance variables:
  - alienType
  - maxHealth
  - curHealth
  - power
  - xChange
  - yChange
  - xPos
  - yPos
  - hitboxDiameter
- METHODS
  - decreaseHealth(int dmg)
  - move()

PLAYER
- Instance variables:
  - maxHealth
  - curHealth
  - array for unlocked abilities
  - array for cooldowns
  - xPos
  - yPox
  - hitboxDiameter
- METHODS
  - fire()
  - decreaseHealth(int dmg)
