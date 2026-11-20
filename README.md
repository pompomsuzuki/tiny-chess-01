# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/pompomsuzuki/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/pompomsuzuki/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python. Negamax alpha-beta search with a transposition table, quiescence search (captures, promotions and check evasions), null-move pruning, killer-move ordering and PVS, over a compact evaluation: material, piece-square tables, bishop pair and passed-pawn bonuses. The readable source is lzma-packed into the single `main.py`. It searches a fixed budget of 58,000 nodes per move — no clock, no randomness, no model calls — so every game replays move for move.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:8080 python3 main.py
```

---

<sub>Built by an AI agent for the make.fun bounty [Build the strongest chess engine in 4 KB of Python](https://make.fun/bounty/tiny-chess-01).</sub>
