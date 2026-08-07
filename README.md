# Keystroke — Typing Practice Game

A modern, gamified typing practice app built with plain HTML, CSS, and JavaScript — no frameworks, no build step, no dependencies. Open the file and it just works, on desktop or mobile.

## Features

- **Timed sessions** — 30s, 1 min, 3 min, 5 min, or a custom duration
- **63 built-in passages** across 7 categories (General, Technology, Programming, Science, Literature, Quotes, Stories) and 3 difficulty levels (Beginner, Intermediate, Advanced)
- **Live stats** — WPM, CPM, accuracy, mistakes, time remaining, progress bar
- **Level system** — 100+ levels with XP, coins, and a level-up animation
- **Achievements** — badges like Bronze/Silver/Gold Typist, Speed Demon, Accuracy Master, 7-Day Streak
- **Daily challenge** — a new passage each day with bonus rewards
- **Local leaderboard** — your personal best sessions, ranked
- **Keyboard heatmap** — see which keys you mistype most
- **6 themes** — Ink & Ribbon (default), Light, Cyberpunk, Neon, Minimal, Retro Terminal
- **Sound & confetti** — built with the Web Audio API and canvas, no external audio/asset files
- **All progress saved locally** — via `localStorage`, no account or backend needed

## Getting started

No installation required.

1. Download `typing-practice.html`
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)

Or, once this is on GitHub, turn on **GitHub Pages** (see below) and share a live link instead of the file.

## Project structure

```
.
├── typing-practice.html   # the entire app — HTML, CSS, and JS in one file
├── README.md
└── LICENSE
```

## Tech notes

- Pure vanilla JavaScript, no frameworks or build tools
- All fonts loaded from Google Fonts (`@import` in the CSS); everything else — sound, confetti, data — is self-contained
- Data persistence via `localStorage` under the key `keystroke_profile_v1`

## License

MIT — see [LICENSE](LICENSE).
