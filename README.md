# 🧠 Interactive Quiz Game

A modern, responsive quiz application built with React that tests knowledge across multiple categories with real-time scoring, timers, and engaging animations.

## ✨ Features

- **🎯 Multiple Choice Questions** - 8 carefully crafted questions across different categories
- **⏱️ Real-time Timer** - 30-second countdown per question with visual indicators
- **📊 Live Score Tracking** - Dynamic score updates and progress visualization
- **🎨 Category-based Organization** - Questions organized by Science, Geography, Art, Technology, and History
- **💫 Smooth Animations** - Engaging hover effects and transitions
- **📱 Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **🎉 Interactive Feedback** - Instant visual feedback for correct/incorrect answers
- **🏆 Results Summary** - Comprehensive score analysis with motivational messages
- **🔄 Replay Functionality** - Easy restart option to play multiple times

## 🚀 Quick Start

### Option 1: Direct HTML File (Recommended)

1. **Download the files:**
   ```bash
   git clone https://github.com/yourusername/quiz-game.git
   cd quiz-game
   ```

2. **Open and play:**
   - Double-click `quiz-game.html`
   - The game opens directly in your browser
   - No installation required!

### Option 2: React Development Environment

1. **Prerequisites:**
   - Node.js (v14 or higher)
   - npm or yarn

2. **Setup:**
   ```bash
   npx create-react-app quiz-game
   cd quiz-game
   npm install lucide-react
   ```

3. **Replace `src/App.js` with the React component code**

4. **Run the development server:**
   ```bash
   npm start
   ```

## 🎮 How to Play

1. **Start the Quiz** - Click on any answer option to begin
2. **Answer Questions** - Select from 4 multiple-choice options
3. **Beat the Timer** - You have 30 seconds per question
4. **Track Progress** - Watch your score and progress bar
5. **View Results** - See your final score and performance message
6. **Play Again** - Click "Play Again" to restart

## 📚 Question Categories

- **🔬 Science** - Physics, Chemistry, Biology
- **🌍 Geography** - Countries, Capitals, Landmarks
- **🎨 Art** - Famous Artists, Paintings, Art History
- **💻 Technology** - Programming, Computer Science
- **📜 History** - World Events, Historical Facts

## 🛠️ Technical Details

### Built With
- **React 18** - Modern React with Hooks
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide React** - Beautiful icon library
- **Vanilla JavaScript** - Core game logic

### Key Components
- **Timer System** - useEffect-based countdown timer
- **State Management** - React useState for game state
- **Responsive Design** - Mobile-first approach
- **Performance Optimized** - Efficient re-renders and animations

### File Structure
```
quiz-game/
│
├── quiz-game.html          # Complete HTML version
├── src/
│   ├── QuizGame.jsx       # Main React component
│   └── questions.js       # Question database
├── README.md              # This file
└── package.json           # Dependencies (for React version)
```

## 🎨 Customization

### Adding More Questions
```javascript
const newQuestion = {
  question: "Your question here?",
  options: ["Option 1", "Option 2", "Option 3", "Option 4"],
  correct: 2, // Index of correct answer (0-3)
  category: "Your Category"
};
```

### Modifying Timer
```javascript
// Change timer duration (in seconds)
const [timeLeft, setTimeLeft] = useState(45); // 45 seconds instead of 30
```

### Adding New Categories
```javascript
const getCategoryColor = (category) => {
  const colors = {
    Science: "bg-blue-100 text-blue-800",
    Geography: "bg-green-100 text-green-800",
    // Add your new category
    Mathematics: "bg-yellow-100 text-yellow-800",
  };
  return colors[category] || "bg-gray-100 text-gray-800";
};
```

## 📱 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Contribution Ideas
- 🆕 Add more question categories
- 🎵 Add sound effects
- 🏅 Implement difficulty levels
- 💾 Add local storage for high scores
- 🌐 Add multiplayer functionality
- 🎭 Add question shuffling


⭐ **Star this repository if you found it helpful!** ⭐

## 🚀 Live Demo

[🎮 **Play the Quiz Game**](https://Nihitha8819.github.io/quiz-game/)

---

Made with ❤️ and ☕ by [Your Name]
