# MusicPro Brand System & Visual Guidelines

**Version:** 1.2  
**Date:** 2026-09-13  
**Master Brand:** MusicPro  
**Primary Domain:** musicpro.app  
**Official YouTube Channel:** @musicproapp (URL: `https://youtube.com/@musicproapp`)

---

## 1. Master Brand Identity

- **Brand Name:** **MusicPro** (Written as single PascalCase word: `MusicPro`, never `Music Pro Hacks` or `Guitar Producer`).
- **Primary Domain:** **`musicpro.app`** (All web assets, documentation links, and guides point to `https://musicpro.app`).
- **Official YouTube Channel:** **`@musicproapp`** (`https://youtube.com/@musicproapp`, uppercase in footers: `@MUSICPROAPP`).
  > [!IMPORTANT]
  > Always use **`@musicproapp`**. Do NOT use `@musicpro` (which belongs to a different channel).

---

## 2. Master Symbol: The 3-Line Equalizer Mark

The canonical logo mark is a minimalist **3-line vertical equalizer waveform** consisting of three vertically centered rounded pill bars:
- **Left Bar:** MusicPro Blue (`#0091FF` / `#007BFF`) — Medium height
- **Center Bar:** MusicPro Green (`#2ED573`) — Tallest bar
- **Right Bar:** MusicPro Orange (`#F59E0B`) — Short bar

### Strict Geometric Proportions
- **Height Ratio:** `15 : 22 : 12` (e.g., in a 512×512 canvas: bar 1 is 240px, bar 2 is 352px, bar 3 is 192px).
- **Bar Width:** Constant 96px width per bar.
- **Corner Radius:** `rx="48"` (full pill rounded ends).
- **Horizontal Positioning:** Center-aligned across the X axis (`x="72"`, `x="208"`, `x="344"`).
- **Vertical Centering:** All three bars share the exact same horizontal center line (`Y = 256`).

---

## 3. Approved Asset Suite (`Brand-Kit/logo/`)

- **Full-Color Vector Mark:** `logo/musicpro-mark.svg` (transparent background)
- **Monochrome Vector Marks:**
  - `logo/musicpro-mark-black.svg` (solid black for high-contrast B&W print)
  - `logo/musicpro-mark-white.svg` (solid white for dark backgrounds)
- **App Icons:**
  - `logo/musicpro-app-dark.svg` (deep dark `#08111C` squircle container)
  - `logo/musicpro-app-light.svg` (crisp white `#FFFFFF` squircle container)
- **Production Favicon Suite (100% Alpha Transparent — No White Box):**
  - `logo/favicon.svg` (vector browser favicon, pure transparent background)
  - `logo/favicon.ico` (multi-resolution 16/32/48 ICO with alpha transparency)
  - `logo/favicon.png` / `logo/favicons.png` (transparent preview & presentation sheet)
  - `logo/apple-touch-icon.svg` / `logo/favicon-180x180.png` (iOS home screen)
  - Raster sizes (all 32-bit RGBA, corner alpha = 0): `16x16`, `32x32`, `48x48`, `180x180`, `192x192`, `512x512`
- **Favicon Transparency Options (`logo/options/`):**
  - **Option 1 (Canonical Floating Mark — Recommended):** Pure 3-line equalizer waveform directly on transparent canvas.
  - **Option 2 (High-Contrast Luminous):** Enhanced cyan-blue and amber saturation for dark browser windows.
  - **Option 3 (Universal Contrast Rim):** Floating mark with subtle ambient contrast rim for pure `#000000` tabs.
  - **Option 4 (Dark Squircle Badge):** Dark glass rounded squircle container with 100% transparent background outside corners.
- **7-Bar Alternate:** `logo/alternate-7bar/` (archived 7-bar waveform M suite preserved for future alternative use)

---

## 4. Brand Colors

Primary Palette for the 3-Bar Mark:
- **Bar 1 (Left):** MusicPro Blue (`#0091FF` / `#007BFF`)
- **Bar 2 (Center):** MusicPro Green (`#2ED573`)
- **Bar 3 (Right):** MusicPro Orange (`#F59E0B`)

Extended Brand Spectrum:
- Primary Blue: `#007BFF` / `#0091FF`
- Bright Cyan: `#00C7FF`
- Teal: `#00E5D4`
- Green: `#2ED573`
- Lime: `#A3E635`
- Yellow: `#FACC15`
- Orange: `#F59E0B`

Neutrals:
- Dark text / ink: `#101828`
- Soft text / muted: `#344054` / `#475467`
- Borders: `#E4E7EC` / `#D0D5DD`
- Canvas / background: `#F7F9FC` (light), `#08111C` (dark)

---

## 5. Typography

- **Primary UI & Body:** `Inter` (weights 400, 500, 600, 700, 800)
- **Display / Editorial:** `Newsreader` (serif accent for editorial titles)
- **Technical / Code / Values:** `JetBrains Mono` (weights 500, 600, 700 for product keys, timestamps, MIDI values)

---

## 6. Favicon & Digital Implementation Rules

1. **True Transparency:** Favicons must never be rendered on an opaque white square canvas. Browser chrome (especially in macOS / Windows dark mode) requires true 32-bit RGBA transparency so tabs remain clean.
2. **Multi-Scale Scaling:** Browser favicons must include 16×16, 32×32, and 48×48 layers inside `favicon.ico` alongside modern `favicon.svg`.
3. **PWA & Apple Touch Icons:** Use `favicon-180x180.png` or `apple-touch-icon.svg` for home screen bookmarks.
