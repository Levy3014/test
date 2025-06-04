# 🎮 Game Launcher with Search

This is a simple web-based game launcher that lets you quickly browse and launch your collection of HTML5 games from one page.

## 🌟 Features

- **Game List**: Displays all your games as buttons.
- **Search Functionality**: Filter games by name in real-time.
- **Clean UI**: Dark-themed, responsive layout.
- **Launch Games**: Opens games in fullscreen iframe inside a new window.

## 🧠 How It Works

- Games are stored in a JavaScript array with a `name` and `url`.
- Buttons are generated dynamically based on this list.
- The search box filters the visible games as you type.
- Clicking a button opens a new browser window that loads the game fullscreen.

## 🧩 Code Breakdown

### HTML

- Search bar (`<input type="search">`)
- Container for game buttons (`<div id="buttonsContainer">`)

### CSS

- Dark background, rounded buttons, hover effects
- Responsive layout with flexbox
- Font styling for readability

### JavaScript

```js
const games = [
  { name: "2048", url: "2048.html" },
  { name: "Drive Mad", url: "drivemad.html" },
  // more games...
];
