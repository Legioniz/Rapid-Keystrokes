# Rapid Keystrokes

A small browser-based typing-speed game built with plain HTML, CSS, and JavaScript.

## How it works

1. Open the page and choose **Start**.
2. Start a 60-second typing round.
3. Type the displayed programming and technology terms exactly as shown. Correct entries are counted and the next random term appears.
4. When the timer ends, the page displays an estimated words-per-minute result.

The prototype also includes short Web Audio feedback, a loading screen, a restart control, and an animated page background.

## Run locally

No package manager, build step, account, or backend is required.

- Download or clone the repository.
- Open `index.html` in a modern browser.
- Keep `app.js`, `style.css`, and the included audio file beside `index.html`.

The page uses Google Fonts when they are reachable; system font fallbacks are declared in the stylesheet.

## Project files

| File | Purpose |
|---|---|
| `index.html` | Game page, start screen, input, timer, and result elements |
| `style.css` | Layout, responsive styles, and visual effects |
| `app.js` | Word selection, 60-second round, scoring, and audio cues |
| `stgbg.mp3` | Included audio track |

## Current scope and limitations

This is an early, self-contained browser project. It uses a fixed word list in the source code, does not create user accounts, and does not save scores or maintain a leaderboard. The displayed WPM is calculated from the number of accepted entries during the timed round; it is a simple practice score, not a formal typing assessment.

## License and ownership

Copyright © 2023 Project contributors. No separate open-source license is currently included; contact the repository owner before redistributing the project.
