# Fantasy Tower Defense – Arcane Forest

A small 2D tower defense prototype built as a single-page HTML5 canvas game.

## Assets
- Sprites now live under `assets/images/` as standalone `.svg` files.
- `index.html` loads sprites from a manifest and waits for every image to finish before starting the game loop.
- Add new sprites by dropping files into `assets/images/` and appending an entry to the manifest array in `index.html`.

## How to play
Open `index.html` in a modern browser. The status bar shows asset loading progress; the scene renders once all sprites are ready.

## Development

### Branching Strategy
- **main**: Production-ready code. Protected branch for stable releases.
- **dev**: Development branch for ongoing work. Use this branch for feature development and testing before merging to main.

### Workflow
1. Create feature branches from `dev` for new features
2. Test changes thoroughly on feature branches
3. Merge completed features into `dev`
4. When ready for release, merge `dev` into `main`
