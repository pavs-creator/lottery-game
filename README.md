# 🎰 Lottery Game (Naku gift vacchindi....jingachaka)

A fun, simple client-side lottery guessing game built using HTML, CSS, and pure JavaScript. The game challenges the user to guess a randomly selected "winning number" among **50** options. The goal was to practice **DOM manipulation**, **event handling**, and **managing game state** in JavaScript.

***

## ✨ Features

* **Dynamic Board Generation:** The lottery boxes (numbers 1-50) are dynamically created using JavaScript when the page loads.
* **Random Winner Selection:** A new winning number is **secretly and randomly chosen** upon clicking the 'Pick a number' button (range is **1 to 50**).
* **Visual Feedback:**
    * The user's currently selected box is highlighted with a **red border** (`.highlightBox`).
    * The correct winning box changes to a **green background** (`.winningBox`) upon a successful guess.
* **Game State Management:** Prevents guessing until the game has officially started.

***

## 🕹️ How to Play

The player's role is to click the boxes to find the secret number!

1.  **Start the Game:** Click the **"Pick a number"** button. The system automatically picks the winning number (between 1 and **50**).
2.  **Guess the Number:** Click on any of the **50 numbered boxes** on the sheet. This is your guess.
3.  **Check the Result:** The result message below the sheet will update.
    * **WIN:** If your click matches the secret number, you win  The winning box turns green, and the game ends.
    * **LOSE:** If your click is incorrect, keep clicking other boxes until you find the winner!

***

## ⚙️ Installation and Setup

This project is entirely client-side. Simply clone the repository and open the `index.html` file in any modern web browser.

```bash
# Clone the repository
git clone [https://github.com/pavs-creator/lottery-game.git](https://github.com/pavs-creator/lottery-game.git)

# Navigate into the project directory
cd lottery-game

# Open index.html in your browser to start playing!
