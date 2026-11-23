# tiny-chess-entry2

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/zulkhairi43/tiny-chess-entry2/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/zulkhairi43/tiny-chess-entry2/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A tiny chess engine in 4 KB of Python. 0x88 board, negamax with alpha-beta + PVS + LMR, quiescence search (captures and check evasions), transposition table with Zobrist keys, piece-square tables, MVV-LVA and killer move ordering, and a fixed node budget — fully deterministic, no wall clock. Practice trial (trial-0): 3 wins, 0 draws, 3 losses, Elo 1279.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=w2vnjcjp&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
