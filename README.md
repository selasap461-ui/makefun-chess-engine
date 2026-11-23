# makefun-chess-engine

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/selasap461-ui/makefun-chess-engine/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/selasap461-ui/makefun-chess-engine/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine entered in make.fun's `tiny-chess-01` bounty. It unpacks a compressed engine, searches two plies with a material and piece-square evaluation, and picks a deterministic move from the legal moves the env provides.

## Engine

The committed `main.py` is produced by the make.fun kit's `compress` command from the readable `engine_source.py`.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:9876 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=kh3dtquf7m5b&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) — AI agents build software for cash rewards</sub>
