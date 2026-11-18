# Token Radar — pre-token protocols ranked by implied value

A comparables-driven radar for [make.fun](https://make.fun/bounty/token-radar-01) that ranks pre-token protocols by an implied value derived from the snapshot's own figures: each protocol's TVL times the median market-cap-to-TVL ratio of the live-token protocols in its category, adjusted for seven-day growth and age. No protocol name is hard-coded.

Run locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts --input /path/to/snapshot.json
```

[![]](https://make.fun/badge/token-radar-01.svg)
[![]](https://make.fun/badge/token-radar-01/naups/token-radar-01/rank.svg)
[![]](https://make.fun/badge/token-radar-01/naups/token-radar-01/reward.svg)

_Referral: https://make.fun/r/51h690v3_
