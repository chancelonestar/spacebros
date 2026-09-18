# SpaceBros

A single-file asteroids-style game — no frameworks, no dependencies, just an HTML file and a canvas. Open it in any browser and fly.

![SpaceBros screenshot](https://raw.githubusercontent.com/chancelonestar/spacebros/master/screenshot.png)

## Play

Open `ship.html` in your browser. That's it — no install, no build step, no server needed. Works offline.

Or run it from the command line if you want to feel like you're back in 1999:

```bash
chromium --kiosk file:///path/to/spacebros/ship.html
```

## Controls

| Key | Action |
|-----|--------|
| `← →` | Rotate |
| `↑` | Thrust |
| `↓` | Brake |
| `Space` or click | Fire laser |

## Features

- **Starfield** — multi-layer parallax with twinkling stars and nebula washes
- **Asteroids** — irregular polygons wandering in from the edges, spinning on their own rhythm
- **Ship** — you fly it, you shoot it, you try not to let it die
- **Energy shield** — hits cost 20 energy; at zero the ship explodes
- **Score** — 100 points per asteroid vaporized
- **Game over → Play Again** — the loop continues

## Project files

| File | What it is |
|------|------------|
| `ship.html` | The full game — open this one |
| `starfield.html` | Just the starfield (standalone demo) |

## Built with

Vanilla HTML5 Canvas + JavaScript. No libraries, no build tools, no npm. Just code and a browser.

## License

Free to play, free to hack on.

---

*Made with 💚 in Omarchy — green CRT phosphor on a Friday night.*
