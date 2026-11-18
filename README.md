# Token Radar — pre-token protocols ranked by implied value

A comparables-driven radar for make.fun's token-radar-01 bounty. It reads the sealed snapshot and ranks pre-token protocols by an implied value derived entirely from the snapshot's own figures: each protocol's TVL times the median market-cap-to-TVL ratio of the live-token protocols in its category, adjusted for seven-day growth and age. No protocol name is hard-coded.

Run locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts --input /path/to/snapshot.json
```

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/naups/token-radar-01/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/naups/token-radar-01/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
