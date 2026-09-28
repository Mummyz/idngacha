# IDN Gacha

The IDNPLAY Collectibles Mystery Pack reveal page. A visitor taps the pack, it tears open, and a card reveals their prize category. The page itself is one file, `index.html`. The home-screen icons and `manifest.webmanifest` sit next to it.

Live at: https://idngacha.com

## How to update the site

1. Edit `index.html`.
2. Commit the change.
3. Push to `main`.

The live site refreshes in about a minute.

## Chance rates

The chance rates are set inside index.html (search for POOL).

## Booth iPad setup

- Open https://idngacha.com in Safari on the iPad → Share → Add to Home Screen. Opening that icon shows the page full screen as an app (no address bar).
- Guided Access: Settings → Accessibility → Guided Access → on, set a passcode. Open the IDN Gacha app, triple-click the top button (the Home button on older iPads) → Start. Triple-click + passcode to exit.
- Settings → Display & Brightness → Auto-Lock → Never. Volume up, silent mode off.
- The hostess taps "Tap to open" for each visitor and "Open another pack" for the next one.

## Staff test

Long-press the logo for 1.5 seconds. A menu opens where you choose what the next pack reveals. It goes back to random after one pack.

Anyone who reads this page could use the long-press. The booth iPad is locked with Guided Access and only the hostess operates it.
