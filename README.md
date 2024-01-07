# Little Link + QR Codes Template

## Deployments

With custom domain: [vercel](https://vercel.com/dashboard)

Otherwise will use GH Pages via Actions

## Current Sites

[1man1.band](https://www.1man1.band) or [1man1band.com](https://www.1man1band.com)

## QR Codes

Link: https://doompony.github.io/REPO
Initially generate with https://qrdex.io/
Format with `qr/scripts/main.py` to get base for ControlNet
Generated with A1111 WebUI

## Setup

1. Create repo from template and run `setup.sh` to configure local git
2. Add images/refs appropriately and app buttons
3. `python -m http.server -d dist 8000` to view locally at `http://localhost:8000/`
4. Deploy to Vercel
5. Generate QR Codes with A1111
6. Distribute QR Codes
