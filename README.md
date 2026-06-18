# 🏎️ Neon Drive 3D (web)

A real-time **3D** arcade night racer in a single HTML file, built with **[Three.js](https://threejs.org)** (WebGL). Chase camera, dynamic headlights + real-time shadows, a neon city, traffic to dodge, and nitro boost.

🔴 **Live demo:** https://apps.mahdi-nmoghadasi.com/racer

## Features
- Real-time 3D scene: lit highway, low-poly cars, neon buildings, moon + headlights, shadows
- Traffic with collisions, **nitro** (FOV + exposure boost), engine sound that scales with speed
- ACES tone-mapping + fog + vignette for a cinematic look
- **Desktop keyboard + mobile touch controls**, auto-resizes to the screen

## Controls
▲ / W gas · ▼ / S brake · ◄ ► steer · **Shift** nitro

## Run
Open `index.html`. Three.js loads from a CDN, so the first load needs internet.

## Tech
Three.js (r128) · WebGL · WebAudio. No build step.
