# Petra AI Now (Bolt variant)

## Overview

Lighter packaging of the **Petra AI Now** landing page (same brand, copy, and Three.js scroll experience as `petra-3d-site`), aimed at quick static hosting with a smaller file tree.

## Purpose

Same as `petra-3d-site`: convert visitors to YouTube / X for Petra AI Now (AI news, agent tools, build-with-AI tutorials).

## Features

- Hero + marquee + video card + pillars + stack + final CTA
- WebGL particle background with scroll-driven camera
- GSAP reveal animations
- `assets/` holds profile + thumbnail images

Compared with `petra-3d-site`, this tree omits the heavier `vendor/` and `shots/` folders; libraries are expected via the imports/CDN pattern used in this variant’s HTML/JS.

## Tech stack

- Static HTML/CSS/JS + Three.js / GSAP
- No backend

## Run / deploy

```bash
python3 -m http.server 8080
# open http://localhost:8080/
```

Use `petra-3d-site` if you need vendored libraries and recorded shot media in-repo.

## Notes

Creative/brand site for the Petra AI Now channel.
