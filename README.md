# Smart Tactile Controller

A five-key USB-C macro pad built around an ESP32-C3 — from KiCad schematic to
fabricated PCB and 3D-printed enclosure.

**[View the project page →](https://YOUR-USERNAME.github.io/smart-tactile-controller/)**

## What's in this repo

| Path | Contents |
|---|---|
| `index.html`, `style.css` | The GitHub Pages project site |
| `assets/` | Schematic and PCB layout images used on the site |
| `hardware/` | *(add your `.kicad_sch` / `.kicad_pcb` files here)* |

## Spec sheet

- **MCU** — ESP32-C3-MINI-1 (RISC-V, Wi-Fi + BLE)
- **Power** — USB-C, 5V in → AP2112K-3.3 LDO → 3.3V rail
- **Input** — 5× Cherry MX-compatible switches, 19.05mm pitch
- **PCB** — 2-layer, 58 × 85mm, 0402 SMD passives
- **Enclosure** — 3D-printed, modeled in Fusion 360
- **Fabrication** — PCBWay, $5 per board

## Deploying this page on GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Pick the `main` branch and the `/ (root)` folder, then **Save**.
5. GitHub gives you a live URL within a minute or two, at
   `https://YOUR-USERNAME.github.io/REPO-NAME/`.

No build step needed — it's a static `index.html` + `style.css` site.

## Local preview

Open `index.html` directly in a browser, or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## License

Add a `LICENSE` file here if you want to make the hardware/design files
reusable (the [CERN-OHL](https://cern-ohl.web.cern.ch/) or
[MIT](https://choosealicense.com/licenses/mit/) licenses are common choices
for open hardware projects).
