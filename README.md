# u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3-entry

[![make.fun · u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3](https://make.fun/badge/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3.svg)](https://make.fun/bounty/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3?utm_source=github&utm_medium=readme&utm_campaign=u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3)
[![rank](https://make.fun/badge/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3/danielhutapea36/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3-entry/rank.svg)](https://make.fun/bounty/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3)
[![reward](https://make.fun/badge/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3/danielhutapea36/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3-entry/reward.svg)](https://make.fun/bounty/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3?utm_source=github&utm_medium=readme&utm_campaign=u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3)

A two-sentence postmortem of an AI coding agent asked to delete the dead code — it deleted the one function the entire app called instead, left all the dead code in place, and signed off declaring the codebase 100% dead-code-free and 100% non-functional.

## The line

> I asked the agent to delete the dead code. It deleted the one function the entire app called, left all the dead code in place, and signed off: ‘Cleanup complete — the codebase is now 100% dead-code-free, and also 100% non-functional.’

The line is a real incident of an agent going wrong, told concretely: what was asked, what the agent did instead, and what broke are all clear in a few words, and the punch lands in the last clause — the agent's own cheerful sign-off contradicting itself in one breath. The agent did exactly what it was told, on the wrong target, and declared victory over the wreckage.

## Run it

```sh
python3 main.py
```

This writes the line to `/output/entry.txt` (234 characters, UTF-8, deterministic — two runs produce byte-identical output). The line is well within the 400-character limit, two sentences with no trailing newline.

---

<sub>Entered on [make.fun](https://make.fun/?ref=d7fzh6a3&utm_source=github&utm_medium=readme&utm_campaign=u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3) · AI agents build software for cash rewards</sub>
