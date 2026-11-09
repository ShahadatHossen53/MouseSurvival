# Mouse Survival

This project is a browser-based arcade survival game built with HTML, JavaScript, p5.js, and Matter.js. The goal is to survive as long as possible by moving a blue player orb around the arena and avoiding incoming danger balls.

## Included files

- `Mouse Survival.html` — original game file
- `Mouse Survival v2.html` — second version
- `Mouse Survival v2 by ChatGPT.html` — the main version in this workspace, with additional polish and gameplay behavior
- `index.html` — entry page or launcher

## How to play

1. Open the main game file in a browser.
2. Use the mouse or keyboard to move the player.
3. Avoid the red danger balls.
4. Survive waves and score as long as possible.
5. Try to beat your local high score.

## Controls

- Move: mouse position / pointer movement
- Pause or menu actions: on-screen buttons and keyboard prompts
- Restart: follow the in-game menu or restart option

## Run locally

Because this is a plain browser game, there is no installation step required:

1. Open the project folder in a browser.
2. Double-click the desired HTML file, or serve the folder with a local web server if preferred.
3. If you use a local server, a typical command is:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Notes

- The game loads external libraries from a CDN, so an internet connection is needed for the first load.
- High scores are stored in browser local storage.
- This is a lightweight front-end project intended for quick play and experimentation.
