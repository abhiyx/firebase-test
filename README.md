# 🎮 **Tic-Tac-Toe Game with Firebase Analytics** 📊

## 🧐 Overview

This is a **Tic-Tac-Toe** game built with **HTML**, **CSS**, **JavaScript**, and **Firebase Analytics**. It was created as an **experiment** to explore how **Google Analytics (GA)** can be integrated with a simple web-based game. The goal is to track game events, user interactions, and more, while making the game interactive and fun! 🎯

---

## 🛠️ **Features**

- **🎯 Firebase Analytics Integration**:  
  Tracks important events like:
  - 🕹️ **Game Start** (`game_started`)
  - 🔄 **Move Made** (`move_made`)
  - 🏆 **Game Won** (`game_won`)
  - 🤝 **Draw Outcome** (`game_draw`)

- **✨ Winning Line Highlight**:  
  Winning streaks are dynamically highlighted with a **line drawn** through the winning cells.

- **📱 Responsive UI**:  
  Designed using **Tailwind CSS** for a clean and **mobile-friendly layout**.

- **👾 User-Friendly Gameplay**:  
  The game alternates between two players (**X** and **O**). It displays **win** or **draw** outcomes with a fun message and auto-updates the UI after every move.

---

## 💻 **Installation**

To run this project locally on your machine:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/tic-tac-toe-with-firebase.git
```

## 2. Open the Game
- Simply double-click the `index.html` file to open it in your browser.
- Or you can run it through any local server or host it on platforms like **GitHub Pages** or **Firebase Hosting**.

---

## 🔑 **Firebase Setup**
To enable **Google Analytics** with this app, follow these steps:

### 1. Create a Firebase Project
- Go to the **[Firebase Console](https://console.firebase.google.com/)**.
- Create a new project and add a web app.

### 2. Add Firebase SDK to Your Project
- Replace the Firebase config in `index.html` with your own **Firebase credentials** (available from the Firebase Console).

### 3. Enable Firebase Analytics
- In the **Firebase Console**, go to **Analytics** and start tracking events!

---

## 🔬 **Experimenting with Google Analytics (GA)**
This project was specifically built to experiment with **Google Analytics** in a web application. The aim was to understand how GA tracks:

- 🏃 **Custom Events**: For instance, tracking player moves or game results.
- 📊 **User Interaction**: Tracking button clicks, game starts, and game results.
- 🔥 **Real-Time Analysis**: Using Firebase's real-time features to see how users interact with the game.

---

## 📅 **Events Tracked with Google Analytics**
The following **custom events** are tracked via **Firebase Analytics**:

- **game_started**: Triggered when the game begins. 🕹️
- **move_made**: Triggered when a player makes a move. ↩️
- **game_won**: Triggered when a player wins the game. 🏆
- **game_draw**: Triggered if the game results in a draw. 🤝

These events are logged to help analyze **user engagement** and **game performance**. 📊

---

## 🕹️ **How to Play**

- **Start the Game**: Click the "Start Game" button to begin a new match. 🎮
- **Play the Game**: Players take turns to click on the grid and place their **X** or **O**. ✖️⭕️
- **End the Game**: The game ends when:
  - A player wins 🏆, or
  - It's a draw 🤝.
- **Restart the Game**: After a game ends, click **Restart Game** to start fresh. 🔄

---

## 💡 **Technologies Used**

- **Frontend**:
  - HTML, CSS (Tailwind CSS), JavaScript
  - Firebase SDK (for Analytics)

- **Hosting**: This can be hosted on platforms like **GitHub Pages** or **Firebase Hosting**. 🌐
