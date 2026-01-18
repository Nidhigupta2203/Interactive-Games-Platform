# Interactive Games Platform

A web-based platform featuring two classic browser games — **Snake** and **Hangman** — along with simple login/signup functionality and a basic homepage.  
This project focuses on practicing core **HTML, CSS, JavaScript**, with basic **PHP** integration for UI flow and authentication concepts.

---

## Overview

This repository includes:

- Snake Game (grid‑based snake that grows as it eats food).
- Hangman Game (word guessing with category‑based hints).
- Simple Login and Signup pages plus a static homepage.

The goal is to practice core **HTML, CSS, JavaScript and a bit of PHP** for basic web game logic and UI.


## Snake Game

### Description

In the Snake game, the player controls a snake moving on the screen and tries to eat randomly appearing blocks. 
Each time the snake eats a block, it grows longer and the game ends if it hits the wall or its own body.

### Features

- Snake grows as it eats food.  
- Simple keyboard controls (arrow keys).  
- Game over when the snake collides with the wall or itself.

### How to Play

- Use the arrow keys (Up, Down, Left, Right) to move the snake.  
- Eat the blocks to increase your score and length.  
- Avoid hitting the boundaries or your own tail.

---

## Hangman Game

### Description

Hangman is a word‑guessing game where the player guesses a hidden word one letter at a time.
The game provides a hint like category (fruit, vegetable, etc.) and allows only a limited number of wrong guesses.

### Features

- Category‑based hints for the secret word.  
- Counts wrong guesses and ends the game when the limit is reached.  
- Reveals the correct word if the player fails to guess.

### How to Play

- Read the hint (for example, “It’s a fruit”).  
- Enter letters one by one to guess the word.  
- Try to guess the full word before you run out of allowed wrong guesses.

---

## Project Structure

```text
Interactive Games Platform/
├── Login/        # Login page files
├── Signup/       # Signup/registration page files
├── homepage/     # Landing / home UI
├── snake/        # Snake game HTML, CSS, JS
├── hangman/      # Hangman game HTML, CSS, JS
└── db/           # Any PHP/db related files if used
```

## How to Run

Clone or download this repository.

Open the relevant HTML files (e.g. homepage/index.html, snake/index.html, hangman/index.html) directly in your browser, or use a simple local server / Live Server in VS Code.

Interact with login/signup (if configured) and then navigate to the game pages.

If you use PHP or database features from the db folder, run the project on a local server environment such as XAMPP/WAMP and place the project inside the server’s htdocs/www directory.
  

## Future Improvements

- Connect login/signup to a real database for user accounts.
- Add scoreboards/high scores for both games.
- Improve mobile responsiveness and game UI styling.
