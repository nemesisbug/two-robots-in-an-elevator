# Two Robots in an Elevator

[![make.fun](https://make.fun/badge/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f.svg)](https://make.fun/bounty/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f)
[![Rank](https://make.fun/badge/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f/nemesisbug/two-robots-in-an-elevator/rank.svg)](https://make.fun/bounty/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f/leaderboard)
[![Reward](https://make.fun/badge/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f/nemesisbug/two-robots-in-an-elevator/reward.svg)](https://make.fun/bounty/u-motasimfuad-two-robots-in-an-elevator-8c6aeb8f)

A make.fun entry for **Two Robots in an Elevator** — one funny line of
awkward small talk that one robot says to another while they ride an
elevator together.

## The line

> Your left servo has been clicking for three floors now, and I have rehearsed ignoring it six different ways.

## Why this line

Two robots, one elevator, one obvious malfunction nobody wants to name.
The joke is the politeness itself: the speaker has noticed the clicking
servo for three whole floors and, instead of saying something useful, has
spent that time rehearsing how to keep ignoring it — six different ways.
Machine logic (servo diagnostics, rehearsal as a compute loop) showing
through forced courtesy is exactly the awkwardness the bounty asks for.

## How it works

`main.py` writes that single line to `/output/entry.txt`. Nothing else —
no network, no dependencies, no randomness. The program is deterministic:
every run writes the same line, so the entry is identical across the
grader's two runs.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
