# Gorlock Catch 🧺☁️

A simple browser-based catch game where Gorlocks fall from the clouds and you have to catch them in your basket before they hit the ground.

---

## How to Play

Move your basket left and right to catch the Gorlocks as they fall from the clouds. Catch enough before you run out of misses to win.

- **Goal:** Catch **15 Gorlocks** to win
- **Misses allowed:** Up to **8** misses before game over
- The game gets progressively harder — Gorlocks fall faster as your score increases

---

## Controls

| Input | Action |
|---|---|
| `←` / `→` Arrow Keys | Move basket left / right |
| `A` / `D` Keys | Move basket left / right |
| Click & Drag | Drag basket with mouse or finger |

---

## Setup

1. Download or clone the files into the same folder:
   - `index.html` — the game
   - `meme.png` — the Gorlock face image (place this next to the HTML file)

2. Open `index.html` in any modern browser. No installation or server required.

> **Note:** If `meme.png` is missing, the game falls back to a 🙂 emoji as the falling object.

---

## Game Rules

- Press **Start** to begin
- Gorlocks spawn from clouds at the top of the screen and drift downward with a slight wobble
- Position your basket under a falling Gorlock to catch it
- A Gorlock that reaches the bottom without being caught counts as a **miss**
- Catch 15 → **You win**
- Miss 8 → **Game over**

---

## Files

```
gorlock-catch/
├── index.html   # Game (self-contained HTML + CSS + JS)
└── meme.png     # Gorlock face sprite
```

---

## Built With

- Vanilla HTML, CSS, and Canvas API — no frameworks or dependencies
- Fully responsive; works on desktop and mobile browsers
