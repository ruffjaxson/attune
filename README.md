# Attune

Calm binaural and isochronic tones for focus and rest.

A single-page web app — open `index.html` locally or visit [focus.jaxsonruff.com](https://focus.jaxsonruff.com).

## Features

- **Five tone presets** from easy focus (10 Hz) to deep concentration (40 Hz)
- **Three playback modes**
  - **Binaural** — different tones in each ear (headphones)
  - **Isochronic** — pulsed single tone (works on speakers)
  - **Ambient** — binaural tones over a soft noise bed
- Soft fades, a gentler carrier frequency, and a low-pass filter so the audio feels less raw
- An in-app **How it works** page with a plain-language science overview

Everything runs in the browser. No accounts, no uploads, no analytics.

## Local use

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy

Hosted on **Cloudflare Workers** (static assets) from this repo’s `main` branch.

- Build command: leave empty / `exit 0`
- Deploy command: `npx wrangler deploy`
- Custom domain: `attune.jaxsonruff.com`

```bash
npm install
npm run deploy
```
