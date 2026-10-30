# Crossword Builder

A dependency-free HTML/JS app that turns a list of words into a playable crossword puzzle.

## Usage

Open `index.html` in a browser (or serve the folder, e.g. `python3 -m http.server`).

Enter one word per line, optionally followed by a clue:

```
PYTHON: A snake or a programming language
BROWSER: Program used to view websites
KEYBOARD
```

Words without clues get a scrambled-letter hint. Spaces and punctuation in words are ignored.

## Features

- Generates a compact layout (many randomized attempts, best kept); words that can't connect are listed as "Couldn't fit"
- Type directly in the grid; Tab/Enter for next word, arrows to move, Space or re-click to switch direction
- Check, reveal word, reveal all, clear, new layout, print
