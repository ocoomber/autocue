# Autocue

Single-file static HTML teleprompter, served via GitHub Pages.

- **Entrypoint:** `index.html` — the entire app (vanilla JS, no build tools, no dependencies)
- **Serve locally:** open `index.html` directly in any browser, or use any static file server
- **Deploy:** push to `main`; GitHub Pages serves from root
- **Persistence:** settings (speed, font size, mirror) stored in `localStorage`
- **Keyboard (prompter mode):** `SPACE`/`Enter` play/pause · `↑`/`↓` adjust speed · `+`/`-` adjust font size · `ESC` back to edit
- **No tests, no lint, no typecheck, no CI, no package.json, no build step**
