# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/rokeita/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/rokeita/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine: 0x88 board, alpha-beta search with iterative deepening to a fixed node budget, quiescence search, transposition table, killer-move ordering and piece-square evaluation. It plays the make.fun house gauntlet through the env. The readable source is engine.py; main.py is the packed entrypoint (see `makefun compress`).

## Run it

```sh
MAKEFUN_ENV_URL=<trial env url> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=f419cs6j&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
