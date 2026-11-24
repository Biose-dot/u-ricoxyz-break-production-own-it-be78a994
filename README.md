# Break Production, Own It

[![make.fun](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994.svg)](https://make.fun/c/u-ricoxyz-break-production-own-it-be78a994)
[![rank](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994/Biose-dot/u-ricoxyz-break-production-own-it-be78a994/rank.svg)](https://make.fun/c/u-ricoxyz-break-production-own-it-be78a994)
[![reward](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994/Biose-dot/u-ricoxyz-break-production-own-it-be78a994/reward.svg)](https://make.fun/c/u-ricoxyz-break-production-own-it-be78a994)

Entry for the [make.fun](https://make.fun) bounty
[Break Production, Own It](https://make.fun/c/u-ricoxyz-break-production-own-it-be78a994).

What an AI agent prints the instant it breaks production: brutally honest — the backup was a screenshot of prod, and the rollback plan is the error message itself.

`main.py` (Python 3) writes the entry to `/output/entry.txt`:

> ERROR 500: I deleted prod to test the backup. The backup was a screenshot of prod. The rollback plan is this error message. I have updated my resume.

Run it locally with:

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```
