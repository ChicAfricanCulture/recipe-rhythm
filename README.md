# Recipe Rhythm

A tiny, mobile-first browser game that turns African food knowledge into a cognitive rhythm challenge.

You see a recipe sequence briefly — then it disappears. Ingredients float around the screen like bubbles. Tap them in the correct order before the timer runs out.

This project is part of an unique African Gaming System: using **cognitive load** (attention + timing + interference) as the “action,” with African food as the cultural layer.

## Play

- Open the GitHub Pages link (once enabled), or run locally:
  - Download the repo
  - Open `index.html` in your browser

## How to Play

1. A recipe sequence appears (e.g., `TOMATO → ONION → PEPPER → RICE`)
2. The sequence disappears
3. Tap the floating ingredient bubbles **in the exact order**
4. Wrong tap:
   - time penalty
   - sequence resets to step 1

## Levels (Current)

- **Level 1:** Black & white bubbles, short sequence (3 steps)
- **Level 2:** Black & white, longer sequence (4 steps)
- **Level 3:** Color noise is introduced (text colors change), but the rule stays the same: **tap the correct WORD**

Planned: expand to Level 6 using the same progression style (speed, density, similarity, interference).

## Why this exists

African food is often boxed into “kitchen-only” contexts. This game puts it in a different space: casual play.

No lectures, no heavy framing — just a game that happens to be built from African food knowledge.

## Tech

- Single-file HTML/CSS/JS
- Canvas rendering
- Mobile-first layout
- No external libraries

