# **KELP — the pronunciation of kWP**

### A minimal, fluid and experimental macOS browser built from scratch.

<p align="center">
  <img src="assets/kelp-wave.svg" height="360">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-early%20alpha-4fa3ff?style=for-the-badge&logo=macos">
  <img src="https://img.shields.io/badge/platform-macOS-7fbaff?style=for-the-badge&logo=apple">
  <img src="https://img.shields.io/badge/electron-39.0-45d4ff?style=for-the-badge&logo=electron">
  <img src="https://img.shields.io/badge/build-alpha-63e0c9?style=for-the-badge">
</p>

---

## Current Look

<p align="center">
  <img src="https://i.imgur.com/BV4KF6B.png" width="720" alt="Kelp Home">
  <br><br>
  <img src="https://i.imgur.com/3ll09Od.png" width="720" alt="Kelp Settings">
</p>

---

# About

KELP began as a tiny experiment (back when it was just **katWebProfissional**) and slowly evolved into a minimal browser handcrafted for macOS.

It’s built around a simple idea:
a browser that feels clean, light, and fluid — like interface elements carved out of water and glass.

Still early-stage, still a bit fragile, but already stable enough for daily testing and exploration.

KELP is intentionally **small**, **transparent**, and avoids bloat.

---

# Features (current)

### Core

* Multi-tab system
* Title + URL sync
* Custom “kwp://home.kwp” protocol → Kelp Home
* Clock + Weather widgets on the Home screen
* Smooth tab highlight animations
* Basic download popup *(implemented but not hooked fully)*

### Navigation

*(mouse interaction works reliably — keyboard shortcuts are improving)*

* `⌘T` new tab
* `⌘W` close tab
* `⌘R` reload
* `⌘L` focus URL bar
* `⌘⇧T` reopen last closed tab

### Visual

* Ocean-themed colors
* Dark, compact macOS layout
* Blur-less tabs for stability
* Minimal chrome-free topbar

---

# Security (default OFF)

KELP ships with a configurable “Tor-lite style” security mode.
All features are **toggle-able** in Settings — off by default to avoid breaking sites.

### Features available (but OFF by default):

* HTTPS-Only Mode
* Vault Tabs *(close & reset tabs when KELP loses focus)*
* Popup Blocking
* WebRTC Disable *(IP leak prevention)*
* Tracker Blocking *(common ad/analytics domains)*
* Anti-Fingerprint tweaks
* Block 3rd-party cookies
* Disable Service Workers
* Disable autoplay audio/video

Security policies are strict, but the goal is to keep the browser usable.

---

# Upcoming

* Favicon detection
* Improved tab animations
* History page *(implemented, not wired)*
* Downloads page / manager *(implemented, not wired)*
* URL suggestions & autocomplete *(implemented, not wired)*
* macOS trackpad gestures
* Quick Actions Launcher

---

# Versioning

Current release:
**v25.11.25-0.0.5macrelease**

Previous:

* v25.11.25-0.0.4
* v25.11.25-0.0.3
* v24.11.25-0.0.2

---

# Tech Stack

* Electron 39
* Chromium
* Node.js
* Vanilla JS + CSS
* Custom preload messaging sandbox

---

# Open-Source Status

KELP is not public/open-source yet.
This README only documents progress and tracks features during the early builds.
