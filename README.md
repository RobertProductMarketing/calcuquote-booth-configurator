# CalcuQuote — electronica 2026 Booth Configurator

Interactive 3D walkthrough and configurator for CalcuQuote's 6×6 m (36 m²) island stand at electronica 2026 (Munich, Nov 10–13). Single self-contained HTML file — no build step.

## Live demo

👉 https://robertproductmarketing.github.io/calcuquote-booth-configurator/

## Controls

- **Orbit** — drag to rotate, scroll to zoom, right-drag to pan.
- **Walk** — click "Walk", then WASD to move and mouse to look. Esc to exit.
- **Reset view** — back to the default camera.

## Configure (right-hand panel, collapsible — one section at a time)

- **Add objects** — drop in kiosks, TVs, counters, tables, chairs, sofas, plants, people, etc. Click an item in the scene to move (drag on floor), rotate, scale, duplicate, or delete it.
  - **Empty stand** — bare booth, clean slate.
  - **Reset layout** — restore the default setup.
  - **Clear added objects only** — remove dropped-in items, keep the configured furniture.
- **Upload graphics** — replace what's shown on monitor screens, logo panels, the back wall, or the overhead banner with your own PNG/JPG.
- **Stand shell / Banner / Screen / Kiosks / Meeting / Reception / Extras** — dimensions and toggles; the 3D scene rebuilds live.

## Publish to GitHub Pages

1. Create a new **public** repository.
2. Upload `index.html` (and this `README.md`).
3. **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)` → Save.**
4. Wait ~1 minute; the live link appears at the top of the Pages settings screen.

To update later: re-upload / commit `index.html`; Pages redeploys automatically.

## Notes

- Needs internet on first load (pulls three.js r128 from a CDN).
- Uploaded images live in each visitor's browser only — not saved or shared, and reset on refresh.
