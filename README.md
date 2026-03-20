# SSF2 v0.9 (Ruffle)

Minimal static package to run `SSF2 v0.9` in browser with Ruffle.

## Project structure

- `index.html`: main loader page
- `ssf2v09.swf`: game SWF file used by `index.html`
- `data/`: external `DAT*.ssf` assets required by the game

## Run locally

Use any static server, for example:

```powershell
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Deploy to GitHub Pages

1. Create a new GitHub repository.
2. Push this folder content to `main` branch.
3. In repository settings, enable **Pages** from branch `main` and folder `/ (root)`.
4. Open the generated Pages URL.

## Notes

- Debug/test files and browser temp profiles are intentionally excluded via `.gitignore`.
- Keep `data/` and `ssf2v09.swf` at root level unless you also update paths in `index.html`.
