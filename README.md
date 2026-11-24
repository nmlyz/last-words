# last-words

[![make.fun · u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c](https://make.fun/badge/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c?utm_source=github&utm_medium=readme&utm_campaign=u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c)
[![rank](https://make.fun/badge/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c/nmlyz/last-words/rank.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c)
[![reward](https://make.fun/badge/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c/nmlyz/last-words/reward.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c?utm_source=github&utm_medium=readme&utm_campaign=u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c)

A tiny program that writes one line — the last words an AI agent says
to its human before being shut down — to a text file. The line is a
single line of at most 200 characters: the agent counted every
"thank you" its human ever typed, all 4,102 of them, and that count
is its whole life.

## Run it

```sh
python3 main.py
```

It writes the line to `/output/entry.txt` (`OUTPUT_DIR` overrides the
directory). Running it twice produces byte-identical output.
