🎮 Python Platformer

A 2D platformer game built with Python and Pygame, based on the Tech With Tim Python Platformer tutorial and heavily expanded with custom mechanics, multiple levels, enemies, and a full progression system.


About

This started as a simple platformer tutorial and grew into a full 5-level game with progressive difficulty, a coin-collection scoring system, multiple enemy types, and a proper win/lose flow — complete with a confetti celebration screen on completion.


Features

5 unique levels, each larger and harder than the last
Level-specific backgrounds — every level has its own visual theme
Progressive difficulty — enemy count and speed increase each level:

Level 1: Fire traps + Saw
Level 2: More fire + saws
Level 3: + Swinging spike balls + static spikes
Level 4: + Rock Head enemies
Level 5: All enemy types combined, fastest speeds



Coin collection system — 20 coins per level, collect at least 15 to unlock the level exit (flag)
Score tracking — 10 points per coin, carried across the whole game
3 lives per playthrough — falling into a pit or touching an enemy costs a life and restarts the current level
Game Over / Win screens — lose all lives and it's game over; beat Level 5 and get a full-screen confetti celebration
Fullscreen gameplay with double-jump platforming controls


Requirements

. Python 3.12 (Pygame is not yet compatible with Python 3.13+/3.14)
. Pygame 2.6.1


Project Structure

├── tutorial.py    

├── assets/      

│   ├── Background/

│   ├── MainCharacters/

│   ├── Items/

│   ├── Terrain/

│   ├── Traps/

│   └── Other/

└── README.md


Credits

Base tutorial and original assets by Tech With Tim
Expanded gameplay, multi-level system, enemies, scoring, and UI by this project





