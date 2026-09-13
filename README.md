# MusicPro Minimal Branding Kit v1.2

This is the canonical starter kit for building future MusicPro websites, web apps/PWAs, desktop-style music tools, PDFs, documentation, and product materials.

## Brand

- **Master brand:** MusicPro
- **Primary domain:** MusicPro.app
- **Official YouTube:** @musicproapp (URL: `https://youtube.com/@musicproapp`)

The approved master symbol is the **three-line equalizer/waveform mark** consisting of three vertically centered rounded bars with a strict 15 : 22 : 12 height ratio (Left: medium blue, Center: tall green, Right: short orange). It serves as both the canonical brand mark and the high-visibility favicon.

*(The earlier seven-bar waveform M is preserved under `logo/alternate-7bar/` as an approved alternate).*

## Source of truth

Use these files as canonical references:

- `logo/musicpro-mark.svg` — full-color master 3-line mark (`#0091FF`, `#2ED573`, `#F59E0B`)
- `logo/musicpro-mark-black.svg` — black monochrome 3-line mark
- `logo/musicpro-mark-white.svg` — white monochrome 3-line mark
- `logo/musicpro-app-dark.svg` — dark app icon
- `logo/musicpro-app-light.svg` — light app icon
- `logo/favicon.svg` & `logo/favicon.ico` — production browser favicon suite (100% alpha transparent)
- `logo/favicon.png` & `logo/favicons.png` — transparent favicon icon & multi-option comparison sheet
- `logo/favicon-*.png` — 32-bit RGBA transparent rasters (`16x16`, `32x32`, `48x48`, `180x180`, `192x192`, `512x512`)
- `logo/options/` — complete favicon suites for all 4 transparency options (Floating, Luminous, Rim, Squircle)
- `logo/apple-touch-icon.svg` — iOS home screen bookmark icon
- `logo/alternate-7bar/` — archived 7-bar waveform M alternate suite
- `tokens/colors.css` — canonical color tokens
- `tokens/typography.css` — canonical typography tokens
- `tokens/spacing.css` — spacing, radius, shadow, and motion tokens
- `tokens/base.css` — base CSS normalization
- `styles.css` — web entrypoint
- `BRAND-SYSTEM.md` — design rules and implementation guidance

## Typography

- **Inter** is the primary UI, navigation, and body family.
- **Newsreader** is the display/editorial serif family for editorial titles.
- **JetBrains Mono** is the technical/code family for product keys, MIDI values, and timestamps.

For PDFs, use locally installed or embedded font files (`fonts/` directory). Do not depend on external web-font imports inside a headless PDF renderer.

## Color

The master mark palette is the source of truth for brand color:
- **Left bar:** MusicPro Blue (`#0091FF` / `#007BFF`) — principal interactive/action color
- **Center bar:** MusicPro Green (`#2ED573`) — accent / active audio color
- **Right bar:** MusicPro Orange (`#F59E0B`) — warm highlight / badge color

## Logo & Favicon rules

1. Always use vector SVG files whenever possible.
2. Favicons and app marks must have **true 32-bit RGBA transparency** (no opaque white square background).
3. Maintain the fixed 15 : 22 : 12 height proportions and vertical center alignment.
4. Do not stretch, skew, rotate, or add decorative effects to the mark.
5. For micro-scales (browser tabs, app badges), use `logo/favicon.svg` or `logo/favicon.ico`.
6. For monochrome print, use `logo/musicpro-mark-black.svg`.

## For coding agents

Before creating a new MusicPro page or application:

1. Read `BRAND-SYSTEM.md`.
2. Load `tokens/colors.css`, `typography.css`, `spacing.css`, and `base.css` (or `styles.css`).
3. Use the canonical SVG from `logo/`.
4. Default to clean, high-contrast light mode with crisp typography.
5. Do not introduce legacy "Guitar Producer" or "Music Pro Hacks" branding.
6. Treat **MusicPro** as the master brand and the specific tool as the product name.
