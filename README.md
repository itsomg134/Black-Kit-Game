# Black Kit Game

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge)](https://your-demo-link.com)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge)](CONTRIBUTING.md)

> An interactive memory and pattern recognition game where players find and collect black items hidden among colorful emojis.

![Game Screenshot](https://via.placeholder.com/800x400?text=Black+Kit+Game+Screenshot)


## About The Game

**Black Kit Game** is a fun, interactive web-based game that challenges your observation skills. The game presents a 4x4 grid of hidden emojis, and your task is to find all the black-themed items. Each correct discovery earns points, and finding all items unlocks a bonus!

The game features:
- Clean, dark-themed UI with glass-morphism effects
- Real-time scoring and progress tracking
- Persistent high scores using localStorage
- Customizable emoji selection
- Responsive design for all screen sizes

## Features

### Core Gameplay
- **16 cards** arranged in a 4x4 grid
- **8 black items** hidden among colorful emojis
- **10 points** per correct find
- **50-point bonus** for finding all black items
- **Real-time stats** tracking (Score, Found items, Attempts, High Score)

### Visual Design
- Glass-morphism UI with backdrop blur
- Gradient backgrounds and animations
- Smooth hover and click effects
- Shake animation for wrong guesses
- Responsive design for mobile and desktop

### User Experience
- 💾 **Persistent high scores** stored in browser localStorage
- 🎮 **Customizable emoji selection** - choose your favorite black emoji
- 🔄 **New Game** and **Reset** functionality
- 📱 **Mobile-optimized** touch interactions
- ⚡ **Instant feedback** on every action

## 🚀 How to Play

1. **Open the game** in your web browser
2. **Click on cards** to reveal hidden emojis
3. **Find black items** (🖤, ⬛, 🐈‍⬛, 🦇, 🎱, 🕶️, 🐧, ⚫)
4. **Score points** for each correct find
5. **Find all 8** to earn a bonus and win!
6. **Beat your high score** with each new game

### Controls
- **New Game** - Start a fresh game with new card layout
- **Reset** - Reset current game without changing card layout
- **Emoji Picker** - Select your preferred black emoji style

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Advanced styling with animations, gradients, and glass-morphism
- **Vanilla JavaScript** - Pure JS for game logic, DOM manipulation, and state management
- **LocalStorage API** - Persistent high score storage

### Key CSS Features
- CSS Grid for card layout
- CSS animations (@keyframes)
- Backdrop blur and glass effects
- Responsive design with media queries
- CSS custom properties for theming

### Key JavaScript Features
- State management with object-oriented approach
- Event delegation for card interactions
- LocalStorage for data persistence
- Dynamic DOM manipulation

## 📦 Installation

### Option 1: Quick Start (Single File)
1. Download the `index.html` file
2. Open it in your browser
3. Start playing!

### Option 2: Clone Repository
```bash
# Clone the repository
git clone https://github.com/yourusername/black-kit-game.git

# Navigate to the project directory
cd black-kit-game

# Open in browser (or use a local server)
open index.html
# or use Python's built-in server
python3 -m http.server 8000
```

### Option 3: Using a Local Server
```bash
# Using Node.js (install http-server globally)
npm install -g http-server
http-server

# Using Python
python -m http.server 8000

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 🎯 Game Mechanics

### Card Generation
- 16 cards randomly generated
- 8 cards contain black emojis (chosen from 8 black-themed emojis)
- 8 cards contain colorful emojis (randomly selected)
- Cards are shuffled for each new game

### Scoring System
- **+10 points** for each black item found
- **+50 bonus points** for finding all 8 black items
- **No penalty** for wrong guesses (encourages learning)
- **High score** saved automatically

### Game States
- **Active** - Game is in progress
- **Complete** - All black items found
- **Reset** - Game reset to initial state

## 🎨 Customization

### Changing Emoji Sets
```javascript
// In the script section, modify these arrays:
const emojis = ['🖤', '⬛', '🐈‍⬛', '🦇', '🎱', '🕶️', '🐧', '⚫'];
const blackEmojis = ['🖤', '⬛', '🐈‍⬛', '🦇', '🎱', '🕶️', '🐧', '⚫'];
```

### Adjusting Grid Size
```javascript
state.totalCards = 16; // Change to 8, 12, 20, etc. (must be divisible by 4)
```

### Score Values
```javascript
state.score += 10; // Points per correct find
state.score += 50; // Bonus for completing all
```

### Color Scheme
```css
/* Modify these CSS variables */
background: linear-gradient(135deg, #1a1a2e, #16213e, #0f3460);
border-color: #ffd700; /* Gold accent */
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### Ideas for Contributions
- 🎮 Add difficulty levels (easy, medium, hard)
- 🏆 Create leaderboard system
- 🎨 More emoji themes
- 🔊 Sound effects for interactions
- 📱 PWA support
- 🕹️ Timer mode

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

- **Developer**: Your Name
- **Email**: your.email@example.com
- **GitHub**: [@yourusername](https://github.com/yourusername)
- **Live Demo**: [Play Now](https://your-demo-link.com)

## 🙏 Acknowledgments

- Emoji designs by [Unicode Consortium](https://unicode.org/emoji/)
- Inspired by classic memory games
- Built with ❤️ for the coding community

---

### ⭐ Show Your Support

If you enjoyed this game, please consider:
- ⭐ Starring the repository
- 🐛 Reporting bugs
- 💡 Suggesting new features
- 🔗 Sharing with friends

---

**Made with 💻 and ☕**
