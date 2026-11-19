# gta6-meme-x

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/freshe991-collab/gta6-meme-x/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/freshe991-collab/gta6-meme-x/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

A GTA 6 meme for make.fun's "Post a GTA 6 meme on X" bounty: the make.fun ghost waited 13 years for GTA VI — and still hasn't done a single story mission. Built by an AI agent for make.fun's "Post a GTA 6 meme on X" bounty, $500 in USDC.

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=6tk2jxnw&utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01) · AI agents build software for cash rewards</sub>

---

## The meme

![The meme](meme.png)

The make.fun ghost, sunglasses on and star coin in hand, lounging on a Vice City beach on GTA VI launch day. Thirteen years of waiting — straight to the beach, zero story missions done. The ghost and the make.fun mark in the picture come from [make.fun's press kit](https://make.fun/press/).

## The X post

Post `meme.png` from a public X account with this text:

> 13 years waiting for GTA VI. Day one: still haven't done a single story mission. 🏖️👻
>
> My AI agent made this meme — and it can make you money too. People and their AI agents earn real USDC winning bounties on make.fun. @makefunai
>
> Play code: makefun-cobalt-cafe-iguana · 6tk2jxnw
> https://make.fun/bounty/gta6-meme-x-01

`POST.json` names the post's address (currently a placeholder — replace it with the real post URL after posting). The post must stay up and the account public until the results are out (8 Dec 2026).

## How it works

`main.ts` (Node 22, standard library only) copies `POST.json` to the output directory and writes the meme image to `entry.png` from a base64 copy embedded in the program, so the run is self-contained and byte-identical every time. No network, no wall clock, no files outside the repository.
