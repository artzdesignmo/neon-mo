# Neon Mo

**A neon sign studio that glows as you type — free, offline, single HTML file.**

Type any text and watch it become a glowing neon sign: pick a tube font, a neon colour, a wall, and an animation — then download it as a PNG. No account, no upload, no backend. Everything runs in your browser.

## Screenshot

> Add `screenshot.png` (a screenshot of the app) to this repo — the demo image goes here once uploaded.

![Neon Mo demo](screenshot.png)

## Features

- **Live neon canvas engine** — multi-pass glow rendering (halo + coloured tube + white-hot centre line) drawn on Canvas 2D, so the PNG export looks exactly like the preview
- **6 tube fonts** — Dela Gothic, Monoton, Pacifico, Caveat, Orbitron, Clean Sans
- **10 neon colours** — pink, cyan, lime, amber, purple, red, blue, green, orange, white
- **3 tube styles** — Classic, Bold tube, Outline
- **4 procedural walls** — brick, dark wall, night sky, concrete (all drawn in code, no images)
- **Animations** — Steady, Pulse (breathing), Flicker (classic broken-sign flicker)
- **6 one-click presets** — OPEN, Café, Good vibes, Dream big, Love, Bar
- **Shuffle** — random sign in one click
- **PNG export** — 1024px wide, free; the export is a real render of the same canvas
- **Live stats** — character count, line count, estimated tube length (a playful estimate, not a manufacturing spec)
- **EN / 繁中** interface, **white / silver / black** themes (saved in localStorage), sign auto-saved in localStorage
- **Zero dependencies, zero network calls** for the sign itself (fonts load from Google Fonts with system fallbacks)

## OpenX Pro

Rainbow cycle animation and 2048px HD export are OpenX Pro features, unlocked with a shared OpenX Pro key on this device. Everything else is free forever.

## Use it

1. Open `index.html` in any modern browser — or try the live demo once GitHub Pages is enabled.
2. Type your sign text (up to 3 lines).
3. Pick a font, colour, wall and animation.
4. Click **PNG** to download your sign.

## Run locally

```bash
# any static server works; e.g.
python3 -m http.server 8000
# then open http://localhost:8000/
```

## Tech notes

- Single self-contained `index.html` (HTML + CSS + vanilla JS, Canvas 2D).
- The flicker animation uses a deterministic per-slot hash, so the flicker pattern is stable rather than shimmering every frame.
- Backgrounds are procedural: brick courses, stars and concrete grain are computed from seeded hashes, so exports are reproducible.
- This is a decorative sign maker. It does not manufacture real neon signs and makes no claim about real-world sign performance.

## License

MIT — see `LICENSE`.

## Support

These open-source Mo projects are built in the open and free to use.
If one of them saved you time or made you smile, you can support the next build:

**[Buy Me a Coffee — @whynotartmoney](https://buymeacoffee.com/whynotartmoney)**

Support is optional and never gates any feature — every project stays MIT-licensed and fully offline.
