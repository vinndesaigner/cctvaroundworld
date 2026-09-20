# 🛰️ C2 Tactical Surveillance Dashboard

A web-based Command & Control (C2) styled OSINT dashboard for real-time global monitoring. Built with a high-tech tactical HUD interface, integrated scanline shaders, and dynamic feed positioning.

![License](https://img.shields.io/badge/license-MIT-green.svg)
![Deployment](https://img.shields.io/badge/deployment-Vercel-black?logo=vercel)
![Security](https://img.shields.io/badge/edge-Cloudflare-orange?logo=cloudflare)

## 🌐 Live Demo

Explore the live surveillance grid: **[cctvrealtime.vincentl.my.id](https://cctvrealtime.vincentl.my.id)**

---

## ⚡ Key Features

- **Tactical Cyber/OSINT UI**: Engineered with custom HUD overlays, blinking telemetry indicators, and CRT scanline visual FX.
- **YT-RELAY Architecture**: Utilizes high-availability public YouTube live streams repurposed as scalable CDN edge nodes.
- **Non-Interactive Display Matrix**: Custom iframe wrapper with `pointer-events: none` to prevent UI interference and maintain an immersive tactical display.
- **Responsive Telemetry Grid**: Auto-adjusting multi-feed grid layout optimized for monitoring centers.

---

## 📜 Source Attribution & Courtesy Notice

This project operates strictly as a **non-commercial OSINT simulation and frontend interface**. 

- **Video Stream Credits**: All embedded video feeds are publicly available YouTube live streams.
- **Source Courtesy**: Video feeds belong to their respective original channels and content owners.
- **Embedded Relay**: Feeds are rendered using standard YouTube embedded players labeled under `SRC // YT-EDGE`. No video content is re-hosted, recorded, or modified on server side.

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, Modern CSS3 (CSS Grid, Flexbox, Keyframe Animations), Vanilla JavaScript (ES6+)
- **Map & Geolocation**: Leaflet.js
- **Infrastructure**: Vercel (Hosting), Cloudflare (DNS / Proxy Edge)

---

## 🚀 Local Development

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/vinndesaigner/cctvaroundworld.git](https://github.com/vinndesaigner/cctvaroundworld.git)
   cd cctvaroundworld