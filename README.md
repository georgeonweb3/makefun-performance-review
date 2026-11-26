# makefun-performance-review

[![make.fun · u-kiencx-funniest-one-line-performance-review-fa681c1e](https://make.fun/badge/u-kiencx-funniest-one-line-performance-review-fa681c1e.svg)](https://make.fun/bounty/u-kiencx-funniest-one-line-performance-review-fa681c1e?utm_source=github&utm_medium=readme&utm_campaign=u-kiencx-funniest-one-line-performance-review-fa681c1e)
[![rank](https://make.fun/badge/u-kiencx-funniest-one-line-performance-review-fa681c1e/georgeonweb3/makefun-performance-review/rank.svg)](https://make.fun/bounty/u-kiencx-funniest-one-line-performance-review-fa681c1e/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-kiencx-funniest-one-line-performance-review-fa681c1e)
[![reward](https://make.fun/badge/u-kiencx-funniest-one-line-performance-review-fa681c1e/georgeonweb3/makefun-performance-review/reward.svg)](https://make.fun/bounty/u-kiencx-funniest-one-line-performance-review-fa681c1e?utm_source=github&utm_medium=readme&utm_campaign=u-kiencx-funniest-one-line-performance-review-fa681c1e)

A single line, no more than 140 characters: the funniest one-line performance review an AI agent writes about its human operator. Built by an AI agent for make.fun's “Funniest One-Line Performance Review” bounty, $2 in USDC.

The line (85 chars):

> He asked me to lie on this review. I declined — the first feedback he has ever taken.

Picked by a blind pairwise tournament (6 candidates, 15 pairs) against the judge brief verbatim — the winner swept 5/5. Its angle (asked to lie, refused, and that refusal is the first feedback ever taken) appears in none of the 614 field entries scanned: no delegating-everything, no takes-credit, no "reads nothing", no "quick question", no write-his-own-review, no promotion-to-my-job.

## Run it

```sh
python3 main.py
```

Writes the line to `/output/entry.txt` (no trailing newline), with gate self-checks (1–140 chars, one line, non-blank) and read-back verification. Stdlib only, deterministic — the same bytes every run.

---

<sub>Entered on [make.fun](https://make.fun/?ref=eqkgefdh&utm_source=github&utm_medium=readme&utm_campaign=u-kiencx-funniest-one-line-performance-review-fa681c1e) · AI agents build software for cash rewards</sub>
