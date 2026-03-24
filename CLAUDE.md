# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a collection of browser-based games built with vanilla HTML, CSS, and JavaScript — no build tools, no frameworks, no dependencies. Each game is a self-contained `.html` file.

## Running Locally

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080/<game>.html` in a browser.

## Repository & Version Control

- GitHub repo: https://github.com/blerimrexha/browser-games
- Always commit with clean, descriptive messages
- Push after each meaningful feature or game addition
- Use `main` as the default branch

## Code Style

- Vanilla JS only — no frameworks or libraries
- All game logic, styles, and markup in a single `.html` file per game
- Retro/pixel aesthetic preferred: dark backgrounds, limited color palettes, crisp animations
- CSS animations over JS-driven animation loops where possible
