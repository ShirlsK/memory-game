# 🃏 Memory Card Game

A simple **Memory Card Game** built with **HTML**, **CSS**, and **JavaScript**.

## 🎮 Demo

*Click the cards to find matching pairs. Once all pairs are matched, click "Restart" to play again.*

## ✨ Features

- Card shuffling on start and restart
- Card flip animations
- Score tracking (number of clicks)
- Restart button to reset the game
- Responsive design

## 🛠️ Technologies used

- HTML5
- CSS3 (grid layout + animations)
- Vanilla JavaScript (no frameworks)

## 🗂️ Project Structure
MemoryGame/
├── index.html
├── index.js
├── style.css
├── data/
│ └── cards.json
├── images/
├── banana.jpg
├── cherry.jpg
└── ... etc.
└── README.md

## 🚀 How to run the project

### 1️⃣ Recommended: run with Live Server

- Open the project folder in **Visual Studio Code**
- Install the **Live Server extension**
- Right-click `index.html` → **"Open with Live Server"**

→ This will ensure that `fetch()` works correctly.

### 2️⃣ Alternative: run with a simple local server

You can also run a basic local server to avoid CORS issues with `fetch()`.

**Example using Python:**

```bash
python3 -m http.server
