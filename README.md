# 🃏 Blackjack - Card Game in TypeScript (CLI)

A simplified version of the classic Blackjack card game built with **TypeScript** and executed in the command line using **Node.js**. The objective is to get as close as possible to 21 without going over, playing against an automated dealer with basic **"Hit"** and **"Stand"** actions.

---

## 🚀 Features

- 🎮 Fully playable console-based Blackjack game
- 💵 Betting system with an initial bankroll of $100
- ♠️ Automatic card dealing with realistic game logic
- 🃏 Automatic detection of Blackjack, Busted, Push, and Winners
- 🅰️ Dual-value Ace support (1 or 11)
- 🧠 Dealer follows standard rules (stands on 17 or higher)
- 💰 3:2 payout for natural Blackjack
- 🔁 Multi-round gameplay until funds are depleted

---

## 🛠️ Technologies Used

- **TypeScript** – Strong typing and object-oriented approach
- **Node.js** – JavaScript runtime for CLI applications
- **prompt-sync** – For user input in the terminal

---

## 📦 Installation & Usage

1. **Install dependencies**
      npm install prompt-sync
      npm i --save-dev @types/prompt-sync

2. **Compile the TypeScript project**
      tsc
3. **Run the compiled app**
     node app.js
