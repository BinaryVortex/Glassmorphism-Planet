# Glassmorphism-Planet

Glassmorphism Planet built using HTML, CSS and JavaScript.

![Preview](screenshot.svg)

Live demo
- Open `index.html` in your browser (double-click or drag into a browser tab).
- Or serve the folder using a local HTTP server, for example:

  - Python 3: `python -m http.server 8000`
  - Node (http-server): `npx http-server`

Features
- Pure HTML/CSS with minimal JavaScript.
- Glassmorphism-inspired planet with soft highlights, craters and a subtle ring.
- Responsive: sizes use modern units (clamp, aspect-ratio) so the scene scales nicely.

Files
- `index.html` — markup for the planet and ring.
- `style.css` — all styling and visual effects (glass highlights, shadows, ring).
- `screenshot.svg` — lightweight SVG preview included in the README.

How to customize
- Change colors and shadows in `style.css` to get different moods.
- Tweak the crater sizes and positions in the `.crater > *` rules.
- Add animation by animating transforms or filters on `.planet` or `.circle`.

Credits
- Built by BinaryVortex — inspired by glassmorphism design trends.

License
- MIT
