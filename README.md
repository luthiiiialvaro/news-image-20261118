# news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/luthiiiialvaro/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/luthiiiialvaro/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

One image that sums up the world's news of Wednesday 18 November 2026: a
newspaper front page, drawn as a single 1024×1024 PNG. The masthead names
the day, the lead story is the widening Gulf war, and five more stories
plus a ticker cover the rest of the day across regions and fields.

## The stories in the image

- **Lead — The Gulf:** Washington confirmed US jets hit a Revolutionary
  Guard missile site on Qeshm Island; Iran answered with drones on US
  sites in Bahrain and Kuwait on Wednesday.
- **Asia-Pacific — Shenzhen summit:** Trump landed in Shenzhen for a
  three-way meeting with Xi Jinping and Vladimir Putin on Thursday; Xi
  and Putin opened the APEC summit denouncing protectionism and Western
  sanctions.
- **Ukraine — Kerch Bridge:** Ukraine's strikes destroyed the bridge's
  road span, which lies in the strait; rail service resumed while Russia
  hit back with 141 drones overnight.
- **United States — Alaska:** Democrat Mary Peltola won Alaska's Senate
  race, giving Democrats a 56–44 majority, their largest since 2009.
- **Africa — Ebola:** the outbreak in the Democratic Republic of Congo
  passed 11,000 cases and 5,400 deaths; children bear the heaviest toll.
- **Also today:** Voyager 1 reaches one light-day from Earth; a Russian
  military plane crashes in Siberia, killing 19; a 5.3-magnitude quake
  hits Romania; Cyclone Xavier strikes the Cook Islands; 146,000 protest
  across France over living costs.

## How it was made

The front page was composed with Python (Pillow) from four flat editorial
illustrations and one drawn panel (the Ebola motif). The entry program
`main.py` (Python 3.13, standard library only) validates the image and
copies it to `/output/entry.png`; both graded runs write the same bytes.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
# writes out/entry.png, byte-identical to entry.png in this repo
```
