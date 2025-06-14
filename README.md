# Tetris Game

A modern Tetris implementation with clean visuals and smooth gameplay.

## Features

- Classic Tetris gameplay
- Next piece preview
- Score tracking with level progression
- Ghost piece indicator
- Sound effects with different tones for different actions
- Responsive design
- Keyboard controls

## Controls

- **← →** : Move piece
- **↑** : Rotate piece
- **↓** : Soft drop
- **Space** : Hard drop
- **P** : Pause game
- **M** : Mute sound

## Sound Design

The game uses Web Audio API to generate different tones for different actions:

- **Move sound**: `playSound(500, 0.05)` - 500Hz for 0.05 seconds
- **Rotate sound**: `playSound(600, 0.05)` - 600Hz
- **Line clear**: `playSound(700, 0.2)` - 700Hz (higher = more exciting)
- **Game over**: `playSound(200, 0.5)` - 200Hz (lower = sadder)


## Technologies

- HTML5 Canvas
- Vanilla JavaScript
- CSS3
- Web Audio API for sound effects
