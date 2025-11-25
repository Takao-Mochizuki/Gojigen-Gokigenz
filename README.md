# Gojigen Gokigenz - 3D Neon Edition

A 3D browser-based strategy game inspired by "Goblet Gobblers" - a twist on tic-tac-toe where pieces can gobble smaller ones!

## Play Online

Open `index.html` in a modern browser, or host it on GitHub Pages.

## Game Rules

### Objective
Line up 3 of your pieces (visible on top) in a row - horizontally, vertically, or diagonally!

### Pieces
Each player has 6 pieces: 2 Large, 2 Medium, 2 Small

### Key Mechanics
- **Gobbling**: Larger pieces can be placed on top of smaller ones (yours or opponent's!)
- **Hidden Pieces**: Gobbled pieces aren't removed - they reappear when the covering piece moves
- **Strategic Movement**: Move your pieces on the board to reveal hidden pieces or create new threats

### Controls
1. Click a piece from your reserve (left/right panels) or on the board
2. Click a board cell to place/move the selected piece
3. Click the same piece again to deselect

## Features

- **3D Graphics**: Powered by Three.js with neon aesthetics
- **4 AI Difficulty Levels**:
  - Beginner: Random moves
  - Intermediate: Basic strategy (win/block)
  - Advanced: Minimax (3-ply search)
  - Pro: Alpha-beta pruning (5-ply search with advanced evaluation)
- **Visual Effects**: Particle systems, piece animations, dynamic lighting
- **Responsive Design**: Works on desktop and mobile

## Technical Stack

- Pure HTML/CSS/JavaScript
- Three.js for 3D rendering
- No build tools required

## License

MIT License
