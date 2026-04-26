# Atlas of the Arabic Dialects

أَطلَسُ اللَّهَجاتِ العَرَبِيَّة

An interactive cartography of **82 Arabic dialects** across the Middle East and North Africa — Levant, Egypt, Iraq, Arabia, Yemen, Sudan, and the Maghreb. Hand-drawn SVG maps, sample phrases, phonology, history, and a side-by-side comparison drawer.

## Run it

It's a single self-contained HTML file with no build step and no external API calls.

- **Locally**: open `index.html` in a browser, or
  `python3 -m http.server 8000` and visit `http://localhost:8000/`.
- **Deployed**: any static host (Vercel, Netlify, GitHub Pages, Cloudflare Pages) will serve it as-is.

## Features

- **7 regional maps** — Levant, Nile Valley, Iraq, Arabia & Gulf, Yemen, Sudan & Sahel, Maghreb.
- **Two themes** — parchment day mode and a midnight-scriptorium night mode (toggle with `T` or the moon/sun button; auto-detects `prefers-color-scheme`).
- **Compare drawer** — pin up to 3 dialects side-by-side; differences in qāf/jīm are highlighted automatically.
- **Today's Featured Dialect** — date-seeded pick that rotates daily.
- **Surprise me** — random dialect with a delightful spin animation (`R`).
- **Smart search** — Arabic + English + Latin transliteration; falls back to fuzzy (Levenshtein) matching for typos; tracks recent searches.
- **Filters** — qāf shibboleth (ʔ / q / g), endangered, Bedouin.
- **Keyboard shortcuts** — `?` for the full overlay; `/` and `⌘K` focus search; `← →` walk dialects; `C` add to compare; `Shift+C` open comparison drawer; `Esc` close.
- **Region overview** — dialect counts and total speakers per region.
- **Hash routing** — deep-link straight to any dialect (`#dialect/cairene`) or region (`#region/maghreb`).
- **Responsive** — mobile, tablet, and desktop layouts; sticky map+panel on wide viewports.

## Linguistic threads

The atlas foregrounds three letters that do most of the work in distinguishing Arabic dialects:

- **ق qāf** — *ʔ* in urban Cairo/Damascus/Beirut/Jerusalem, preserved *q* in Druze/Mosuli/Tunisian/Tihami pockets, *g* across Bedouin/Najdi/Sudanese/Hijazi.
- **ج jīm** — uniquely *g* in Egyptian, *ʒ* in Levantine and Maghrebi, *dʒ* in Gulf/Iraqi, *y* in Najdi.
- **Vowels** — northern Levantine *imāla* (`bāb` → `bēb`), Maghrebi vowel deletion (`katabtu` → `ktbt`), full vowels preserved in Yemeni and Hijazi.

## Sources

Linguistic data synthesised from:

- Versteegh, *The Arabic Language* (Edinburgh, 2014)
- Behnstedt & Woidich, *Arabische Dialektgeographie* (Brill, 2005)
- Holes, *Modern Arabic* (Georgetown, 2004)
- Watson, *Phonology and Morphology of Arabic* (Oxford, 2002)
- Ingham, *Najdi Arabic* (Benjamins, 1994)
- Procházka — peripheral varieties (Cypriot Maronite, Anatolian, Khorasani, Uzbeki).

Country borders from **Natural Earth** (50m, public domain).

## A note on dialect borders

Real dialect boundaries are *gradients*, not lines. Within a single village, a Christian neighbour, a Druze neighbour, and a Muslim neighbour may pronounce the same word three different ways. This atlas captures the centre of gravity of each dialect — a guide to the music, not the score.

## License

Content is licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/).
