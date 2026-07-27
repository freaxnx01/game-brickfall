# Brickfall 🧱

An 8-level Arkanoid-style brick-breaker with a dark "Nocturne" UI — paddle, ball physics, power-up capsules, laser mode, combo scoring, and synthesized retro sound.

**▶ Play it here: `https://github.freaxnx01.ch/game-brickfall/`**

![Dark arcade UI](https://img.shields.io/badge/style-nocturne%20arcade-9184d9) ![Single file](https://img.shields.io/badge/build-none%20needed-8fd8e8) ![License](https://img.shields.io/badge/license-MIT-bfe3b2)

## Features

- **8 hand-designed levels** — ROWS, CHECKER, PYRAMID, FORTRESS, DELTA, RING, BUNKER, CORE
- **Brick variety** — standard, armored (2–3 HP), indestructible walls, and explosive bricks that chain-react and shake the screen
- **5 power-up capsules** — Wide paddle, Multi-ball, Slow-mo, Laser (twin bolts), Extra life
- **Combo scoring** — multiplier climbs the longer you keep a rally alive
- **Synthesized sound effects** (Web Audio, no audio files)
- 960×640 canvas playfield with ball trails, particles, and screen shake
- High score saved locally

## Controls

| Input | Action |
|---|---|
| Mouse / ← → / A · D | Move paddle |
| Space | Launch ball / fire laser / continue |
| P / Esc | Pause |
| M | Mute |

## Running locally

Open `index.html` in any modern browser — that's it.

## Tech

Single-file HTML5 canvas game, built with a small custom `sc-if` / `sc-for` templating runtime (`support.js`) that drives the HUD and overlay markup around the canvas game loop. No build tools, no external game framework.

## License

MIT — see [LICENSE](LICENSE).
