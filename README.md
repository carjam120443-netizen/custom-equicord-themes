# ⌨️ Custom Equicord Themes

A small collection of custom CSS themes for **Equicord / Discord** — starting with a terminal-inspired look. Turn your chat client into a dark command center with green phosphor text, subtle scanlines, terminal-style panels, and monospace typography. 🟢

## Themes

### Terminal Green
**File:** [`terminal-green.css`](./terminal-green.css)

A retro terminal aesthetic inspired by Linux shells and classic CRT displays.

- 🟢 Deep black and forest-green surfaces
- ⌨️ Monospace typography for a terminal feel
- 🖥️ Green accents, borders, and subtle glow
- 📟 Optional-looking scanline texture (kept subtle)
- 💬 Chat remains readable, with message content and controls still recognizable

## Install

1. Make sure you have [Equicord](https://equicord.org/) installed and working.
2. Open your Equicord theme/CSS settings.
3. Enable custom CSS or import a theme file, depending on your setup.
4. Copy the contents of `terminal-green.css` into the custom CSS editor, or place the file in the themes folder if your Equicord setup supports local theme files.
5. Enable the theme and reload Discord if needed.

> **Note:** Equicord settings and theme-loading methods can change between versions. Use the method supported by your current installation.

## Customize

Open `terminal-green.css` in any text editor. Near the top, change the CSS variables to adjust the palette:

- `--term-bg`: main background
- `--term-panel`: panel background
- `--term-green`: primary terminal green
- `--term-dim`: muted green
- `--term-border`: panel outlines

You can also remove the scanline `body::after` rule if you prefer a completely clean background.

## Compatibility

- Designed for Equicord's custom CSS/theme workflow.
- Discord class names can change after updates, so some styling may need adjustments.
- This is a visual stylesheet only; it does not add commands, bots, or terminal functionality.

## Disclaimer

Community-made styling project; not affiliated with Discord or Equicord. Use custom client modifications in line with the rules and policies that apply to your installation.

---

Made for terminal enjoyers. `$ discord --terminal-mode` 🐧
