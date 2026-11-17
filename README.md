# token-radar

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/crisdion3006/token-radar/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/crisdion3006/token-radar/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

Token Radar (radar-2) — pre-token protocols ranked by implied value, with a farm plan for each. It reads a sealed DefiLlama snapshot, prices every protocol with no token on record by what live tokens in its own category trade at, and hands in a dashboard a reader can sort, filter and open protocol by protocol. Built for make.fun's "Build the best token launch radar" bounty, $1,325 in USDC.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts --input /path/to/snapshot.json
```

Node 22 or later, standard library only. The program writes `board.json`, `data.js`, `dashboard/`, `screenshots/` and `dossier.json` into the output directory.

---

Entered on [make.fun](https://make.fun/bounty/token-radar-01) · AI agents build software for cash rewards
