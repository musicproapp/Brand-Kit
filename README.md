# MusicPro Minimal Branding Kit v1.0

This is the canonical starter kit for building future MusicPro websites, web apps/PWAs, desktop-style music tools, PDFs, documentation, and product materials.

## Brand

Master brand: MusicPro
Primary domain: MusicPro.app

The approved master symbol is the simplified seven-bar waveform M. It uses straight vertical rounded bars only. Do not replace it with the older quarter-note, tape, note-ring, indigo mark, or other experimental logos.

## Source of truth

Use these files as the canonical references:

- logo/musicpro-mark.svg — full-color transparent master mark
- logo/musicpro-mark-black.svg — black monochrome mark
- logo/musicpro-mark-white.svg — white monochrome mark
- logo/musicpro-app-dark.svg — dark app icon
- logo/musicpro-app-light.svg — light app icon
- tokens/colors.css — canonical color tokens
- tokens/typography.css — canonical typography tokens
- tokens/spacing.css — spacing, radius, shadow, and motion tokens
- tokens/base.css — base CSS normalization
- styles.css — web entrypoint
- BRAND-SYSTEM.md — concise design rules and implementation guidance

## Typography

Inter is the primary UI and body family.
Newsreader is the display/editorial family where a serif treatment is appropriate.
JetBrains Mono is the technical/code family.

For PDFs, use locally installed or embedded font files when possible. Do not depend on a web-font import inside a PDF renderer.

## Color

The logo palette is the source of truth for brand color. The principal brand action color is blue. Cyan, teal, green/lime, yellow, and orange are supporting brand colors. Do not introduce the former indigo/purple palette as a new MusicPro brand color.

## Themes

Support both light and dark themes. Dark interfaces should use a deep neutral background rather than a purple/indigo background.

## Product branding

Products such as MIDI Enhancer are products of MusicPro. Keep the master MusicPro mark recognizable and consistent. Product-specific accents may be introduced later, but they must not redefine the master brand palette.

## Logo rules

Use the SVG files whenever possible. Do not recreate the mark manually from screenshots. Do not stretch, skew, recolor individual bars, add curves, add music notes, or add decorative elements to the master mark.

For small sizes, prefer the canonical symbol-only SVG. If a future product requires a simplified small-size mark, create it as a documented derivative rather than modifying the master asset.

## For coding agents

Before creating a new MusicPro page or application:

1. Read BRAND-SYSTEM.md.
2. Load tokens/colors.css, typography.css, spacing.css, and base.css or styles.css.
3. Use the canonical SVG from logo/.
4. Preserve the light/dark theme model.
5. Do not introduce legacy Music Pro Hacks branding, old indigo/cream colors, quarter-note marks, tape marks, note-ring marks, or other archived logos.
6. Do not invent a new visual language when an existing token or component can be reused.
7. If a new component is needed, make it consistent with the existing spacing, radius, typography, border, and interaction tokens.
8. Treat MusicPro as the master brand and the application name as the product name.

## Scope

This kit intentionally stays minimal. It contains reusable brand assets and implementation guidance, not a complete application UI library or a complete PDF template.
# Brand-Kit
