# Lush Orla Scroll Experience

A standalone scroll driven fashion prototype for the Lush / Orla concept.

## Run locally

Serve this directory over HTTP so the video and browser media APIs work:

```powershell
python -m http.server 4173
```

Then open `http://127.0.0.1:4173/`.

## Interaction

- Scroll maps to the Orla reference video timeline.
- The Craft section reveals material studies and garment notes.
- The Shop section presents the outfit as separate pieces.
- The fixed Lush wordmark fades before the Shop cards enter the viewport.

## Asset notes

The page uses the included poster, reference video, wordmark and Shop product renders. Fonts and five material-study images are loaded from their existing public URLs in `index.html`.

This repository is a public prototype. Image, video, font, and model rights should be confirmed before redistribution or commercial use.