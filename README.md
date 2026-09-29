# XOX - Tic Tac Toe Game

A modern, responsive Tic-Tac-Toe game built with HTML, CSS, and JavaScript.

## Features

✨ **Game Modes**
- Player vs Player mode
- Player vs Computer mode (with AI using Minimax algorithm)

📊 **Score Tracking**
- Persistent score tracking across games
- Display wins for X, O, and draws

🎮 **Gameplay**
- 3x3 grid board with smooth interactions
- Turn-based gameplay with status updates
- Winner detection with animated highlighting
- Draw detection
- Restart button to clear the board

🎨 **Modern UI**
- Clean, colorful gradient design
- Responsive layout (mobile & desktop)
- Smooth animations and transitions
- Glassmorphism effects
- Color-coded players (Blue X, Pink O)

⚙️ **Smart AI**
- Unbeatable computer opponent using Minimax algorithm
- Realistic thinking delay for better UX

## How to Play

1. Open `index.html` in your web browser
2. Choose a game mode:
   - **Player vs Player**: Two human players take turns
   - **Player vs Computer**: Play against the AI
3. Click on any empty cell to make your move
4. First player to get 3 in a row (horizontal, vertical, or diagonal) wins
5. Click **Restart** to clear the board and play again

## Game Rules

- Players alternate turns, with X always going first
- Players can only place their mark in empty cells
- A player wins by getting 3 of their marks in a row
- If all cells are filled with no winner, it's a draw
- Scores are tracked across multiple games

## Technologies Used

- **HTML5**: Semantic markup and accessibility
- **CSS3**: Modern styling with gradients, animations, and flexbox/grid layouts
- **JavaScript (Vanilla)**: Game logic, AI, and interactivity

## AI Algorithm

The computer opponent uses the **Minimax algorithm** for optimal play:
- Evaluates all possible game states
- Assigns scores: +10 for AI win, -10 for player win, 0 for draw
- Selects the move with the highest score
- Provides an unbeatable opponent

## Browser Support

- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Installation

No installation required! Simply:
1. Download or clone the repository
2. Open `index.html` in your browser
3. Start playing!

## File Structure

```
tic-tac-toe-game/
├── index.html      # Game HTML, CSS, and JavaScript
└── README.md       # This file
```

## Future Enhancements

- Sound effects
- Difficulty levels for AI
- Game statistics and history
- Theme switcher (dark/light mode)
- Online multiplayer support
- Game replay feature

## License

Free to use and modify.

## Author

Created as a modern take on the classic Tic-Tac-Toe game.
