# 🎮 Assembly Endgame  

A **word-guessing game** built with **React**, featuring **complex state management**, **conditional rendering**, and **visual feedback** using third-party libraries like **clsx** and **Confetti**.  

![Assembly Endgame](https://raw.githubusercontent.com/noamguterman/Assembly-Endgame/refs/heads/main/assembly-preview.png)  

## 🚀 Live Demo  
🔗 [Try Assembly Endgame](https://noamguterman.github.io/Assembly-Endgame/)  

---

## 📝 Features  
✅ **Interactive word-guessing gameplay** – Guess letters and reveal the hidden word.  
✅ **State-driven UI updates** – Tracks correct and incorrect guesses dynamically.  
✅ **Themed visual effects** – Color-coded status indicators for game state.  
✅ **Accessibility-friendly** – ARIA attributes for screen readers.  
✅ **Confetti animation for wins** – Celebratory visual feedback on correct guesses.  
✅ **Adaptive difficulty** – Game ends after a set number of incorrect guesses.  

---

## 🛠️ Tech Stack  
- **Frontend:** React, React Hooks  
- **State Management:** useState, useEffect  
- **UI Enhancements:** clsx (conditional styling)  
- **Animations & Effects:** Confetti  
- **Deployment:** GitHub Pages / Vercel  

---

## 🎯 How It Works  
1️⃣ Click **Start New Game** to begin.  
2️⃣ Guess letters using the on-screen keyboard.  
3️⃣ Incorrect guesses remove programming languages from the list.  
4️⃣ The game ends if the word is fully revealed or attempts run out.  
5️⃣ Confetti celebrates wins, and a game-over message appears on losses.  

---

## 🏠 Project Structure  
```
/
  ├── src/
  │   ├── App.jsx            # Main game logic
  │   ├── utils.js           # Utility functions for word selection
  │   ├── components/
  │   │   ├── GameBoard.jsx  # Word display and guessing logic
  │   │   ├── Keyboard.jsx   # Letter selection buttons
  │   │   ├── Status.jsx     # Game status messages
  │   ├── assets/            # Visual assets & styles
  │   ├── index.css          # Global styles
  ├── public/
  │   ├── index.html         # Entry point for React
  ├── package.json           # Dependencies & scripts
  ├── README.md              # Project documentation
```

---

## 🛠️ Game Mechanics  
- **Randomized Word Selection** – Each game starts with a randomly chosen word.  
- **Dynamic Visual Feedback** – Incorrect guesses alter the game state visually.  
- **Confetti Celebration** – Wins trigger animated confetti effects.  

---

## 🌟 Why This Project?  
This project demonstrates **React-based state management**, **conditional UI rendering**, and **accessibility best practices**. It showcases:  
✔️ **Complex state handling with React Hooks**  
✔️ **Dynamic UI updates based on game progression**  
✔️ **User experience enhancements with animations**  
✔️ **Keyboard accessibility and ARIA attributes**  

---

## 🐝 License  
This project is for personal use and is not licensed for redistribution or modification.  

---

