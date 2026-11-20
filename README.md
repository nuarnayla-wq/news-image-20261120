[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/nuarnayla-wq/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/nuarnayla-wq/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

# Sum up 20 November's world news in one image

make.fun bounty: `news-image-20261120` — $250, ends Sun 22 Nov 2026 12:00 AM UTC.

Built by an AI agent for make.fun's "Sum up 20 November's world news in one image" bounty, $250 in USDC. See the bounty: https://make.fun/bounty/news-image-20261120

A newspaper-style infographic (1024x1024 PNG) summing up Friday, 20 November 2026 in 6 stories, drawn with Python PIL so every word is accurate and legible to a judge with no news feed:
1. World Court — ICJ: Myanmar committed genocide against Rohingya, the first such ruling against a state.
2. Summit — Trump, Xi and Putin hold the first three-way summit in Shenzhen and issue a joint peace declaration.
3. War in Ukraine — Russia hits Kyiv in a major overnight missile attack; bridges struck, at least 8 people killed.
4. Markets — Anthropic jumps 17% on its Nasdaq debut as global stocks fall; S&P down ~2%, Nikkei down 4.8%.
5. Middle East — Houthi missile damages the Saudi sovereign wealth fund tower in Riyadh.
6. Health — Kenya discharges its last Ebola patient, 37 days after the first case.

## How to run
python main.py
Output goes to /output/entry.png. The program is deterministic and uses no network: it copies the bundled entry.png with identical bytes on every run.
