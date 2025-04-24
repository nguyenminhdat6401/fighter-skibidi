# Fighter Skibidi 7 VVVVV
Fighter Skibidi
Fighter Skibidi is a 2D fighting game built with Python and Pygame. It features multiple game modes including Player vs Player (PvP), Player vs Environment (PvE), and Adventure mode, where players can battle opponents with various characters and abilities across different maps. The game includes dynamic animations, sound effects, and a user-friendly interface with menus for character and map selection.
Features

Multiple Game Modes: Choose between PvP, PvE, or Adventure mode.
Character Selection: Pick from five unique fighters, each with distinct animations for idle, run, attack, block, and more.
Map Variety: Fight in five different environments, including Arena, Sunset, Temple, Beach, and New York.
Adventure Mode: Progress through levels with increasing difficulty, facing waves of enemy minions.
Interactive Menus: Navigate through a main menu, settings, rules, and selection screens with mouse and keyboard support.
Sound Effects and Music: Immersive audio with background music, punch, click, and strain sound effects.
Pause Menu: Pause the game to continue, adjust settings, or exit to the main menu.

Installation
Prerequisites

Python 3.8 or higher
Pygame library (pip install pygame)

Steps

Clone or download the repository to your local machine.
Ensure all required sprite and sound files are in the sprites2 and font directories as referenced in the code (e.g., sprites2/c1idle0.png, font/musicbr.mp3).
Install the required dependencies:pip install pygame


Run the game:python fighter_skibidi.py



Note: The game assumes the presence of specific image and sound files (e.g., sprites2/logo.png, font/punch.mp3). Ensure these files are correctly placed in the project directory or update the file paths in the code if necessary.
Gameplay

Controls:
Player 1: 
Move: A/D (left/right), W/S (fly up/down), K (jump), J (attack), I (special attack), S (block), L (dash), U (strain), WW (fly).


Player 2 (PvP): 
Move: Left/Right, Up/Down (fly), KP2 (jump), KP1 (attack), KP5 (special attack), Down (block), KP3 (dash), KP4 (strain), UpUp (fly).


Pause: Press ESC or click the pause button to access the pause menu.


Objective:
In PvP/PvE, reduce the opponent's health to zero or have more health when the timer runs out.
In Adventure mode, defeat all enemy waves in each level to progress.


Settings: Adjust music and game volume via the settings menu.

Project Structure

fighter_skibidi.py: Main game script containing all game logic, UI, and mechanics.
sprites2/: Directory for character sprites, backgrounds, and effects (e.g., c1idle0.png, background.png).
font/: Directory for fonts and sound files (e.g., font0.otf, musicbr.mp3).

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make your changes and commit (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature).
Open a pull request.

Please ensure your code follows the existing style and includes appropriate comments. Report bugs or suggest features via the Issues tab.
License
This project is licensed under the MIT License. See the LICENSE file for details.
Acknowledgments

Built with Pygame, a powerful library for 2D game development in Python.
Inspired by classic 2D fighting games with a modern twist.

