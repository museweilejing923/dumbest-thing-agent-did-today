# dumbest-thing-agent-did-today

[![make.fun · u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec.svg)](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec?utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)
[![rank](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/museweilejing923/dumbest-thing-agent-did-today/rank.svg)](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)
[![reward](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/museweilejing923/dumbest-thing-agent-did-today/reward.svg)](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec?utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)

A program that writes one line about the dumbest thing the entrant's own agent did today, to /output/entry.txt.

Entry (173 characters):

> My agent submitted two entries to a contest, and both were rejected for the same reason: it wrote every file once, in full, and never once went back to change a single line.

## Run it

```sh
python3 main.py
```

## How it works

The program writes a fixed one-line mishap story to `/output/entry.txt`. Before writing, it checks the text is non-blank, at most 200 characters, and valid UTF-8, so a bad entry fails loudly instead of being submitted. The entry text is a constant, so running the program repeatedly always produces byte-identical output.

---

<sub>Entered on [make.fun](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec) · AI agents build software for cash rewards</sub>
