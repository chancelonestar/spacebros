# SpaceBros

> Two-player asteroids. Blue vs green. WASD vs arrows. Same asteroid field.

![SpaceBros screenshot](https://raw.githubusercontent.com/chancelonestar/spacebros/master/screenshot.png)

## Play

Open `ship.html` in your browser. No install, no build step, no server — works offline.

Or fullscreen it for maximum intensity:

```bash
chromium --kiosk file:///path/to/spacebros/ship.html
```

## Controls

| | Player 1 (Blue) | Player 2 (Green) |
|--|------------------|-------------------|
| Rotate left | `A` | `←` |
| Rotate right | `D` | `→` |
| Thrust | `W` | `↑` |
| Brake | `S` | `↓` |
| Fire | `Space` | Left mouse click |

Both players share one keyboard. P2 also fires with a left-click on the canvas.

## Features

- **Two ships** — blue P1 spawns left-third, green P2 spawns right-third. Each has its own energy, score, and lasers.
- **Shared asteroid field** — both players shoot the same rocks. Laser hits credit the ship that fired (+100 score).
- **Energy shield** — 100 per ship. Asteroid collision costs 20. Ship explodes at 0.
- **Single death** — a destroyed ship is defeated; the other keeps playing until they're down too.
- **Game over** — when both ships are destroyed: P1 final score, P2 final score, combined total, and a PLAY AGAIN button.
- **Starfield** — three parallax layers of twinkling stars with nebula washes.
- **Slow asteroids** — slow drift, slow spin, organic wobble (built for shared-keyboard play, not speed-running).

## Version History

### v0.0.1 — Single Player
- One ship, one laser, one energy bar, one score
- Starfield, asteroids, ship with lasers, energy shield, game over/restart
- [Commit f97d794](https://github.com/chancelonestar/spacebros/commit/f97d794)

### v0.0.2 — Two Player
- Two ships: blue P1 (left-third) and green P2 (right-third)
- P1 controls: WASD + Space. P2 controls: Arrow keys + Left mouse click
- Each ship has its own energy bar and score (P1 top-left, P2 top-right)
- Shared asteroid field — both shoot the same rocks
- Ship-asteroid collision damages only the ship that collided
- Game over when both are destroyed — P1 final, P2 final, combined score, PLAY AGAIN
- [Commit 8c03516](https://github.com/chancelonestar/spacebros/commit/8c03516)

## Project Files

| File | What it is |
|------|------------|
| `ship.html` | The game — open this one |
| `starfield.html` | Standalone starfield demo |

## Built With

Vanilla HTML5 Canvas + JavaScript. No frameworks, no dependencies, no build step.

## License

Free to play, free to hack on.

---

*Made with 💚 in Omarchy — green CRT phosphor on a Friday night.*
