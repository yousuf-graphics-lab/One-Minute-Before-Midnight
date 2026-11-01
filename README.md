# One Minute Before Midnight

A playable, browser-based prototype for a compact Android horror mystery. Wake in a shifting room, search for the brass key and a changing three-digit code, keep your noise down, and escape before the minute is up. Each run adds another fragment to the story.

## Play

Open `index.html` directly, or serve this folder from a local web server:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`. No build step or dependencies are required. The layout adapts to mobile and desktop screens; the scene hotspots are touch-friendly.

## Prototype notes

- 60-second survival loop, countdown HUD, noise/threat meter, key + randomized code puzzle, repeatable runs, and a short evidence trail.
- The artwork is an original stylized room illustration in `public/room-art.png`.
- Ambient tone is optional and created in-browser with the Web Audio API; the game remains silent unless enabled.
- This is a web prototype, not a packaged Android/Play Store release. It can be wrapped for Android using a WebView/Capacitor workflow after platform-specific testing and store preparation.
