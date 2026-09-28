# IDN Gacha

The IDNPLAY Collectibles Mystery Pack reveal page. A visitor taps the pack, it tears open, and a card reveals their prize category. The page itself is one file, `index.html`. The home-screen icons and `manifest.webmanifest` sit next to it.

Live at: https://idngacha.com

## How to update the site

1. Edit `index.html`.
2. Commit the change.
3. Push to `main`.

The live site refreshes in about a minute.

## Chance rates

Chances per pack: Advance 66.25%, Elite 18.75%, Legendary 10% (1 in 10), Ultimate 5% (1 in 20). Every pack is a fresh draw; nothing is counted or stored. Set inside index.html (search for CHANCES).

## Two QR codes

- On the pack (start screen): IDNPLAY Instagram, https://www.instagram.com/idnplay_official
- On the card back after "Show Raffle QR": the raffle entry form, https://idnapi.fillout.com/raffle
- The QR drawings live inside index.html; to change a link, ask Claude to redraw that QR.

## Hostess flow

Tap to open → category revealed → Show Raffle QR (visitor scans) → Open another pack.

## Booth iPad setup

If the IDN Gacha icon was added to the iPad home screen before v1.2.0, delete it and add it again so the new IDNPLAY icon appears.

- Open https://idngacha.com in Safari on the iPad → Share → Add to Home Screen. Opening that icon shows the page full screen as an app (no address bar).
- Guided Access: Settings → Accessibility → Guided Access → on, set a passcode. Open the IDN Gacha app, triple-click the top button (the Home button on older iPads) → Start. Triple-click + passcode to exit.
- Settings → Display & Brightness → Auto-Lock → Never. Volume up, silent mode off.
- The hostess taps "Tap to open" for each visitor and "Open another pack" for the next one.

## Staff test

Long-press the logo for 1.5 seconds. A menu opens where you choose what the next pack reveals. It goes back to random after one pack.

Anyone who reads this page could use the long-press. The booth iPad is locked with Guided Access and only the hostess operates it.
