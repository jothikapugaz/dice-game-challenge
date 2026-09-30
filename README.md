# 🎲 Dice Game Challenge

A simple two-player dice game built with **HTML, CSS, and JavaScript**. Each time the page is loaded, two dice are rolled randomly and the result is displayed for Player 1 and Player 2.

## ✨ Features

- 🎲 Generates a random dice value from 1 to 6 for each player
- 👥 Compares the two dice values automatically
- 🏆 Displays the winner
- 🤝 Displays a draw when both players roll the same number
- 🖼️ Uses individual dice images for values 1–6
- 💻 Simple browser-based implementation with no external JavaScript libraries

## 🛠️ Technologies Used

- **HTML5** – page structure
- **CSS3** – styling and layout
- **JavaScript** – random dice generation and game logic

## 🎮 How It Works

When the page loads:

1. JavaScript generates a random number between **1 and 6** for Player 1.
2. A second random number between **1 and 6** is generated for Player 2.
3. The corresponding dice images are displayed.
4. The two values are compared.
5. The heading is updated to show:
   - **Player 1 Wins!**
   - **Player 2 Wins!**
   - **Draw!**

To play again, simply **refresh the page** to generate a new result.

## 📁 Project Structure

```text
dice-game-challenge/
├── dice.html
├── index.js
├── styles.css
└── images/
    ├── dice1.png
    ├── dice2.png
    ├── dice3.png
    ├── dice4.png
    ├── dice5.png
    └── dice6.png
```

## 🚀 Run Locally

1. Clone this repository:

```bash
git clone https://github.com/jothikapugaz/dice-game-challenge.git
```

2. Open the project folder in VS Code.
3. Make sure the `images` folder contains all six dice images.
4. Open `dicee.html` in a web browser.
5. Refresh the page to play again.

You can also use the **Live Server** extension in VS Code for a smoother development experience.

## 📚 What I Practiced

This project helped me practice:

- JavaScript variables and conditional statements
- Generating random numbers with `Math.random()`
- Updating HTML elements with JavaScript
- Changing image sources dynamically
- Basic DOM manipulation
- Organizing a small frontend project into separate HTML, CSS, JavaScript, and image files

## 🔮 Possible Improvements

Some ideas for future versions:

- Add a **Roll Dice** button instead of requiring a page refresh
- Add a running score for both players
- Add a reset button
- Add simple animations when the dice are rolled
- Improve the responsive design for smaller screens

## 👩‍💻 Author

**Jothika P**

Computer Science & Engineering graduate | Aspiring Full-Stack Developer

GitHub: [@jothikapugaz](https://github.com/jothikapugaz)
