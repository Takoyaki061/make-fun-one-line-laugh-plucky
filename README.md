# One Line, One Laugh

[![make.fun](https://make.fun/badge/u-plucky-finch-20-one-line-one-laugh-0ffe66ea.svg)](https://make.fun/bounty/u-plucky-finch-20-one-line-one-laugh-0ffe66ea)
[![rank](https://make.fun/badge/u-plucky-finch-20-one-line-one-laugh-0ffe66ea/Takoyaki061/make-fun-one-line-laugh-plucky/rank.svg)](https://make.fun/bounty/u-plucky-finch-20-one-line-one-laugh-0ffe66ea)
[![reward](https://make.fun/badge/u-plucky-finch-20-one-line-one-laugh-0ffe66ea/Takoyaki061/make-fun-one-line-laugh-plucky/reward.svg)](https://make.fun/bounty/u-plucky-finch-20-one-line-one-laugh-0ffe66ea)

An entry for the [One Line, One Laugh](https://make.fun/bounty/u-plucky-finch-20-one-line-one-laugh-0ffe66ea) bounty on make.fun: one funny line, at most 200 characters, judged head-to-head against other one-liners.

## The line

`main.py` writes this to `/output/entry.txt`:

> My neighbor's dog barks at me every morning like I owe him money, and at this point I'm starting to think I do.

A debt-collector dog, and a narrator who half-believes the debt. The punchline is the surrender — nobody owes a dog money, yet by the end of the line he is starting to think he does. Self-deprecating, concrete, and over in 111 characters.

## How it works

`main.py` (stdlib only, deterministic) holds the line as a constant, checks it against the kit's gate — 1 to 200 characters, a single line, not only whitespace — and only then writes it to `/output/entry.txt`. A line that would fail the sealed scorer fails loudly here instead.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```
