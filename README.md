# Drift

A calm little arcade. Thirteen small games on a slowly drifting, ambient background, built as a single HTML file with no dependencies.

## Features

- Ambient background that cross-fades between colours, with film grain and optional floating dust
- 7 themes plus Auto, which follows your time of day, and a custom accent colour
- Local accounts: just a name and a colour, with no email and no password
- Profile with time played, sessions, wins, per-game stats, best scores, day streak and an activity heatmap
- Command palette (Ctrl/Cmd + K), wallpaper mode (P) and an optional soft cursor
- Settings for card style, typeface, drift speed, grain, sound and clock format

## Games

Orbit Flap, Snake, Breakout, Reaction Time, Number Guesser, Word Guesser, Hangman, Memory Match, Simon, 2048, Lights Out, Tic-Tac-Toe and Breathe.

## Run it

Open `index.html` in any modern browser. There is nothing to install or build.

## Shortcuts

- Ctrl/Cmd + K: command palette
- P: wallpaper mode
- Esc: close or go back
- Snake and 2048 also accept WASD and hjkl

## Notes

- Accounts, settings and scores are saved in your browser's local storage, so they stay on your device and do not sync between browsers.
- Fonts (Inter and JetBrains Mono) load from Google Fonts, with system fonts as a fallback when offline.

## Built with

HTML, CSS and vanilla JavaScript. Canvas for the background and some games, and the Web Audio API for sounds.
