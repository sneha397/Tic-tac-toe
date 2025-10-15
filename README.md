# Tic Tac Toe — Cool Neon Edition

A stylish **Tic Tac Toe game** built using **React** and **CSS**, featuring a neon theme with animated winning cells. Play against another player on the same device in this fun and visually appealing game.

---

## 🎮 Features

- **Player vs Player**: Two players can play on the same board.
- **Neon Design**: Vibrant colors, glowing animations, and smooth hover effects.
- **Win & Draw Detection**: Highlights winning line and displays the winner or draw.
- **New Game Button**: Reset the board and start a fresh match.
- **Responsive Layout**: Works on both desktop and mobile screens.

---

## 🛠️ Technologies Used

- **React 18** (via CDN)
- **Babel** (for JSX support)
- **HTML & CSS**
- **No backend required** — fully front-end

---

## 📦 How to Run

1. Clone or download the repository.
2. Open the `Tic-tac-toe.html` file in your browser.
3. Start playing immediately! No server setup needed.

---

## 📝 Usage

- Click on an empty cell to place **X** or **O**.
- The game automatically detects a winner or a draw.
- Click **New Game** to reset the board.

---

## 🎨 Customization

You can customize the game’s look by editing CSS variables:

```css
:root {
  --bg: radial-gradient(circle at top left, #0f172a 0%, #020617 100%);
  --glow1: #0ff;
  --glow2: #00bfff;
  --x-color: #38bdf8;
  --o-color: #06b6d4;
}
