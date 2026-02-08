# 🏙️ Visual Backtracking Simulator

> **An interactive visual simulation of the 4×4 Skyscraper puzzle solver with real-time backtracking animation.**

### DEMO [Skyscrapers DEMO](https://mariusdamien.github.io/Skyscraper-solver/)

---

## ✨ Features

- **Real-time backtracking visualization** — watch each value being placed and removed step by step
- **Animated 2D grid** with color-coded building heights (1–4)
- **Skyline view** — proportional bars representing building heights per row
- **Clue indicators** displayed around the grid (top, bottom, left, right)
- **Live statistics** — step count, backtrack count, elapsed time
- **Activity log** tracking every solver action
- **Adjustable speed** slider to slow down or speed up the animation
- **Preset puzzles** to quickly test different configurations

## 🚀 Usage

Just open `index.html` in any modern browser. No dependencies, no build step.

1. Enter 16 clues (digits 1–4 separated by spaces) or pick a preset
2. Click **Résoudre** and watch the algorithm work
3. Adjust the speed slider to control animation pace

## 📸 How it works

The solver uses **recursive backtracking**: it tries placing values 1–4 in each cell, checks for row/column duplicates and visibility clue violations, and backtracks when it hits a dead end — all animated in real time.

## 👤 Author

**Marius DAMIEN**

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
