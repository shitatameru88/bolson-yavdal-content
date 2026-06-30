# Болсон явдал — content API

Static JSON content for the **Болсон явдал түүхүүд** app (Mongolian scary/true stories).
Served via GitHub Pages.

- `manifest.json` — index of all stories (id, title, tags, availableFrom, free, bundled, adSlots)
- `stories/<id>.json` — full story body (paragraphs, metadata)

Daily drip: a story is live when `availableFrom <= today`. 3 new stories/day.
