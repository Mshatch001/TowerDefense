# Fantasy Tower Defense – Arcane Forest

A small 2D tower defense prototype built as a single-page HTML5 canvas game.

## Assets
- Sprites now live under `assets/images/` as standalone `.svg` files.
- `index.html` loads sprites from a manifest and waits for every image to finish before starting the game loop.
- Add new sprites by dropping files into `assets/images/` and appending an entry to the manifest array in `index.html`.

## How to play
Open `index.html` in a modern browser. The status bar shows asset loading progress; the scene renders once all sprites are ready.
