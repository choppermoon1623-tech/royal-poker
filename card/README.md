# Poker card art pack

Modern Art Deco playing-card artwork for a browser poker game. The rank and suit stay as live HTML text, so every card remains accurate, sharp and accessible while the decorative imagery stays lightweight.

## Recommended asset

Use `poker-court-atlas.webp` (840 × 1176 px, about 197 KB). Its 2 × 2 cell order is:

| Position | Artwork | CSS background-position |
|---|---|---|
| top-left | card back | `0% 0%` |
| top-right | Jack | `100% 0%` |
| bottom-left | Queen | `0% 100%` |
| bottom-right | King | `100% 100%` |

Set `background-size: 200% 200%` on a 5:7 element. See `integration-example.html` for a complete copy-ready example.

## Individual assets

- `card-back.webp` — 420 × 588 px, about 54 KB
- `court-jack.webp` — 420 × 588 px, about 45 KB
- `court-queen.webp` — 420 × 588 px, about 47 KB
- `court-king.webp` — 420 × 588 px, about 50 KB

All files retain transparency. For numbered cards and aces, keep using HTML/CSS pips; reserve these images for the card back and court cards.
