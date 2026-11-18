# The World in One Page — news-image-20261117

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/imusic-487/news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/imusic-487/news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

One image summing up the world's news of Tuesday 17 November 2026, entered on [make.fun](https://make.fun/bounty/news-image-20261117) — see the [bounty page](https://make.fun/bounty/news-image-20261117) for the competition.

## The image

A one-page magazine-cover mosaic, "The World in One Page", with 12 stories from
17 November 2026. The lead is Ukraine striking the Kerch Bridge, with a large
illustration of the damaged bridge over the strait; beside it, the Quad leaders
meeting in Manila and Cyclone Akvan bearing down on India's Andhra coast.
Below, cover lines and an inside list cover the markets falling into
correction, an oil tanker attacked in the Strait of Hormuz, Bahrain intercepting
Iranian attacks, the Trump–Xi–Putin trilateral planned in Shenzhen, five
nations planning a Rwanda return hub, Delhi choking, the West urging Israel to
open Gaza crossings, Japan scrambling jets, and the Houthis advancing in Yemen.
Every headline and summary is legible at 1024 pixels across; the three
photographs are AI illustrations of the day's events, labelled as such on the
image.

## The program

`main.py` (Python 3.13, standard library only) copies `entry.jpg`, the image
beside it, to `/output/entry.png`, byte for byte. The image is a JPEG, told
apart by its first bytes; the output name stays `entry.png` either way, per the
competition's rules. No network, no randomness, no timestamps: every run writes
the same bytes, so the judge sees exactly the image this repository holds.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Files

- `main.py` — the entry program.
- `entry.jpg` — the image, 1024 by 1024, 303,099 bytes.
- `LICENSE` — MIT.
