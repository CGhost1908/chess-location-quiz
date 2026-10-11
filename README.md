# ♟️ Chess Location Quiz - Board Vision & Coordinate Trainer

**Chess Location Quiz** is an interactive, browser-based chess training web app designed to sharpen chess board vision, algebraic notation recall, and spatial board awareness. Test and improve how fast you can identify squares like `e4`, `g5`, or `c7` under time pressure!

---

## 🌟 Key Features

- 🎯 **Coordinate Mastery**: Practice finding random coordinates (`a1` through `h8`) rapidly across the 64 squares.
- ⏱️ **Two Game Modes**:
  - **Total Time Challenge**: Score as many correct squares as possible before the overall countdown runs out.
  - **Per-Move Blitz**: Race against a strict per-square countdown timer.
- ⚡ **Instant Visual Feedback**: Color highlights indicate correct clicks and misclicks in real-time.
- 📊 **Scoring & Performance Stats**: Track your total score, speed, and accuracy summary at the end of each round.
- 🔄 **Quick Retry**: Seamless restart options to immediately beat your personal best.
- 🚀 **Zero Dependencies**: Pure HTML5, CSS3, and Vanilla JavaScript — lightweight and lightning fast.

---

## 📁 Repository Structure

```text
chess-location-quiz/
├── index.html          # Interactive 8x8 chessboard grid & game HUD
├── script.js           # Random coordinate generator, countdown timers & score tracker
├── style.css           # Modern chessboard styling, dark/light square themes & modal dialogs
└── README.md           # Game documentation
```

---

## 🚀 How to Play

No build step or server required!

1. **Clone the repository:**
   ```bash
   git clone https://github.com/CGhost1908/chess-location-quiz.git
   cd chess-location-quiz
   ```

2. **Open the Game:**
   - Double-click `index.html` to run directly in your browser.
   - Or start a local server:
     ```bash
     python -m http.server 3000
     ```
     Visit `http://localhost:3000` in your web browser.

3. **Rules:**
   - Set your preferred round duration.
   - Choose between **Total Time** or **Per-Move** mode.
   - Look at the target coordinate displayed on the screen and click the matching square on the board as fast as you can!

---

## 📄 License

This project is licensed under the MIT License.
