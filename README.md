# claude-space

## Cove Light Simulation (Section B, A8-01)

2D ray-tracing simulation of the cove lighting. Single static HTML file, no build step.

```
public/index.html   # deployed site (current version)
versions/           # frozen copies of earlier versions
vercel.json         # static deploy config (outputDirectory: public)
```

### Deploy on Vercel
1. Import this repo in Vercel (Framework Preset: **Other**).
2. Leave Build/Install commands empty. Output directory is read from `vercel.json`.
3. Production branch: `main`.

### Run locally
```bash
npx serve public
```

Before a major edit, copy `public/index.html` to `versions/` with the next version number.
