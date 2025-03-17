# Snake Game

A classic Snake Game implementation using HTML5 Canvas, CSS, and JavaScript. Control a snake to eat food and grow longer while avoiding collisions with walls and itself.

## Features

- Smooth snake movement with arrow key controls
- Score tracking
- Food generation
- Collision detection (walls and self)
- Game over screen with restart capability
- Prevented default scrolling behavior when using arrow keys
- Responsive design

## How to Play

1. Open `index.html` in a web browser
2. Click the "Start Game" button to begin
3. Use the arrow keys to control the snake's direction:
   - ↑ (Up Arrow): Move up
   - ↓ (Down Arrow): Move down
   - ← (Left Arrow): Move left
   - → (Right Arrow): Move right
4. Eat the red food blocks to grow and increase your score
5. Avoid hitting the walls or colliding with yourself
6. When game over, click "Play Again" to restart

## Technical Details

- Built with vanilla JavaScript, HTML5, and CSS
- Uses HTML5 Canvas for rendering
- Implements event prevention for arrow keys to avoid page scrolling while playing
- Responsive design that works across different screen sizes

## Project Structure

```
snake-game/
├── index.html
├── js/
│   └── game.js
└── styles/
    └── style.css
```

## Recent Updates

- Added prevention of default scrolling behavior when using arrow keys during gameplay
- Implemented game over screen with restart functionality
- Added score tracking system

## Development

To modify or enhance the game:

1. Clone the repository
2. Make changes to the relevant files:
   - `index.html` for structure
   - `js/game.js` for game logic
   - `styles/style.css` for styling
3. Test in a web browser

## License

This project is open source and available for anyone to use and modify. 