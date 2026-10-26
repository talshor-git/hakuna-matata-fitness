# AGENTS.md

Hakuna Matata — Hebrew RTL fitness PWA. Single-file static site (`index.html`)
served from GitHub Pages (`main` branch, root). No build step, no backend —
data lives in `localStorage`.

## Commands
- `python3 -m http.server 8000` — serve locally (then open http://localhost:8000)
- `git push origin main` — deploys (GitHub Pages builds automatically)

## Conventions
- UI is Hebrew + RTL; all user-facing copy is in Hebrew. Rubik font.
- **Bump the version on every change**: bump `VERSION` in `index.html`
  (minor +1, patch stays 0), e.g. `1.3.0` -> `1.4.0`.
- Commit messages: concise Hebrew describing the change.
- After every change: commit and `git push origin main` — that is the deploy.
- Keep everything inside `index.html` unless a new module is clearly warranted.
- No comments unless necessary.
