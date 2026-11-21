# test-site

A modern "Hello, World" landing page featuring an interactive 3D Earth globe
(Three.js/WebGL) with auto-rotation, drag-to-rotate, atmosphere glow, and a
starfield backdrop.

Open `index.html` directly in a browser or serve it with any static server:

```
python3 -m http.server 8000
```

No build step required. Three.js and Earth textures load from a public CDN;
if unavailable, the page degrades gracefully with a styled fallback message.
