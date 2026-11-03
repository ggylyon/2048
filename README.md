# 🎮 2048 Game

A modern browser-based implementation of the classic **2048 puzzle game**, built with JavaScript, HTML, and CSS.

Slide numbered tiles across a 4×4 grid, merge matching numbers, and challenge yourself to reach the legendary **2048 tile**. Every move matters — plan your strategy carefully and try to achieve the highest score!

## 🚀 Live Preview

[**Play 2048 →**](https://ggylyon.github.io/2048/)

## 🎨 Design Reference

The game is inspired by the original 2048 puzzle game.

[View the original game →](https://play2048.co/)

## 🛠 Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Game structure and layout |
| CSS3 | Styling and responsive interface |
| JavaScript (ES6+) | Game logic, tile movements, merging, and score calculation |
| npm | Dependency management and project scripts |
| Jest | Unit testing |
| Cypress | End-to-end testing |

## ✨ Features

- **Classic 2048 gameplay** — play on a 4×4 grid.
- **Four-direction movement** — use arrow keys to move tiles up, down, left, or right.
- **Dynamic scoring** — earn points by merging tiles.
- **Random tile generation** — new tiles appear after successful moves.
- **Win and game-over detection** — receive feedback when you reach 2048 or run out of moves.
- **Restart functionality** — start a new game whenever you want.
- **Clean interface** — focus on the puzzle and your next move.

## 🎯 How to Play

1. Click the **Start** button to begin a new game.
2. Use the arrow keys on your keyboard to move all tiles in the selected direction.
3. Merge two tiles with the same number to create a tile with double the value.
4. Keep combining tiles and increase your score.
5. Reach the **2048 tile** to win the game!

### Game Rules

- The game board consists of 16 cells arranged in a 4×4 grid.
- Tiles slide as far as possible in the selected direction.
- Two tiles with the same value merge into one tile with double the value.
- A tile can merge only once per move.
- A new tile (2 or 4) appears after every successful move.
- The game ends when no more moves are available.

## ⚙️ Getting Started

Follow these steps to run the project locally.

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (LTS version recommended)
- npm (included with Node.js)
- Git

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ggylyon/js_2048_game.git
   ```

2. Navigate to the project directory:

   ```bash
   cd js_2048_game
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

5. Open the local URL provided in your terminal.

> **Note:** If the `npm start` command is not configured in your `package.json`, use the available project scripts or a local development server.

## 🧪 Testing

Run the test suite:

```bash
npm run test
```

Run tests without linting:

```bash
npm run test:only -- -n
```

Run tests with additional console information:

```bash
npm run test:only -- -l
```

## 📁 Project Structure

```text
js_2048_game/
├── src/
│   ├── modules/
│   │   └── Game.class.js
│   ├── index.html
│   └── main.js
├── tests/
├── cypress/
│   └── integration/
├── package.json
├── package-lock.json
└── README.md
```

## 📄 License

This project is distributed under the [GPL-3.0 License](./LICENSE).

---

Made with JavaScript.
