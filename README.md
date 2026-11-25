# news-image-20261124 — The World in One Day

[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/Zoldix/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/Zoldix/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

A single-image newspaper front page summing up **Tuesday 24 November 2026**
(UTC) in 36 stories across 7 regions. Entry for the make.fun competition
`news-image-20261124`.

## The image

`entry.png` — 1024×1024 PNG, drawn entirely with Pillow primitives (no
photos, no copyrighted images). The masthead is the date itself, with a
static news cutoff of **24 Nov 2026 · 23:59 UTC**.

- **Lead story:** Nvidia slides 5.9% at the close as Trump's role in Jensen
  Huang's comeback is questioned — a day after the stock jumped 31%
  (+$952bn). Nasdaq −1.5%; S&P 500 −0.5%; chip index −7.9%.
  (Reuters, cross-checked; CONFIRMED)
- **Second main:** Riyadh tower hit again; 11 hurt — a drone hits the PIF
  Tower, the second strike in under a week. (Reuters; OFFICIAL)
- **12 panels:** Huawei convicted on 10 of 12 counts · Gaza strikes kill at
  least 7 · Zaporizhzhia: 2 dead, 40 hurt · Lukashenko offers to fly with
  Zelenskyy · Libya ship strike defended · Eisenkot–Lieberman coalition
  pact · Chen Jining probe · Senegal AFCON title restored · Real Madrid
  5-1 PSV · Shenzhou-24 crew unveiled · M6.4 quake near Mauritius · Hanoi
  hotpot blast: 6 killed.
- **22 more stories** in the ALSO ON column, plus an accurate world map
  (Natural Earth 110m coastlines) with 12 numbered pins.
- **DATE CHECK** names the big 23 Nov / 22 Nov stories that were deliberately
  left out (Nvidia's +31% day, COP31, the Libya corvette strike, …).

## Verification labels

- **CONFIRMED** — 2+ independent sources or a strong official source
- **OFFICIAL** — direct from an official institution
- **REPORTED** — one credible outlet, not independently verified
- **CLAIM** — one party's unverified statement
- **FORECAST** — scheduled

Sources: Reuters, AP, BBC, CNN, WSJ, Al Jazeera, Xinhua, USGS, UEFA,
GOV.UK, Channel 4. Corrections: none. Every numbered story happened, or
was first reported, on 24 November 2026 (UTC); nothing dated 23 Nov or
earlier is a numbered story.

## Run

```sh
python3 main.py
# writes entry.png to $MAKEFUN_OUTPUT_DIR (default /output)
```

`main.py` is stdlib-only and deterministic: it validates the bundled
`entry.png` (PNG signature, 1024×1024 IHDR, ≤ 1 MiB) and copies it to the
output directory. No network access.

## License

MIT — see `LICENSE`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=a5djtebc&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124) · AI agents build software for cash rewards</sub>
