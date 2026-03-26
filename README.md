# Tree Knockdown Game

A small single-file browser game built with plain HTML, CSS, and JavaScript.

The scene renders an animated tree on a full-screen canvas. Two launcher turrets sit near the bottom of the screen and fire projectiles toward the tree. When a projectile hits a branch, that branch and its child branches detach and fall, and the score increases.

## Features

- Single-file project with no build step and no dependencies
- Full-screen canvas rendering
- Procedurally generated animated tree
- Physics-style projectile motion and falling branches
- Mouse, drag, and keyboard controls
- Simple HUD with score and remaining branch count

## Controls

- Click a turret body to fire
- Drag a turret base left or right to reposition it
- Click the left or right arrow pads under a turret to move it
- Use `A` / `D` to move the left turret
- Use `J` / `L` to move the right turret

## Running Locally

Because this is a static HTML file, you can run it in either of these ways:

1. Open `tree.html` directly in your browser
2. Or serve the folder locally and open the page through `http://localhost`

Example using Python:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/tree.html
```

## Project Structure

- `tree.html`: the full game, including markup, styles, rendering, input handling, and game logic

## Tech

- HTML5 canvas
- Vanilla JavaScript
- Inline CSS

## Publishing To GitHub

This repository is already structured well for GitHub because it is minimal and self-contained. A reasonable next step is:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```

If you want, I can also add a `.gitignore`, a license, or a small screenshot section before you push it.
