# Morse Code Maker

A free, client-side Morse code translator and trainer that runs entirely in your browser. Type text and instantly see the Morse code output — or decode Morse back into plain text — with playback, a dark mode, and zero server calls.

## Features

- **Two-way conversion** — text to Morse code and Morse code back to text
- **Audio playback** — hear the dots and dashes with Web Audio API tones
- **Dark / light mode** — theme toggle with a modern, responsive UI
- **Copy to clipboard** — one-click copy of the translated output
- **100% client-side** — no backend, no tracking, works offline after first load

## Tech Stack

- Vanilla HTML5, CSS3, JavaScript
- Font Awesome icons (CDN)
- Web Audio API for sound playback

## Quick Start

Open `morse-code-maker.html` directly in any modern browser — no build step, no server required. Everything runs locally on your machine.

## Project Structure

```
├── morse-code-maker.html   # Full app: UI, styles, and translation logic in one file
├── LICENSE
└── README.md
```

## Deploy Notes

Single-file static app — deploy by serving `morse-code-maker.html` (or renaming it to `index.html`) on any static host: GitHub Pages, Cloudflare Pages, Netlify, or Vercel. No build step and no environment variables needed.

---

Built by [Girish Lade](https://ladestack.in) — free developer tools at [ladestack.in](https://ladestack.in)
