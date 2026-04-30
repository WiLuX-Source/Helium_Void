# Wilux Void

A minimal, AMOLED-friendly dark theme for [Helium Browser](https://helium.computer). Pure black frame with system-dark neutral grays — no eye-searing purple, no compromises.

## Preview

| Element | Color |
|---|---|
| Frame | `#000000` — pure black |
| Toolbar / Active Tab | `#070707` — near black |
| Inactive Tabs / Omnibox / NTP | `#1c1c1e` — system dark gray |
| Text | `#ffffff` — white |
| Links | `#0a84ff` — system blue |

## Installation

1. Download or clone this repo
2. Open `chrome://extensions` in Helium
3. Enable **Developer mode** (top-right toggle)
4. Click **Load unpacked** → select the `helium_theme` folder
5. Done

> Heads up: Helium doesn't always apply theme changes on extension refresh. If colors aren't updating, remove the theme and re-add it via Load unpacked. If it still won't load, fully quit and relaunch Helium first.

## Notes

- Incognito windows are not affected — this is a Helium limitation, not a theme issue. Even the Void Theme from the Chrome Web Store has the same behavior.
- Built on Manifest V2 — Chrome's theme API does not support the `theme` key in MV3.

## License

Do whatever you want with it.
