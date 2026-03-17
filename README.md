# 🦕 Dino Run

A browser-based clone of the Chrome offline dinosaur game. Built with vanilla HTML, CSS, and JavaScript — no dependencies, no build step.

**[▶ Play it live](https://tashil10.github.io/dinogame/)**

---

## Features

- Smooth physics with gravity and jump arc
- Procedurally generated cactus obstacles
- Increasing speed as score climbs
- High score tracking (session)
- Animated dino with walking legs
- Scrolling clouds
- Mobile-friendly (tap to jump)

---

## Controls

| Input | Action |
|-------|--------|
| `Space` / `↑` | Jump |
| Tap / Click | Jump |

---

## Getting Started

No install required. Just open `index.html` in any modern browser.

```bash
git clone https://github.com/Tashil10/dinogame.git
cd dinogame
open index.html   # macOS
# or
xdg-open index.html  # Linux
```

---

## Project Structure

```
dinogame/
└── index.html    # Entire game — HTML, CSS, and JS in one file
```

---

## How It Works

| Component | Details |
|-----------|---------|
| Rendering | Canvas (dino) + DOM elements (obstacles, clouds) |
| Physics | Simple Euler integration — gravity + vertical velocity |
| Collision | Axis-aligned bounding box (AABB) |
| Difficulty | Speed increases every 300 score points |
| Obstacles | Randomly spawned tall or wide cacti |

---

## Roadmap

- [ ] Sound effects
- [ ] Day/night mode
- [ ] Flying pterodactyls
- [ ] Persistent high score (localStorage)
- [ ] Mobile touch controls overlay

---

## License

MIT
