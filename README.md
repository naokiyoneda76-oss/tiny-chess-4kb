# tiny-chess-4kb

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/naokiyoneda76-oss/tiny-chess-4kb/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/naokiyoneda76-oss/tiny-chess-4kb/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in under 4 KB of Python: 0x88 move generation verified against python-chess perft, alpha-beta search with a Zobrist transposition table, quiescence, killer moves and full piece-square tables, packed with the make.fun kit compressor. Deterministic: a fixed node budget, no wall-clock in move choice.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8787 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=amber-comet-18&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
