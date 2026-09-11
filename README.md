# Helium Void

A minimal, AMOLED-friendly dark theme for [Helium Browser](https://helium.computer). Pure black frame with system-dark neutral grays — no eye-searing purple, no compromises.

## Preview

![Helium Void: pure black window frame with system-dark gray tabs and omnibox](https://github.com/user-attachments/assets/76fe9136-7362-48c8-8514-75f6a5eea9b5)

| Element | Color |
|---|---|
| Frame | `#000000` — pure black |
| Toolbar / Active Tab | `#070707` — near black |
| Inactive Tabs / Omnibox / NTP | `#1c1c1e` — system dark gray |
| Text | `#ffffff` — white |
| Links | `#0a84ff` — system blue |

## Installation

1. Download the latest `Helium-Void-x.y.zip` from [Releases](../../releases)
2. Open `chrome://extensions` in Helium
3. Drag the zip onto the page
4. Done

Helium unpacks it into your profile, so the zip is safe to delete afterwards.

<details>
<summary><b>Or load it unpacked</b> — if you want to edit the colors</summary>

1. Clone this repo, or unzip a release
2. Open `chrome://extensions` and enable **Developer mode** (top-right toggle)
3. Click **Load unpacked** → select the folder containing `manifest.json`

> [!IMPORTANT]
> Unlike the drag-and-drop route, this one never copies the files — Helium re-reads that folder on every launch. **Move or delete it and the theme goes with it.** Keep it somewhere permanent, not Downloads or a temp folder you'll clear out later.

> Heads up: Helium doesn't always apply theme changes on extension refresh. If colors aren't updating, remove the theme and re-add it via Load unpacked. If it still won't load, fully quit and relaunch Helium first.

</details>

## Notes

- Incognito windows are not affected — this is a Helium limitation, not a theme issue. Even the Void Theme from the Chrome Web Store has the same behavior.
- Built on Manifest V3.

## License

Do whatever you want with it.
