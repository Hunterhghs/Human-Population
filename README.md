# World Population Dashboard

**Animated data visualization of human population from 10,000 BC to the present day.**

Built with [Observable Plot](https://observablehq.com/plot) and D3.js. Self-contained single-file HTML — no build step required.

## Features

- Animated population curve tracing 12,000 years of human history
- Non-linear time axis — ancient millennia compressed, modern era expanded
- Camera tracking mode — sliding window follows the animated point
- 14 historical milestones (Agricultural Revolution through 8 billion)
- Linear and logarithmic y-axis scales
- Variable-speed animation with play/pause, step, and restart controls
- Hover tooltip with precise year and population values
- Keyboard shortcuts (Space, ← →, R, L, G, T)
- Responsive dashboard layout

## Data Sources

- **Ancient era (10,000 BC–1800):** HYDE 3.3, Gapminder Foundation
- **Modern era (1800–present):** UN World Population Prospects (2022 revision)

## Usage

Open `index.html` in any browser. No server or build tools required. For local development with live reload, serve with any static file server:

```bash
python3 -m http.server 8000
```

## License

H Heuristics © 2025
