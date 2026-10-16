# Our Circle

**A party game for close friends — one phone, one host, nine modes.**

[![Play Now](https://img.shields.io/badge/play-now-brightgreen?style=for-the-badge&logo=github)](https://lostdeins.github.io/our-circle/)
[![Vanilla JS](https://img.shields.io/badge/vanilla-JS-yellow?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![No Dependencies](https://img.shields.io/badge/dependencies-none-blue?style=for-the-badge)](https://github.com/lostdeins/our-circle)
[![License: MIT](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)](LICENSE)

🇷🇺 [Читать на русском](README.ru.md)

---

## What is this?

Our Circle is a single-file HTML party game for companies and groups of friends. One person holds the phone and acts as host — reads questions aloud, marks votes, and passes the turn. Everyone else plays along.

It's designed for gatherings where people already know each other well (or think they do 😏).

## Features

- **9 game modes:** Most likely, Never have I ever, Truth or dare, Challenge, Imposter, Red or blue, Paranoia, Trivia, Describe the word.
- **2 languages:** English and Russian, switchable on the fly.
- **4 party themes:** Corporate, Bachelorette, Halloween, New Year — they change the questions in 4 of the 9 modes.
- **Tournament mode:** All points from all games add up across an evening.
- **Offline-first:** Works without internet. All data is stored locally in the browser.
- **No dependencies:** Pure HTML + CSS + JavaScript. No frameworks, no build step, no backend.
- **Dark & light themes:** Auto-detects your system preference on first launch.
- **Undo:** Take back the last scoring action within a round.
- **Shareable results:** Generate a PNG image with the final scoreboard.

## How to play

1. Open the [live demo](https://lostdeins.github.io/our-circle/) or download `index.html` and open it in any browser.
2. Pick a mode from the home screen.
3. Set up players (names and avatars) — the app remembers them for next time.
4. Choose a party theme (optional).
5. Start the game. The host reads aloud, the group plays.

## Tech stack

| Layer | Technology |
|---|---|
| UI | Vanilla HTML + CSS (Material Design 3 inspired) |
| Logic | Vanilla JavaScript (ES6+) |
| Storage | localStorage |
| Hosting | GitHub Pages |

## Files in this repository

- `index.html` — the entire game (UI, logic, content) in one file
- `README.md` — English documentation (this file)
- `README.ru.md` — Russian documentation
- `LICENSE` — MIT License

## Local development

No build step needed. Just open `index.html` in any modern browser.

If you want a local server, run `python -m http.server 8000` in the project folder and open `http://localhost:8000` in your browser.

## Contributing

This is a personal project, but feedback and ideas are welcome. Open an issue if you have a suggestion.

## License

MIT — do whatever you want.
