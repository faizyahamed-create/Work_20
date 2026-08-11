# 3D Wizard Chess

A browser-based 3D wizard-themed chess prototype built with Three.js.

## Included now

- Real-time 3D scene rendered in the browser
- Orbit camera with zoom
- Fantasy-themed board and pieces
- White/black starting setup
- Click-to-select pieces
- Basic destination movement prototype
- Turn indicator and reset button

## Run

Open `index.html` from a static web server. Because the game imports Three.js from a CDN, a local HTTP server is recommended.

Example:

```bash
cd wizard-chess
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Next steps

- Replace placeholder pieces with detailed 3D wizard/creature models
- Implement complete chess rules and check/checkmate
- Add capture animations and magical spell effects
- Add sound and music
- Add AI opponent and multiplayer
- Add responsive touch controls
