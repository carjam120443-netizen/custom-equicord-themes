# ⌨️ Custom Equicord Themes

A small collection of custom CSS themes for **Equicord / Discord**. Pick your vibe: retro terminal green or glossy Windows Aero glass. 🟢🪟

## Themes

### 🟢 Terminal Green
**File:** [`terminal-green.css`](./terminal-green.css)

A retro terminal aesthetic inspired by Linux shells and classic CRT displays.

- Deep black and forest-green surfaces
- Monospace typography, green accents, and subtle glow
- Subtle scanline texture
- Readable chat, code blocks, and controls

### 🪟 Aero Glass
**File:** [`aero-glass.css`](./aero-glass.css)

A Windows Vista / Windows 7-inspired look with cool blue gradients and glossy, glass-like panels.

- Frosty blue and silver surfaces
- Glossy title bars and beveled-looking buttons
- Soft borders, highlights, and window-like shadows
- Rounded menus, search fields, and message composer
- Blue-tinted code blocks and smooth hover states

## Install

1. Make sure you have [Equicord](https://equicord.org/) installed and working.
2. Open your Equicord theme/custom CSS settings.
3. Choose the theme you want.
4. Copy that CSS file's contents into your custom CSS editor, or place the file in your themes folder if your setup supports local theme files.
5. Enable the theme and reload Discord if needed.

> **Note:** Equicord settings and theme-loading methods can change between versions. Use the method supported by your current installation.

## Customize

Both themes define CSS variables near the top of their files, so you can tweak colors without hunting through every rule.

- **Terminal Green:** adjust `--term-bg`, `--term-panel`, `--term-green`, `--term-dim`, and `--term-border`.
- **Aero Glass:** adjust `--aero-bg`, `--aero-panel`, `--aero-blue`, `--aero-border`, and `--aero-text`.

## Compatibility

- Designed for Equicord's custom CSS/theme workflow.
- Discord class names can change after updates, so some styling may need adjustments.
- These are visual stylesheets only; they do not add commands, bots, or terminal functionality.
- Aero uses CSS gradients and translucent-looking surfaces to evoke glass; the exact effect depends on Discord's current layout and CSS support.

## Disclaimer

Community-made styling project; not affiliated with Discord or Equicord. Use custom client modifications in line with the rules and policies that apply to your installation.

---

Made for people who like their chat a little more retro — or a little more Aero. `$ discord --style=nostalgia` 🐧
