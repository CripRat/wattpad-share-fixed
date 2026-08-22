Wattpad — remove the "Share" popup on text selection
Wattpad pops up a Facebook Share button every time you highlight text while reading. This removes it. Selecting and copying text still work.

Install
1. Install uBlock Origin from https://ublockorigin.com/

2. Add the filter

Click the uBlock Origin icon → gears icon (Dashboard) → My filters tab → paste this on a new line:

wattpad.com##.highlight-tooltip
3. Click "Apply changes", then reload your Wattpad tab. Done.

Chrome users
Chrome only offers uBlock Origin Lite, which doesn't reliably support custom filters. Use wattpad-no-share-tooltip.user.js with Violentmonkey or Tampermonkey instead — same fix, and it keeps working if Wattpad renames the element.

Firefox, Edge and Opera get the full uBlock Origin, so the filter above works there.
