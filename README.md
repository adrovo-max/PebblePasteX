# PebblePasteX

**Work across PCs.** One mouse and keyboard for two Windows computers, with text, file, and folder sharing over your local network.

[Download 1.0.7](https://github.com/adrovo-max/PebblePasteX/releases/latest) · [Official website and setup guide](https://handypebble.com/pebblepastex/) · [More HandyPebble software](https://handypebble.com/pebblepaste/)

## What it does

- Move your pointer through the selected screen edge to use the other PC with the same keyboard and mouse.
- Copy text, files, and folders between approved PCs. File paste and progress are handled by Windows Explorer.
- Pair with a matching six-digit code that must be approved on both computers.
- Keep your last keyboard/mouse and clipboard sharing switches across app restarts, including switches you turned off.
- Choose an optional glow, burst, jelly effect, or gravity wave at the screen edge.
- Pause connections from the app or tray. Press **Ctrl + Alt + Shift + Esc** on the local keyboard to return control.
- Follow your Windows display language automatically, or choose from 12 languages in Settings.

## Set up two PCs

1. Install the same version on two Windows 10 or Windows 11 **x64** PCs on the same private Wi-Fi or Ethernet network.
2. If Windows asks for network access, allow Private networks only. Do not disable Windows security.
3. Open PebblePasteX on both PCs, compare the pairing code, and approve on both screens.
4. Select where the other screen sits. Enable keyboard/mouse sharing and clipboard sharing on both PCs as needed.

First-time setup keeps sharing off until you enable it. After upgrading from an older version, turn on your desired switches once; version 1.0.7 remembers them automatically from then on. Pause and tray Exit do not erase your choices. **Settings → Reset sharing switches** turns both switches off now and on future starts, without deleting pairing, language, screen position, or effect preferences.

To update, choose **Exit PebblePasteX** from the tray on each PC, then run the new installer. Existing pairing and preferences are kept. The installer includes WebView2 for PCs that need it; you do not need a separate runtime download.

## Privacy and practical limits

No account or cloud workspace is required. Pairing, input, and file sharing use encrypted connections between approved PCs on the local network. The website opens only when you click its link.

This version is for Windows x64. macOS and Linux are not supported. Secure desktop prompts, Windows sign-in screens, and elevated applications may not accept remote input. Clipboard history and images copied directly from an editor are not supported. Keep both PCs connected during file paste.

Automated checks cover pairing, input routing, file streams, cancellation, and settings recovery. Longer physical two-PC sessions, Windows 11 behavior, and Explorer file/folder paste still need further hands-on verification. Start with disposable files and save your work before trying remote input.

## Free, noncommercial use

PebblePasteX is free for noncommercial use. You may share the official download link or the unmodified installer for noncommercial use. Do not sell it or bundle it into a paid product without prior written permission.

**Proprietary software. All rights reserved. Source code is not publicly available.** This repository contains product information and downloadable releases only. See [LICENSE-NOTICE.md](LICENSE-NOTICE.md).

Made by HandyPebble. [Visit HandyPebble](https://handypebble.com/pebblepastex/).
