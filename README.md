[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/akbarrrputraa/news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/akbarrrputraa/news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

# news-image-20261117 — The World in One Image: Tuesday, 17 November 2026

Entry for the [make.fun competition **"Sum up 17 November's world news in one
image"**](https://make.fun/bounty/news-image-20261117) ($250, free entry).

## The image

`entry.png` (1024×1024, PNG) is a newspaper front page summing up Tuesday
17 November 2026:

- **Lead:** Trump, Xi and Putin to meet in Shenzhen — China confirms a
  first-ever trilateral summit on Thursday 19 November, on the sidelines of
  APEC, with Ukraine, trade and security on the agenda.
- **Middle East:** Iranian drones target a US radar site in Bahrain and are
  intercepted; Trump warns of a naval blockade.
- **Ukraine:** Russian missiles hit bridges over the Dnipro in Kyiv; Ukraine
  says it damaged the Kerch Bridge in reply.
- **Health:** the US loses its measles elimination status after nearly three
  decades.
- **Gaza:** the UK, Australia, Canada and Italy urge Israel to open the
  crossings as UN agencies warn of a winter emergency.
- **Asia:** Japan scrambles jets after Russian aircraft enter its airspace.
- **Tech & markets:** the US tightens AI chip export curbs; stocks fall
  ahead of Nvidia earnings.
- **Also:** COP31 in Antalya enters its decisive phase; Depardieu admits a
  sexual assault charge; a banking outage hits Chase and Zelle.

The page was composed in `poster.html` (hand-written HTML/CSS with inline
SVG flags and icons) and rendered to `entry.png` with headless Chromium at
1024×1024. The render was checked by eye: every story legible, nothing
clipped, no garbled text.

## The program

`main.py` (Python 3.13, standard library only) copies `entry.png` to
`/output/entry.png`, byte for byte. No network, no dependencies, no
randomness — the grader's two runs write identical bytes.

Run it outside the grader with:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see `LICENSE`.
