# Casino 

Casino is a **web-based application** that simulates three popular casino games: **Slots, Blackjack, and Roulette**. It supports both **single-player** and **multiplayer** over Wi-Fi, with all bets placed using **virtual currency (VC)**.

Unlike real online casinos, this project is **free, open source, and for educational/entertainment purposes only** — no real money, no accounts, no ads.


## How to Run

1. Clone the repository:

   git clone https://github.com/lehenry5208/casino.git
   cd casino
   
2. Install dependencies:

   npm install
   
3. Start the server:

   
   node server.js

4. Open in your browser:

   
   http://localhost:3000
   
5. To test multiplayer, open the link in multiple browser tabs or connect from multiple devices on the same Wi-Fi network.


## How to Build

* Built with:

  * **HTML, CSS, JavaScript** (front end)
  * **Node.js + Express** (server)
  * **Socket.IO** (real-time multiplayer)
  * **SQLite** (optional, to store VC balances & game history)

* Requirements:

  * Node.js installed
  * A modern browser (Chrome, Firefox, Edge, Safari)

---

## How to Contribute

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes.
4. Open a pull request.

## How to Play

# Slots

Place a bet with your virtual currency.

Spin the slot machine.

Matching symbols award winnings.

# Blackjack

Single-player: play against the dealer.

Multiplayer: multiple players compete against the dealer at the same table.

Objective: get as close to 21 as possible without going over.

# Roulette

Single-player: place bets on numbers, colors, or ranges.

Multiplayer: multiple players place bets before the same spin.

The wheel spins, and winnings are awarded based on the result
