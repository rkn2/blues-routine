# Blue's Routine Clues

A Blue's Clues-themed interactive routine chart, built as a single self-contained HTML file hosted on GitHub Pages.

**Live URL:** https://rkn2.github.io/blues-routine

## What it does

- **Auto-detects time of day** — opens in Morning mode (5am–noon) or Bedtime mode (otherwise)
- Two tabs: **Bedtime** and **Morning**
- Tap each task to check it off — paw prints burst upward on each check
- Notebook-styled progress bar with a 🐾 emoji riding the fill
- Full celebration screen with confetti + spinning Blue when all tasks are done
- Adds to iPhone home screen via Safari → Share → Add to Home Screen (runs fullscreen, works offline after first load)

## Bedtime routine (4 steps)
1. 🪥 Brush your teeth
2. 🚽 Go pee
3. 🧺 Put clothes in the laundry bin
4. 📖 Read your book

## Morning routine (6 steps)
1. 🚽 Go pee first!
2. 🪥 Brush your teeth
3. 🥣 Eat breakfast
4. 👕 Put your clothes on
5. 👟 Put your shoes on
6. 🚗 Get in the car

## Visual modes

**Bedtime** — Dark navy background, 65 twinkling stars, glowing moon, Blue wiggles slowly (2.2s), gold checkmarks

**Morning** — Diagonal blue-stripe background, animated glowing sun, Blue wiggles fast (1.3s), blue checkmarks

## Celebrations

- **Bedtime:** "Sleep tight!" / "Blue found all the clues! Sweet dreams! 🌙"
- **Morning:** "Let's go! Yay!" / "Blue thinks you're a superstar today! ⭐"

## Rebuilding from scratch

Everything is in `index.html` — no build tools, no dependencies beyond Google Fonts.

1. Clone this repo
2. Edit the `R` object in the `<script>` tag to update task lists or celebration messages
3. Commit and push to `main` — GitHub Pages updates in ~1 minute
