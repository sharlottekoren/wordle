# Wordle

A browser-based clone of Wordle, built with HTML, CSS, and JavaScript.

## How to play

Open [wordle.html](wordle.html) in a browser and start typing.

- Guess the hidden 5-letter word in 6 tries.
- Type letters using your keyboard or by clicking the on-screen keyboard, then press **Enter** to submit a guess.
- Use **Backspace** to delete the last letter.
- After each guess, tiles and keyboard keys are colored to show how close you were:
  - **Green** — the letter is in the word and in the correct position.
  - **Yellow** — the letter is in the word but in the wrong position.
  - **Gray** — the letter is not in the word.
- The word is chosen at random each time the page loads, and guesses are validated against a word list.

## Running locally

No installation or build tools are required. Just open the HTML file directly:

```text
wordle.html
```

## Project structure

- [wordle.html](wordle.html) — page structure and layout
- [wordle.css](wordle.css) — styling for the board and keyboard
- [wordle.js](wordle.js) — game logic: word selection, input handling, guess validation, and tile/keyboard colouring
