# thehabdash — Project Status

**Status:** GitHub Pages placeholder live. DNS configuration pending at registrar.

## What This Is

Placeholder page for thehabdash.com. Interactive 3D surface animation (Neovius/Gyroid blend) using p5.js WebGL, colored in CMYK process primaries on near-black. Adapted from dxn-here-now animation.

## Palette

- Background: `#0A0A0A`
- Layer 1: Cyan `#00AEEF` (alpha 215)
- Layer 2: Magenta `#EC008C` (alpha 155)
- Layer 3: Yellow `#FFF200` (alpha 70)

## Interactions

- Mouse position morphs surface shape (X = Neovius/Gyroid blend, Y = ripple)
- Click and drag to rotate
- Single click flicks the surface
- Double-click explodes outward

## Files

- `index.html` — animation page
- `CNAME` — custom domain config for GitHub Pages
- `.nojekyll` — disables Jekyll processing

## DNS Setup (manual, at registrar)

Add these A records for `thehabdash.com`:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```
Add CNAME: `www` → `septapod.github.io`

## URLs

- GitHub: https://github.com/septapod/thehabdash
- Pages (immediate): https://septapod.github.io/thehabdash/
- Custom domain (after DNS): https://thehabdash.com

## What's Left

- [ ] DNS configuration at registrar
- [ ] Verify custom domain resolves after propagation
