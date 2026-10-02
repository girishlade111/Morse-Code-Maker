# Morse Code Maker

A single-file web app that converts text to Morse code (and back) right in the
browser — with audio playback, visual signal flashing, and copy support.
100% client-side: no build step, no dependencies, no server.

## Features

- **Text → Morse** — type anything and get the dot-dash encoding instantly
- **Morse → Text** — decode Morse input back to readable text
- **Audio playback** — hear the Morse signal via the Web Audio API
- **Visual signaling** — flashing indicator for dot/dash timing
- **Zero setup** — one HTML file; open it or host it anywhere

## Tech stack

- HTML5, CSS, JavaScript (vanilla — no frameworks)
- Web Audio API for sound generation

## Quick start

Open `index.html` in any browser, or serve the folder with any static server:

```bash
npx serve .
```

## Deploy notes

Plain static — served from `index.html` at the repo root. Works on GitHub Pages,
Cloudflare Pages, Netlify, or any static host. No environment variables required.

---

Built by [Girish Lade](https://ladestack.in) · https://ladestack.in
