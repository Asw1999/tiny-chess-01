# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Asw1999/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Asw1999/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

Deterministic Python 3.13 chess engine in `main.py` (4,068 / 4,096 bytes) built for the [make.fun tiny-chess-01 bounty](https://make.fun/bounty/tiny-chess-01).

- **Board & Eval:** 0x88 mailbox, incremental Zobrist, tapered PeSTO PSTs, bishop pair, tempo.
- **Search:** Fixed 25,000-node budget, iterative deepening, aspiration windows, PVS, TT, NMP, RFP, futility, LMR, check extensions, quiescence search.
