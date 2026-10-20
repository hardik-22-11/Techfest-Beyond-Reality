# TECHFEST — BEYOND REALITY

A scroll-driven 3D website for Techfest. You don't browse it, you fly through it: a mechanical planet, floating structures, four interactive domain machines, a working reactor, and a core that splits open at the end.

🔗 **Live demo:** https://hardik-22-11.github.io/Techfest-Beyond-Reality/

---

## Run it

It's a single self-contained file. No npm, no install, no server.

1. Download `index.html`
2. Double-click it (Chrome or Edge recommended)

That's it. React, Three.js and GSAP are bundled inside the file, so it works without a CDN. Only the Google Fonts need internet; offline it falls back to system fonts.

## What's in it

- **Scroll-driven camera.** A GSAP ScrollTrigger timeline flies the camera along a path through the whole scene. Scroll is the controller.
- **Digital universe.** Floating structures rotate, scale and shift as you pass them.
- **Four domains.** ROBOWARS (battle robot), AI & ROBOTICS (robotic head), INNOVATION (energy reactor), AEROSPACE (satellite). Hover to glow and spin, click to select, hit EXPLORE for details.
- **Innovation Lab.** A live reactor with working controls: power on/off, energy colour (cyan, violet, orange), and spin speed.
- **Final core.** The sphere opens and powers up as you reach the end.
- **Polish.** Loading screen with progress, trailing cursor, mouse parallax, bloom, mobile nav, WebGL fallback, and reduced-motion support.

All 3D objects are procedural. There are no model files and no external assets.

## Stack

React + Vite, React Three Fiber, drei, GSAP ScrollTrigger, Framer Motion, Lucide icons. Bundled to one file with `vite-plugin-singlefile`.

## Content note

Festival details (dates, venues, guests, prizes) are clearly marked placeholders. The only real link is the official site: https://techfest.org

This is an unofficial concept build.

## Deploy

1. Create a public GitHub repo
2. Upload the file as `index.html`
3. Settings → Pages → Deploy from branch → `main` / root → Save

Your live link appears after about a minute.

---

Built for Techfest CA — Task 2: Build in 3D.
