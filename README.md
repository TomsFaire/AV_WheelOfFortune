# Wheel of Fortune Game

A fully functional Wheel of Fortune game built with HTML, CSS, and JavaScript. Perfect for live events, team building, or entertainment.

## Features

- **Spinning Wheel**: Interactive wheel with realistic physics and animation
- **4-Player Scoring**: Track points for up to 4 players with active player indicators
- **Smart Word Layout**: Automatic word wrapping that keeps words intact across lines
- **Virtual Keyboard**: Click or type letters to make guesses
- **Custom Puzzles**: Press `Ctrl+Shift+P` to enter custom phrases
- **Responsive Design**: Works on all screen sizes with 16:9 aspect ratio
- **Classic Theme**: Authentic Wheel of Fortune colors and styling

## How to Play

1. **Spin the Wheel**: Click the wheel or press spacebar
2. **Guess Letters**: Type letters or click the virtual keyboard
3. **Earn Points**: Get points based on wheel value × number of letters found
4. **Special Results**: 
   - BANKRUPT: Lose all points, next player
   - LOSE A TURN: Skip to next player
   - FREE PLAY/WILD/MYSTERY: Guess any letter

## Customization

- **Custom Puzzles**: Press `Ctrl+Shift+P` to enter your own phrases
- **Player Names**: Edit player names in the JavaScript section
- **Wheel Values**: Modify the `DEFAULT_ITEMS` array to change wheel values

## Technical Details

- **Pure HTML/CSS/JavaScript**: No external dependencies
- **Canvas-based Wheel**: Smooth animations with requestAnimationFrame
- **Responsive Grid Layout**: Adapts to different screen sizes
- **Smart Text Layout**: Prevents word breaking across lines

## Usage

Simply open `index.html` in any modern web browser. The game is ready to play immediately with the default puzzle "FAIRE MARKET".

## License

Private repository for Tom's Faire projects.