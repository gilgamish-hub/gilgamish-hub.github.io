# gilgamish-hub.github.io

Source of my portfolio: **[gilgamish-hub.github.io](https://gilgamish-hub.github.io)**

One hand-written HTML file with no frameworks and no build step:

- The 3D core at the top is drawn on a `<canvas>` with plain JavaScript: an icosphere split into 320 triangles, displaced by moving waves, lit by a light that follows the cursor and sorted back to front each frame.
- The accent colour is a single CSS variable (`--h`) that JavaScript moves with the pointer and the scroll position.
- Sections appear with an `IntersectionObserver`. When the visitor's system asks for reduced motion, the page switches to a calmer mode (slower hero, fade-only reveals) instead of switching animation off.
- Screenshots are WebP; the whole page loads in well under 1 MB.

Hosted on GitHub Pages from the `main` branch.
