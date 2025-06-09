# 🎲 Tenzies Game

Tenzies is a small game of luck and strategy built with React. The goal of the game is simple: roll the dice until all of them show the same value. On each turn, you can hold the dice you want to keep so they won’t change on the next roll.
<img src="./public/screenshot.png" alt="Capture d'écran du jeu Tenzies" width="350" />

## 🌐 Live Demo
👉 Available here: [https://tenzies-psi-nine.vercel.app](https://tenzies-psi-nine.vercel.app)

---

## 🕹️ Game Rules

- The game starts with 10 dice showing random values from 1 to 6.
- Click on a die to hold it (lock its current value).
- Click the "Roll" button to roll all unheld dice.
- The game is won when all dice are held and display the same value.
- A confetti animation celebrates your victory, and a button lets you start a new game.

---

## 🛠️ Technologies Used

- **React**
- **NanoID** – for generating unique IDs
- **react-confetti** – for victory visual effects
- **CSS Modules** or custom styling

---

## ✨ Features

- Simple and responsive interface
- Automatic win detection logic
- Easy option to replay a new game

---

## 🚀 Run the Project Locally

### Cloner le dépôt

```bash
git clone git@github.com:Dfremont7/tenzies.git
cd tenzies
````
### Installer les dépendances
```bash
npm install
````

### Démarrer le serveur de développement
```bash
npm run dev
````
