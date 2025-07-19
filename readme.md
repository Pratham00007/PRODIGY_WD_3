# 🎮 Tic Tac Toe Game with AI

A modern, interactive Tic Tac Toe game built with HTML, CSS, and JavaScript. Play against a friend or challenge yourself against an AI opponent with multiple difficulty levels!

<img width="1917" height="948" alt="tick_tack_ai" src="https://github.com/user-attachments/assets/89c2114b-4cb4-4907-8f28-45323ac871e5" />



https://github.com/user-attachments/assets/422fa39c-c2ae-4306-a03f-c4198044ada9




## ✨ Features

### 🎯 Game Modes
- **Player vs Player**: Classic two-player mode
- **Player vs AI**: Challenge the computer with 3 difficulty levels

### 🤖 AI Difficulty Levels
- **Easy**: Random moves - perfect for beginners
- **Medium**: Smart defensive play - blocks your wins and tries to win
- **Hard (Unbeatable)**: Uses minimax algorithm - nearly impossible to beat!

### 🎨 Interface Features
- **Modern UI Design**: Beautiful gradient backgrounds and smooth animations
- **Score Tracking**: Persistent score counter for X, O, and ties
- **Visual Feedback**: Hover effects, winning animations, and status messages
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Keyboard Controls**: Play using number keys (1-9) or mouse clicks
- **Game Controls**: Reset current game or start completely fresh
- **AI Indicator**: Shows when it's the AI's turn to move

## 🎯 How to Play

### Game Mode Selection
1. Choose between **Player vs Player** or **Player vs AI**
2. If playing against AI, select difficulty level (Easy/Medium/Hard)

### Gameplay
1. Player X always goes first (human player in AI mode)
2. Click on empty cells to make your move
3. In AI mode, wait for the AI to make its move (indicated by "AI" label)
4. Get three of your symbols in a row (horizontal, vertical, or diagonal) to win
5. If all cells are filled without a winner, it's a tie

### Controls
- **Reset Game**: Clear the board but keep scores
- **New Game**: Start fresh with reset scores
- **Mode Buttons**: Switch between Player vs Player and Player vs AI

## 🤖 AI Difficulty Explained

### Easy Mode 🟢
- Makes completely random moves
- Great for young players or casual games
- You should win most of the time

### Medium Mode 🟡  
- Tries to win when possible
- Blocks your winning moves
- Makes random moves otherwise
- Provides a good challenge for most players

### Hard Mode 🔴
- Uses the minimax algorithm
- Plays optimally every time  
- Nearly unbeatable when playing perfectly
- Best outcome against perfect AI is a tie

## 🚀 Quick Start

### Method 1: Download and Run
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start playing immediately!

### Method 2: Single File Version
If you prefer a single-file version, use the `tic-tac-toe.html` file which contains all HTML, CSS, and JavaScript in one file.

## 📁 Project Structure

```
tic-tac-toe/
├── index.html          # Main HTML structure
├── style.css           # All styling and animations
└── README.md          # This file
```

## 🎮 Controls

### Mouse Controls
- **Click** on any empty cell to make a move
- **Click** Reset Game to clear the board
- **Click** New Game to start over with fresh scores

### Keyboard Controls
- **1-9**: Make a move in the corresponding cell (numbered left-to-right, top-to-bottom)
- **R**: Reset the current game
- **N**: Start a new game

## 🛠️ Technical Details

### Built With
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Grid, Flexbox, and animations
- **Vanilla JavaScript**: Clean, modern ES6+ code

### Key Features Implementation
- **CSS Grid**: For the game board layout
- **CSS Animations**: Smooth transitions and winning effects
- **Event Listeners**: Handling clicks and keyboard input
- **Game State Management**: Tracking moves, turns, and scores
- **Win Detection Algorithm**: Efficient checking of all winning combinations
- **AI Algorithms**: 
  - Random move selection for Easy mode
  - Strategic blocking/winning for Medium mode
  - Minimax algorithm for Hard mode (unbeatable AI)

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Customization

### Colors
You can easily customize the color scheme by modifying the CSS variables:
- Primary gradient: `#667eea` to `#764ba2`
- Player X color: `#ff6b6b`
- Player O color: `#4ecdc4`
- Winning highlight: `#ffd700`

### Animations
All animations can be customized in the CSS:
- Hover effects duration: `0.3s`
- Winning pulse animation: `0.6s`
- Cell click animation: `0.1s`

## 📱 Responsive Design

The game automatically adapts to different screen sizes:
- **Desktop**: Full-featured layout with hover effects
- **Tablet**: Touch-optimized with larger buttons
- **Mobile**: Compact layout with vertical button stack

## 🐛 Troubleshooting

### Game Not Working?
1. Ensure all files are in the same directory
2. Check that file names match exactly (case-sensitive)
3. Open browser Developer Tools (F12) to check for errors
4. Try the single-file version (`tic-tac-toe.html`) as an alternative

### Common Issues
- **Cells not clickable**: Check JavaScript console for errors
- **Styling not loading**: Verify `style.css` path in `index.html`
- **Functions not working**: Ensure `script.js` is loading properly

## 🚀 Future Enhancements

- [ ] Online multiplayer support
- [ ] Different board sizes (4x4, 5x5)
- [ ] Themes and customizable colors
- [ ] Sound effects and music
- [ ] Tournament mode
- [ ] Player name customization
- [ ] Game statistics and history
- [ ] AI vs AI mode for demonstration
- [ ] Hint system for human players
- [ ] Game replay functionality colors
- [ ] Sound effects and music
- [ ] Tournament mode
- [ ] Player name customization
- [ ] Game statistics and history

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Guidelines
- Follow the existing code style
- Test your changes thoroughly
- Update documentation as needed
- Keep commits small and focused

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

Created with ❤️ by Pratham

## 🙏 Acknowledgments

- Inspired by the classic Tic Tac Toe game
- Modern design trends and CSS animations
- Community feedback and suggestions

---

### 🌟 Star this repository if you found it helpful!

**Enjoy playing Tic Tac Toe! 🎉**
