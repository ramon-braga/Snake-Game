# Snake Game

This is a simple Snake Game implemented using HTML, CSS, and JavaScript.

## Introduction

The Snake Game is a classic arcade game where players control a snake to collect food and grow while avoiding collisions with the snake's own body and the game boundaries.

## HTML Structure

The HTML structure defines the game's layout and elements:

- **Meta Tags:** Standard metadata for character set and viewport settings.
- **CSS Links:** Links to external stylesheets for styling the game.
- **Score Display:** A `<div>` element displaying the player's score.
- **Game Over Screen:** A `<div>` containing "Game Over" text, final score display, and a "Play again" button.
- **Canvas Element:** A `<canvas>` element used for rendering the game graphics.
- **JavaScript Script:** A `<script>` tag linking to the JavaScript logic (`script.js`) for the game.

## CSS Styles

The game's visual styles are defined using CSS:

- **Font:** The "Poppins" font from Google Fonts is imported for consistent typography.
- **Global Styles:** Global styles such as margin, padding, and font-family are applied to all elements using `*`.
- **Background:** The background color, layout, and text color are defined for the game area.
- **Score Display:** Styles for the score display elements, including font size and alignment.
- **Game Over Screen:** Styles for the game over screen, positioning, and text formatting.
- **Button:** Styles for the "Play again" button, including border, padding, font size, and color.

## JavaScript Logic

The JavaScript code (`script.js`) provides the core functionality of the Snake Game:

- **Canvas Rendering:** The game graphics are drawn on the canvas element.
- **Snake Movement:** The snake's movement is controlled based on user input (arrow keys).
- **Food Generation:** Random food items are generated on the grid for the snake to eat.
- **Collision Detection:** The game checks for collisions with walls and the snake's own body.
- **Scoring:** Players earn points for eating food, and the score is displayed.
- **Game Loop:** The game continuously updates its state using a game loop implemented with `setInterval`.

## Gameplay

Gameplay involves controlling the snake and collecting food while avoiding collisions. Here's how to play:

- **Controls:** Use keys ("W," "A," "S," "D") to change the snake's direction.
- **Objective:** Eat the food to grow the snake and earn points.
- **Collision:** Avoid collisions with the game boundaries and the snake's own body.
- **Game Over:** When the game ends due to a collision, a "Game Over" screen is displayed with your final score. Click "Play again" to restart.
