# ⭕❌ Tic Tac Toe Game

A classic, responsive Tic Tac Toe web game built using vanilla HTML5, CSS3, and JavaScript[cite: 5, 6, 7]. It features a 2-player turn system, automatic win/draw detection, and options to reset or start a new game[cite: 5, 6].

[👉 Click Here to Play the Live Game](https://github.com/Debjeet-Roy-Chowdhury/Tic-Tac-Toe)

---

## ✨ Features

- **2-Player Turn Mode:** Seamlessly toggles turns between **X** (starts first) and **O**[cite: 6].
- **Win Detection:** Automatically checks for winning horizontal, vertical, and diagonal patterns[cite: 6].
- **Draw Detection:** Detects when all 9 moves are completed without a winner and displays a draw message[cite: 6].
- **Overlay Winner Banner:** Displays a congratulatory modal overlay for the winner along with a **New Game** button[cite: 5, 6].
- **Quick Reset:** Includes a dedicated **Reset Game** button to clear the board at any point during gameplay[cite: 5, 6].
- **Responsive Grid:** Uses relative CSS units (`vmin`) to keep the grid perfectly scaled across different screen sizes[cite: 7].

---

## 🛠️ Tech Stack

- **HTML5:** Board grid structure, buttons, and winner modal container (`index.html`)[cite: 5].
- **CSS3:** Dark-themed background, Flexbox grid layout, yellow grid buttons, and modal positioning (`style.css`)[cite: 7].
- **JavaScript (ES6):** Event handlers for grid clicks, array pattern checking (`winPatterns`), move tracking, and DOM state toggling (`script.js`)[cite: 6].

---

## 📖 How to Play

1. Player 1 clicks any empty box to mark an **X**[cite: 6].
2. Player 2 clicks an empty box to mark an **O**[cite: 6].
3. The game ends as soon as one player aligns 3 matching marks horizontally, vertically, or diagonally, or when all 9 boxes are filled without a winner[cite: 6].
4. Click **New Game** or **Reset Game** to play again[cite: 5, 6]!

---

## 💻 Local Setup

1. Clone the repository:
   ```bash
   git clone [https://github.com/Debjeet-Roy-Chowdhury/Tic-Tac-Toe.git](https://github.com/Debjeet-Roy-Chowdhury/Tic-Tac-Toe.git)