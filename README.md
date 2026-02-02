# LVSHN KABINA FM — Radio for After Effects

LVSHN KABINA FM is a CEP extension for Adobe After Effects that adds an in-panel radio player with curated stations and optional content packs.

## Features
- In-panel radio player for After Effects (CEP / Extensions)
- Curated stations + expandable packs
- Offline signed codes: **PRO** / **PASS** / **Packs**
- Lightweight UI and quick access while working

## Requirements
- Adobe After Effects
- CEP Extensions enabled (Window → Extensions)
- Windows or macOS
- Installation via **ZXP Installer**

## Installation (ZXP Installer)
1. Close After Effects.
2. Open **ZXP Installer**.
3. Install `LVSHN_KabinaFM_<version>.zxp` (or drag & drop into the installer).
4. Launch After Effects.
5. Open: **Window → Extensions → LVSHN Kabina FM**

## If the panel doesn’t appear (CEP Developer Mode)
Sometimes self-signed ZXP requires CEP Developer Mode.

### Windows
1. Close After Effects.
2. Press `Win + R` → type `regedit` → Enter.
3. Set `PlayerDebugMode` to `1` in one (or more) of these keys:
   - `HKEY_CURRENT_USER\Software\Adobe\CSXS.5`
   - `HKEY_CURRENT_USER\Software\Adobe\CSXS.6`
   - `HKEY_CURRENT_USER\Software\Adobe\CSXS.7`
   - `HKEY_CURRENT_USER\Software\Adobe\CSXS.8`
   - `HKEY_CURRENT_USER\Software\Adobe\CSXS.9`
4. Restart After Effects.

### macOS
1. Close After Effects.
2. Open Terminal and run:
   - `defaults write com.adobe.CSXS.5 PlayerDebugMode 1`
   - `defaults write com.adobe.CSXS.6 PlayerDebugMode 1`
   - `defaults write com.adobe.CSXS.7 PlayerDebugMode 1`
   - `defaults write com.adobe.CSXS.8 PlayerDebugMode 1`
   - `defaults write com.adobe.CSXS.9 PlayerDebugMode 1`
3. Restart After Effects.

## Activation (Codes)
Open the panel → **Codes** → paste your code.

Supported signed code types:
- **PRO** (full version features)
- **PASS** (time-limited access, e.g. 30 days depending on configuration)
- **PACK** (unlocks a specific content pack)

> Codes are cryptographically signed. If a code is valid but content doesn’t appear, ensure you’re on the latest version and check that online pack links are reachable.

## Updates
- Install a new `.zxp` over the existing version via ZXP Installer.
- Restart After Effects after updating.

## Troubleshooting
- **Installed but not visible:** enable CEP Developer Mode (see above) and restart AE.
- **Stations/packs not loading:** check your internet connection and availability of pack URLs.
- **UI looks old after update:** clear CEP cache and restart AE.

## Privacy
The extension does not collect personal data by default. (Adjust this section if you add analytics.)

## Support
- Email: <ilyalvshn@gmail.com>
- Gumroad: <https://lvshn.gumroad.com/>
- Boosty: <https://boosty.to/levshin_ilya>
- Telegram: <https://t.me/levshin_ilya>
