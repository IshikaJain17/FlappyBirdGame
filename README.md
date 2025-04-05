# Flappy Bird Game

![Welcome Screen](Screenshot 2025-04-05 052922.png)
*Welcome screen with animated text*

![Gameplay](Screenshot 2025-04-05 054544.png)  
*In-game screenshot showing the bird and pipes*

![Game Over](Screenshot 2025-04-05 054350.png)  
*Game over screen showing final score*

A Python implementation of the classic Flappy Bird game using Pygame.

## Essential Game Files
- `main.py` - Main game logic
- `gallery/sprites/bird.png` - Player character sprite
- `gallery/sprites/pipe.jpg` - Pipe obstacles
- `gallery/sprites/bg.jpg` - Background image
- `gallery/audio/` - Sound effects folder

## Recent Updates

### Visual Enhancements
- Added animated "SPACE" text on welcome screen
- Implemented gradient and shadow effects for title text
- Improved color-coded instructions

### Game Over Screen
- Added final score display
- Compact "Press SPACE" restart instruction
- Better vertical spacing between elements
- Consistent visual style with welcome screen

### Gameplay Improvements
- Proper game restart functionality
- Enhanced collision detection
- Improved scoring system

## Features
- Classic Flappy Bird gameplay mechanics
- Score tracking
- Sound effects
- Responsive controls

## Requirements
- Python 3.x
- Pygame

## Installation
1. Clone the repository:
```bash
git clone https://github.com/IshikaJain17/flappy-bird.git
cd flappy-bird
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## How to Play
- Press SPACE or UP ARROW to make the bird flap
- Avoid hitting the pipes
- Try to get the highest score!

## Controls
- SPACE/UP: Flap
- ESC: Quit game

## Project Structure
```
flappy-bird/
├── assets/
│   ├── audio/      # Game sound effects
│   └── sprites/    # Game graphics
├── main.py         # Main game logic
├── README.md       # This file
└── requirements.txt # Dependencies
```

## License
MIT License
