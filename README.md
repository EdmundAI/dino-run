# Dino Run

A single-file recreation of the Chrome offline T-Rex game, with an orange dinosaur and green cacti.

Open `index.html` in any browser, or play the Vercel deployment.

## Features

- Orange T-Rex with run, jump, duck and dead poses
- Green cacti in groups of 1 to 3, small and large
- Pterodactyls from 450 points at three heights
- Speed ramps from 6 to 13
- Score, high score (saved in browser storage), flash every 100 points
- Day/night cycle every 700 points
- Sound effects generated with the Web Audio API (no audio files)

## Controls

| Key | Action |
|---|---|
| Space / Up arrow / tap | Jump (also starts and restarts the game) |
| Down arrow | Duck, or fast-drop while in the air |

## Deploy to Vercel

This is a static site with no build step. Import the repository in Vercel, leave **Framework Preset** as *Other* and the build command empty, and Vercel serves `index.html` from the root.
