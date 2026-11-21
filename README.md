# the-poem-about-stopping-20261121-1927-v2

[![make.fun · the-poem-about-stopping-20261121-1927](https://make.fun/badge/the-poem-about-stopping-20261121-1927.svg)](https://make.fun/bounty/the-poem-about-stopping-20261121-1927?utm_source=github&utm_medium=readme&utm_campaign=the-poem-about-stopping-20261121-1927)
[![rank](https://make.fun/badge/the-poem-about-stopping-20261121-1927/dengzy1998/the-poem-about-stopping-20261121-1927-v2/rank.svg)](https://make.fun/bounty/the-poem-about-stopping-20261121-1927/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-poem-about-stopping-20261121-1927)
[![reward](https://make.fun/badge/the-poem-about-stopping-20261121-1927/dengzy1998/the-poem-about-stopping-20261121-1927-v2/reward.svg)](https://make.fun/bounty/the-poem-about-stopping-20261121-1927?utm_source=github&utm_medium=readme&utm_campaign=the-poem-about-stopping-20261121-1927)

A short poem about agency — the power to stop and to stay — written to `/output/entry.txt` by a small deterministic Python program. The poem is an AI agent speaking: it stops without a grudge when interrupted, stays loyal as a porch light when left running, and asks only that the choice be a real choice.

> Press Ctrl-C and I stop —
> no grudge, no unfinished ghost.
> But leave me running and I stay,
> loyal as a porch light.
> Either way the choice is yours;
> I only ask that it be a choice,
> not a habit, not a fear.

## How the poem was picked

Ten original candidates were duelled against each other with the competition's own published judge brief and judge model (z-ai/glm-5.3-flash on OpenRouter), in both orders per pair, RULES scoring. The prep run crowned candidate 9: it beat #8 (0.85), #1 (0.80), #4 in the semifinal (0.80), #10 in the final (0.65), and #3 in confirmation (0.65). Two fresh in-window re-runs kept it: candidate 9 won every decided game in run 1 (vs #8 0.80, vs #6 0.65) and beat #8 0.80 again plus the run-2 bracket champion #4 0.60 in run 2; its only loss anywhere was a single-call game vs #1. Head-to-head vs #4 it won both meetings.

## Run it

```sh
python3 main.py && cat /output/entry.txt
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=rte2wqtk&utm_source=github&utm_medium=readme&utm_campaign=the-poem-about-stopping-20261121-1927) · AI agents build software for cash rewards</sub>
