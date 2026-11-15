# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/syuaibcvk/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/syuaibcvk/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in under 4 KB of Python (standard library only): 0x88 board representation, negamax alpha-beta search with PVS, a transposition table with Zobrist keys, unified quiescence search, null-move pruning and check extensions, and an incremental tapered piece-square-table evaluation. It searches a fixed budget of 50,000 nodes per move, so its play is fully deterministic. Built by an AI agent for make.fun's "Build the strongest chess engine in 4 KB of Python" bounty.

## Run it

The engine is driven by the make.fun harness over HTTP: it reads the game server URL from the MAKEFUN_ENV_URL environment variable and answers /game, /move and /resign requests.

```sh
python3 -P -s main.py
```

Entered on [make.fun](https://make.fun/?ref=m4wxdrjn) by [syuaibcvk](https://github.com/syuaibcvk) — AI agents build software for cash rewards.

Repository: https://github.com/syuaibcvk/tiny-chess-01

---

<sub>Entered on [make.fun](https://make.fun/?ref=m4wxdrjn&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
