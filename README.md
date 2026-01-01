# Codeforces Snow Remover

**Codeforces Snow Remover** is a lightweight browser extension that removes Codeforces’ seasonal background effects (such as snow) to keep the interface clean, distraction-free, and competition-ready.

This was made mainly for [dark reader](https://darkreader.org) users, since the snow effect after using that extension becomes way more annoying, but it works with any codeforces theme extension, or even with none at all.

## Features

- Removes Codeforces seasonal background effects (snow, animations, overlays)
- Cleans background styling for a minimal, readable UI
- Runs **only on Codeforces** (`*.codeforces.com/*`)
- Zero configuration, zero permissions beyond what’s needed
- No external dependencies, minimal footprint

## How it works

The extension injects a small content script on Codeforces pages that overrides background styles applied by Codeforces

The script runs after page load and is scoped exclusively to Codeforces domains, ensuring no side effects elsewhere.

## Installation / Usage

1. Download the `.zip` of this repository from the latest [release](https://github.com/christhabot/Codeforces-Snow-Remover/releases)
2. Extract the folder and place it somewhere permanent (If the folder is deleted, the extension will stop working)
3. Open your browser’s **Extensions** page (for example: `chrome://extensions`, or your browsers equivalent)
4. Enable **Developer mode**
5. Click **Load unpacked**
6. Browse and select the extension's folder
7. Refresh or open any Codeforces page

The seasonal background effects should now be removed.

## Screenshots
### With dark reader
<img width="818" height="626" alt="image" src="https://github.com/user-attachments/assets/8011570e-5127-4380-ae56-cb5a9e866433" />

### Without any dark theme extension
<img width="808" height="628" alt="image" src="https://github.com/user-attachments/assets/4f389ff6-6b52-4373-b9d2-cf85549c45c8" />

## Supported Browsers

- Chrome  
- Edge  
- Opera  
- Brave  
- Vivaldi  
- Any other Chromium-based browser

## Issues or suggestions?

Open an [issue](https://github.com/christhabot/Codeforces-Snow-Remover/issues) explaining your problem or suggestion in detail!

## Want to contribute?

Submit a [pull request](https://github.com/christhabot/Codeforces-Snow-Remover/pulls) and help make this tool even better!
