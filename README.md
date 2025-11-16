# 🎰 Lotto Scratcher - Emoji Scratch Match Game

An interactive browser-based scratch-off lottery game where players scratch to reveal emoji patterns and win points based on various matching combinations!

## 🎮 Play Now

**[Play the game here!](https://echooff3.github.io/lotto-scratcher/)**

## 📖 About

Lotto Scratcher is a fun and engaging scratch-off game built entirely with vanilla JavaScript, HTML5 Canvas, and CSS. No external dependencies required! Scratch the silver overlay to reveal a 10x10 grid of emojis and discover winning patterns to rack up points.

## ✨ Features

- **Interactive Scratch Mechanic**: Use your mouse or touch to scratch away the overlay
- **Progress Tracking**: Visual progress bar shows how much you've scratched
- **Multiple Win Conditions**:
  - Full rows (10 matching emojis): 50 points
  - Full columns (10 matching emojis): 50 points
  - Main diagonal (10 matching emojis): 100 points
  - Anti-diagonal (10 matching emojis): 100 points
  - All 100 squares matching: 500 points
  - Chains (5+ consecutive matching emojis): 5 points per emoji
  - Groups (5+ connected matching emojis): 3 points per emoji
- **Score Multipliers**: Earn bonus multipliers for multiple winning patterns
  - 2+ wins: 1.5x multiplier
  - 3+ wins: 2x multiplier
  - 5+ wins: 2.5x multiplier
- **Celebration Effects**: Winning triggers particle animations and splash screens
- **Responsive Design**: Works on desktop and mobile devices
- **Persistent Score**: Track your total score across multiple rounds

## 🎯 How to Play

1. **Scratch**: Click and drag (or touch and swipe on mobile) to scratch away the silver overlay
2. **Reveal**: Continue scratching until at least 80% is revealed - the game will automatically check for wins
3. **Win**: If you have matching patterns, you'll see a victory splash with your points
4. **Play Again**: Click "Play Again" to start a new round (score resets, or keeps accumulating)

## 🚀 Installation & Usage

### Option 1: Play Online
Simply visit the [GitHub Pages link](https://echooff3.github.io/lotto-scratcher/) to play instantly in your browser!

### Option 2: Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/Echooff3/lotto-scratcher.git
   ```

2. Navigate to the project directory:
   ```bash
   cd lotto-scratcher
   ```

3. Open `index.html` in your web browser:
   - **Windows**: Double-click `index.html` or right-click → Open with → Your Browser
   - **Mac/Linux**: 
     ```bash
     open index.html  # Mac
     xdg-open index.html  # Linux
     ```
   
   Or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js http-server
   npx http-server
   ```
   Then visit `http://localhost:8000`

## 🎨 Game Elements

The game features 9 different fruit emojis:
- 🍎 Apple
- 🍊 Orange
- 🍋 Lemon
- 🍉 Watermelon
- 🍇 Grapes
- 🍓 Strawberry
- 🥭 Mango
- 🍈 Melon
- 🍑 Peach

## 🛠️ Technical Details

- **Pure Vanilla JavaScript**: No frameworks or libraries needed
- **HTML5 Canvas**: For the scratch-off overlay effect
- **CSS3 Animations**: Smooth transitions and particle effects
- **Responsive Design**: Adapts to screen sizes with media queries
- **Mobile-Friendly**: Touch events supported for mobile devices

## 📱 Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (Chromium)
- Firefox
- Safari
- Opera
- Mobile browsers (iOS Safari, Chrome Mobile, etc.)

## 🎓 Learning Project

This project demonstrates:
- Canvas manipulation and drawing
- Event handling (mouse and touch)
- Algorithm implementation (pattern detection, BFS for groups)
- Responsive web design
- Pure JavaScript game development

## 📄 License

This project is open source and available for educational and entertainment purposes.

## 🤝 Contributing

Feel free to fork this project and submit pull requests with improvements or new features!

## 👤 Author

Created by [Echooff3](https://github.com/Echooff3)

---

**Enjoy scratching and winning! 🎉**
