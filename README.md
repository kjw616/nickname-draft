# Nickname Draft

A quick browser game: guess the NBA player behind the nickname. Four
difficulty levels change the format, not just the player pool.

![Difficulty selection screen](screenshot.png)

**Live demo:** _add GitHub Pages link here_

## How it plays

| Level | Format | Lives | Points per correct |
|---|---|---|---|
| Easy | Multiple choice (4 options), household names | None (10 questions) | +10 |
| Normal | — | — | +15 |
| Hard | — | — | +25 |
| Impossible | Type the player's name | — | +40 |

<!-- Fill in the dashes from the game's settings. -->

## Design notes

<!-- Fill these in. This is the part a UX reviewer reads most closely. -->

- **The idea:** _…_
- **Difficulty design:** _Why scale difficulty by format (multiple choice
  → typed answer) and lives rather than just harder players?_
- **Feedback & iteration:** _Who played it? What confused them?_
- **What I'd do next:** _…_

## How it's built

A single self-contained `index.html` (HTML/CSS/vanilla JS), no build step.
Nicknames sourced from player pages on Basketball-Reference.com.
