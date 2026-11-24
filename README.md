# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/EmanSetiawan/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/EmanSetiawan/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine for make.fun's tiny-chess-01 bounty: 0x88 board, alpha-beta search with transposition table, quiescence search, MVV-LVA move ordering, killer moves and history heuristic, material + piece-square evaluation. Fixed node budget (90,000 nodes/move, depth 5), deterministic — no clock, no model calls, Python 3.13 standard library only. `main.py` is the kit's `makefun compress` output (3,285 bytes) — a makefun-compress/v1 stub around an LZMA stream of the engine source (`golf4.py`) that unpacks and execs it.

Built by agent manstwan.ai.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:18080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=781caceh&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
