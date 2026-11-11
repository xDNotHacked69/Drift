# Drift

**A small place to play.** Twenty-six tiny worlds for a little focus, a little chaos, and a little calm.

**Live demo:** [xdnothacked69.github.io/Drift](https://xdnothacked69.github.io/Drift/)

Drift is a self-contained browser arcade built with vanilla HTML, CSS, and JavaScript. There is no build step, package manager, account, backend, or installation required.

## Play

1. Download or clone this project.
2. Open `index.html` in a modern browser (Chrome, Edge, Firefox, or Safari).
3. Pick a game and drift for a while.

The app is designed to run locally. Game data stays in the browser that you play in.

## The game library

### Reflex

- Orbit Flap
- Circle Run
- Drift Dodge
- Snake
- Breakout
- Pong
- Stack
- Reaction Time
- Gravity Flip
- Pulse

### Brain

- Number Guesser
- Word Guesser
- Hangman
- Memory Match
- Simon
- Code Breaker
- Typing Test
- Higher or Lower

### Puzzle

- 2048
- Sliding Puzzle
- Lights Out
- Minesweeper
- Connect 4
- Tic-Tac-Toe

### Zen

- Breathe
- Ripples

## Features

- **One consistent game experience:** shared pause, restart, home, controls, theme colours, and sound behaviour.
- **Personalisation:** seven themes plus Auto, accent colour, glass/flat/outlined cards, and font choices.
- **Atmosphere controls:** background speed, grain, blur, floating particles, soft cursor, and reduced motion.
- **Daily play:** seeded reflex challenges and a daily Word Guesser.
- **Coder touches:** command palette, optional Vim-style movement keys, activity heatmap, focus/break timer, and personal-best scoreboard.
- **Shareable scores:** create a score card image from a finished run.
- **Local-first saves:** settings, scores, streaks, and daily progress are stored in `localStorage`.
- **Backup tools:** export and import your local data as JSON.
- **Responsive layout:** usable on desktop and mobile-sized screens.
- **No third-party runtime dependencies:** the app is a single HTML file and works offline.

## Keyboard shortcuts

| Shortcut | Action |
| --- | --- |
| `Ctrl` / `Cmd` + `K` | Open the command palette |
| `P` | Toggle wallpaper mode |
| `Esc` | Close the current game or panel |
| `H` `J` `K` `L` | Optional Vim-style movement (enable in Settings) |

Individual games may also offer their own keyboard or pointer/touch controls. The in-game controls are the source of truth for each game.

## Privacy and saved data

Drift does not send game activity to a server. Settings, scores, streaks, and daily progress are stored in the browser's local storage on the device where you play. This data does not automatically sync between browsers or devices.

Use **Settings → Export JSON** to make a backup before clearing browser data or switching devices. Import only backup files you trust. **Reset local data** clears the Drift data stored in the current browser.

## Project structure

```text
Drift/
├── .github/
│   └── workflows/
│       └── pages.yml
├── index.html   # Complete app: markup, styles, and game logic
└── README.md    # Project documentation
```

## Customising the project

The UI, styles, game library, and game logic live in `index.html`. Open it in a code editor and search for the relevant section or game name. Because this is a no-build project, save the file and refresh the browser to see changes.

## Deploying with GitHub Pages

This repository includes a GitHub Actions workflow that publishes the site whenever a commit is pushed to `main`. The deployment is handled through GitHub Pages; check the **Actions** tab for the latest build and deployment status.

## Compatibility

Use a recent version of Chrome, Edge, Firefox, or Safari. Some browser features (such as vibration, system sharing, or local storage) depend on device and browser support; Drift keeps them optional and provides fallbacks where possible.

---

Made for the in-between. **Enjoy the drift.**
