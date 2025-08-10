# Rendering Mermaid Diagrams

## Option A — GitHub Actions (no local setup)
- Push the repo to GitHub.
- The workflow `.github/workflows/mermaid.yml` renders every `.mmd` to `figures/svg/*.svg` and `figures/png/*.png` on each push.
- The bot will commit the generated images back to the repo.

## Option B — Local render (Node required)
```
# From the repo root:
npm run render:all
```
This uses `@mermaid-js/mermaid-cli` via `npx` so you don't need to install globally.

## Where to edit
- Edit the source `.mmd` in `figures/`.
- Generated files appear in `figures/svg/` and `figures/png/`.
