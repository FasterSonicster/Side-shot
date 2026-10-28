# STARFALL — Three.js Side-Scrolling Shooter

A browser-based 3D arcade shooter using Three.js.

## Controls
- **WASD / Arrow keys:** move
- **Space:** fire
- **P:** pause
- Touch devices have an on-screen directional pad and FIRE button.

## Run locally
Because the JavaScript uses ES modules, serve this folder through a local web server instead of opening `index.html` directly. For example:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Cloudflare Pages
This is a static site. Connect this GitHub repository to Cloudflare Pages, leave the build command blank, and set the output directory to `/`.

Three.js is loaded from jsDelivr; Google Fonts are optional decoration.