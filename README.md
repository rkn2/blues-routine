# Blue's Routine Clues

A Blue's Clues-themed interactive routine chart for kids, built as a single HTML file and hosted on GitHub Pages.

**Live URL:** https://rkn2.github.io/blues-routine

## What it does

- Two tabs: **Bedtime** and **Morning**
- Tap each task to check it off
- Progress bar fills as tasks are completed
- Celebration message when all tasks are done
- Works as a home screen app on iPhone (Safari → Share → Add to Home Screen)

## Bedtime routine
1. Brush your teeth
2. Go pee
3. Put clothes in the laundry bin
4. Read your book

## Morning routine
1. Eat breakfast
2. Get dressed
3. Brush your teeth
4. Pack your backpack

## Rebuilding from scratch

Everything is self-contained in `index.html` — no dependencies, no build step.

1. Clone this repo
2. Edit `index.html` — the task lists are in the `ROUTINES` object near the bottom of the file
3. Commit and push to `main` — GitHub Pages updates automatically within ~1 minute

## Updating tasks

Open `index.html`, find the `ROUTINES` object in the `<script>` tag, and edit the `tasks` arrays:

```js
tasks: [
  { icon: "🪥", text: "Brush your teeth" },
  ...
]
```
