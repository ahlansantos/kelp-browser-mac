# **KELP, the pronunciation of *kWP***

### *A minimal, fluid and experimental Mac browser — built from scratch.*

<p align="center">
  <img src="assets/kelp-wave.svg" height="120">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-early%20alpha-ff4f4f?style=for-the-badge&logo=macos">
  <img src="https://img.shields.io/badge/platform-macOS-1f75fe?style=for-the-badge&logo=apple">
  <img src="https://img.shields.io/badge/electron-39.0-4bd4ff?style=for-the-badge&logo=electron">
  <img src="https://img.shields.io/badge/build-stable-4caf50?style=for-the-badge">
</p>

---

## **Screenshots**

> *Current look — ocean-themed, smooth and minimal.*

<p align="center">
  <img src="https://i.imgur.com/WAQPU6F.png" width="700" alt="Kelp home">
  <br><br>
</p>

---

# **About kWP / KELP**

KELP started life as **katWebProfissional**, a tiny, weird web project.
Somehow it turned into a full mini-browser, now designed specifically for macOS,
with a clean UI, soft animations and that *“water glass”* vibe.

Still super early-stage, but already functional enough to browse normally.
Think of it as a little browser surfacing from the ocean and learning to walk.

---

# **Features (current)**

### Core

* 🗂️ Multi-tab system (stable in 0.0.4)
* ➕ ⌘T — new tab
* ❌ ⌘Shift+⌘T — reopen closed tab *(still experimental)*
* 🔄 ⌘R — reload
* ➡️ Back / Forward support
* 🔎 Zoom *(⌘+, ⌘−, ⌘0)*
* 🧭 Loading bar (Not working on 0.0.4+, will be fixed on 0.0.5)
* 🌊 Ocean-themed Home page
* -> Settings Window (0.0.4+)

### Customization

* -> Widgets (0.0.4+)

### Security (current)

* 🌐 **HTTPS-Only Mode**
  Automatically redirects all `http://` → `https://`.

* 🧊 **Vault Tabs**
  All tabs auto-close when you leave the app or change the focus (extra privacy).

* 🚫 **Popup Blocker**
  Blocks all unwanted popups and new windows.

### macOS Integration

* Full ⌘ shortcut support (Bit buggy, needs to hover or click on a tab or search bar)
* Ready for DMG distribution (alpha)
* Trackpad Navigation (Upcoming, maybe on 0.0.5+?)

---

# **Upcoming Features**

* 🔖 History page (UI)
* ⚙️ New Settings page
* ⭐ Tab favicons
* 🎨 Light/dark adaptive theme
* 🧩 Mini-modules / extensions (0.0.5+?)

---

# **Version History**

⚠️ *Supports Apple Silicon (M1+) and Intel Macs.*

* **v25.11.25-0.0.4macrelease** — *Current version*
  Cleaned security system, added popup-blocker, fixed HTTPS-only, vault tabs stable, entire codebase restructured.

* **v25.11.25-0.0.3macrelease** — UI improvements, animations and layout fixes

* **v24.11.25-0.0.2macrelease** — First semi-usable build

Early alpha — breaking changes expected.
Like… a lot.

---

# **Tech Stack**

* ⚡ Electron 39
* 🖥️ BrowserView rendering
* 🎨 HTML / CSS / JS
* 🧩 Minimal preload bridge
* 🐚 macOS window chrome

---

# **Open-Source Status**

KELP is **not open-source yet**.
The repo exists mainly for version tracking, screenshots and progress logs.


É só pedir, meu amor.
