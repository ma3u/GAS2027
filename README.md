# S9 — The Knowledge Transfer Gap

Workgroup outcome from **Group #2** at the **Group Architect Summit 2026** (28–29 September 2026, Katowice).

**Subject T5 / S9 — "How do we train tomorrow's seniors if juniors no longer code?"**

👉 **[Open the presentation](https://ma3u.github.io/GAS2027/)**

## What is in here

A four-slide deck built with [reveal.js](https://revealjs.com):

1. **The question** — the subject the table picked, photographed from the summit sheet.
2. **What we found** — three clusters from the working board: learning and skills, the junior dev pattern, cost and dependency.
3. **The table deliverable** — a mentoring and skills plan on three pillars, with the three actions the table voted to start with.
4. **Pair programming with AI** — the comic strip, full screen.

Every claim on the slides comes from the sticky notes on the Group #2 board. Both photographs are in
`assets/img/` and are clickable in the deck for the full-resolution originals.

## Sharing it

The page carries Open Graph and Twitter card tags, so a link pasted into LinkedIn, Slack or
Bluesky unfurls with the comic and the headline question *"If AI writes the code, where do the
next senior engineers come from?"*. The preview image is `assets/img/og-preview.jpg`, sized
1200×630.

LinkedIn caches previews aggressively. If you have already shared the link once, refresh it
through the [Post Inspector](https://www.linkedin.com/post-inspector/) before posting again.

## Using the deck

| Key | Action |
| --- | --- |
| `→` / `Space` | Next slide or next build step |
| `←` | Back |
| `S` | Speaker notes, with the talk track for each slide |
| `F` | Full screen |
| `O` | Slide overview |

Append `?print-pdf` to the URL and print from the browser to export a PDF.

## Running it locally

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Layout

```
index.html                      the three slides
assets/css/deck.css             the theme
assets/img/agenda-sheet.jpg     the printed summit subject sheet
assets/img/topic-s9.jpg         the S9 subject, cropped
assets/img/whiteboard.jpg       the Group #2 working board
assets/img/action-points.jpg    the action points, cropped
assets/img/comic-close.jpg      closing panel, pair programming with AI
assets/img/pair-programming-comic.jpg   the full strip, shown on slide 4
assets/img/og-preview.jpg       1200x630 link preview card
```
