# Nothingness

## About

Nothingness is a Google Chrome extension by [Refueled](https://refueled.net/nothingness). It replaces your New Tab page with a completely blank, empty page.

Unlike similar extensions, Nothingness contains no ads whatsoever. It also includes no extra features, data collection, or required permissions. It does one thing and does it perfectly: delivers a clean, distraction-free new tab every time.

## Features
- Overrides `chrome://newtab` with an empty white (or black in dark mode) page.
- No UI, no permissions, no background scripts, nothing else.

## Installation
1. Open Chrome and go to `chrome://extensions/`
2. Enable "Developer mode" (top right).
3. Click "Load unpacked".
4. Select this `nothingness` folder.

## Homepage / Home button
Chrome extensions cannot override the homepage or home button to a local/extension page (or data: URL).

To also get a blank page for the Home button (`Alt+Home`):

1. Go to `chrome://settings/appearance`
2. Turn on "Show home button"
3. Choose "New Tab page"

Now both new tabs and the home button will show the blank page.

## Files
- `manifest.json` — declares the new tab override.
- `blank.html` — the empty page (adapts to light/dark).
