# Tetris Game

## About
A modern Tetris implementation with clean visuals, smooth gameplay, and sound effects generated purely using JavaScript and the Web Audio API. Enjoy classic Tetris mechanics with a responsive design, perfect for both casual players and developers exploring web-based game development.

## Features
- Classic Tetris gameplay
- Next piece preview
- Score tracking with level progression
- Ghost piece indicator
- Sound effects with different tones for different actions (implemented using JavaScript)
- Responsive design
- Keyboard controls

## Controls
- ← → : Move piece
- ↑ : Rotate piece
- ↓ : Soft drop
- Space : Hard drop
- P : Pause game
- M : Mute sound

## Sound Design
The game uses the Web Audio API to generate different tones for actions, all implemented with JavaScript:
- Move sound: `playSound(500, 0.05)` - 500Hz for 0.05 seconds
- Rotate sound: `playSound(600, 0.05)` - 600Hz
- Line clear: `playSound(700, 0.2)` - 700Hz (higher = more exciting)
- Game over: `playSound(200, 0.5)` - 200Hz (lower = sadder)

## Technologies
- HTML5 Canvas
- Vanilla JavaScript
- CSS3
- Web Audio API for sound effects

## Installation
1. Clone or download this repository.
2. Open `index.html` in a modern web browser.
3. Start playing using the keyboard controls!

## Contributing
Contributions are welcome! Feel free to fork the repository, add features, or fix bugs, and submit a pull request.

## License
This project is licensed under the MIT License.
