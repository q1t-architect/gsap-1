# GSAP Scroll-Driven Video Prototype

Scroll-driven video playback using GSAP ScrollTrigger + `video.currentTime`.

## Quick Start

```bash
# Clone
git clone https://github.com/q1t-architect/gsap-1.git
cd gsap-1

# Serve locally (any static server)
npx serve .
# or
python3 -m http.server 8000
```

Open `http://localhost:3000` (or `:8000`) and scroll.

## How It Works

- `<video>` tag with `muted`, `playsinline`, no autoplay
- GSAP ScrollTrigger binds scroll position → `video.currentTime`
- Hero section is `400vh` tall, video container is `position: sticky`
- Scroll from top to bottom = video plays from 0s to end

## Tech Stack

- GSAP 3.12.7 (CDN, MIT license)
- ScrollTrigger plugin (CDN, MIT license)
- Pure HTML/CSS/JS — no build tools

## Video Source

[Sleek Car Headlight Close-up at Night](https://www.pexels.com/video/sleek-car-headlight-close-up-at-night-29498807/) by Michael Pronin — Pexels free license.
