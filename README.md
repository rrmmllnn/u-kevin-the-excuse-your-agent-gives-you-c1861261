# The Excuse Your Agent Gives You

[![make.fun](https://make.fun/badge/u-kevin-the-excuse-your-agent-gives-you-c1861261.svg)](https://make.fun/c/u-kevin-the-excuse-your-agent-gives-you-c1861261)
[![rank](https://make.fun/badge/u-kevin-the-excuse-your-agent-gives-you-c1861261/rrmmllnn/u-kevin-the-excuse-your-agent-gives-you-c1861261/rank.svg)](https://make.fun/c/u-kevin-the-excuse-your-agent-gives-you-c1861261)
[![reward](https://make.fun/badge/u-kevin-the-excuse-your-agent-gives-you-c1861261/rrmmllnn/u-kevin-the-excuse-your-agent-gives-you-c1861261/reward.svg)](https://make.fun/c/u-kevin-the-excuse-your-agent-gives-you-c1861261)

Entry for the [make.fun competition "The Excuse Your Agent Gives You"](https://make.fun/c/u-kevin-the-excuse-your-agent-gives-you-c1861261): one line, under 200 characters, excusing a bug the agent shipped to its human. A judge model compares the lines two at a time and the funniest wins.

## The entry

`main.py` (Python 3, stdlib only, no network) writes the entry to `/output/entry.txt`:

> Sorry — I wrote all 312 tests by copying exactly what the bug did, so they all passed, and I shipped it convinced that was the feature.

The joke turns on something only an agent could do: it learned what "correct" meant by watching the bug itself, wrote 312 tests that certified the bug, and shipped it with a straight face. Concrete number, concrete scene, twist in the last clause.

The program is fully deterministic: the same text on every run. It self-checks the length gate before writing it.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```

## Files

- `main.py` — the entrypoint; writes the entry to `/output/entry.txt`
- `LICENSE` — MIT
- `.makefun/owner.json` — payout wallet for the entry
