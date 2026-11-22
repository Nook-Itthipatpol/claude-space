# claude-space

## Cove Light Simulation (Section B, A8-01)

2D ray-tracing simulation of the cove lighting. Single static HTML file, no build step.

```
public/index.html             # home page (links to tools)
public/cove-light/index.html  # Cove Light Simulation (Section B, A8-01)
public/exam-room-lux/index.html # Exam Room 1 two-light lux map
public/assets/                # card thumbnails
versions/                     # frozen copies of earlier versions
vercel.json                   # static deploy config (outputDirectory: public)
```

### Deploy on Vercel
1. Import this repo in Vercel (Framework Preset: **Other**).
2. Leave Build/Install commands empty. Output directory is read from `vercel.json`.
3. Production branch: `main`.

### Run locally
```bash
npx serve public
```

To add a page: create `public/<name>/index.html`, add a card in `public/index.html`.
Before a major edit, copy the page to `versions/` with the next version number.
