# Rachit's site — illustration update

## What's in this folder

- `index.html` — your patched homepage with 12 new illustration slots wired in
- `images/` — 12 renamed illustration files ready to drop into your repo's existing `images/` folder

## Where each illustration lands

| Section | File | Caption |
|---|---|---|
| 01 — About (mid) | `illust-reading.png` | "Learning, in the quiet hours" |
| 01 — About (end) | `illust-collage.png` | "Many sides — one person" |
| 03 — Why Game Algorithms? | `illust-chess.png` | "Games as laboratories" |
| 04 — Projects (Game Algorithms Engine card) | `illust-laptop.png` | floats right on desktop, hidden on mobile |
| 05 — How I Approach Problems | `illust-thinking.png` | "Structure first. Code last." |
| 06 — Achievements | `illust-trophy.png` | (no caption) |
| 07 — Theatre | `illust-spotlight.png` | "The stage as a social tool" |
| 09 — Beyond → Mountains | `illust-trek.png` | "The same attention Astachal had been teaching" |
| 10 — Currently | `illust-meditate.png` | "Still listening" |
| 11 — Writing | `illust-writing.png` | (no caption) |
| 12 — Contact | `illust-wave.png` | "Say hi" |

Plus `illust-thinking-transparent.png` is in the images folder as an alternate of the thinking illustration with a transparent background — not currently used in the HTML, but available if you want to swap it in somewhere as a floating accent over a textured area.

## To deploy

1. Copy everything in this folder's `images/` into your repo's `images/` folder (the same one that already has `Astachal.jpg`, `JK.jpeg`, `vriksha.png`, etc.)
2. Replace your repo's `index.html` with the one in this folder
3. Commit and push — GitHub Pages will pick it up

## Style notes

- All 12 placements use your existing `photo-slot ratio-1-1` class — same gold border, same hover lift, same aesthetic as your other photos
- Sizes are constrained with inline `max-width` (280–480px) so they read as accents rather than dominating their sections
- The Game Algorithms Engine illustration uses `float-right` + `hidden md:block` so it tucks into the project description on desktop and disappears on mobile (where the card is already dense)
- Mobile tested via the responsive utilities — all illustrations are centered and full-width within their max-width container

## If you want to remove or swap any

Each illustration is wrapped in a clearly-labelled HTML comment like `<!-- Illustration: the studious self -->` — search for that pattern in `index.html` and you can pull or rearrange any of them in seconds.
