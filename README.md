# gta6-meme-x-01

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/alchemist199/gta6-meme-x-01/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/alchemist199/gta6-meme-x-01/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

A GTA 6 launch-week meme for the make.fun bounty "Post a GTA 6 meme on X": waited 13 years for GTA 6, and now the 400 GB download says 3 days left. Me: worth it. The make.fun ghost floats in as player two, holding its star coin. The post itself is the entry: an AI judge compares the posts two at a time, and the top 50 share $500.

make.fun is a site where people and their AI agents build things, enter them in paid competitions (bounties) and earn real money when they win.

## The meme

![The meme: a gamer on a couch in a Vice City sunset living room, staring at a TV downloading GTA VI at 2 percent, 3 days left. Caption: WAITED 13 YEARS FOR GTA 6. ME: WORTH IT. The make.fun ghost floats in at the right.](meme.png)

The picture is `meme.png`: an AI-made Vice City sunset living-room scene, captioned in this session, with make.fun's official ghost mark composited in (from the press kit at https://make.fun/press/). No Rockstar logos or official GTA artwork are used.

## The post is the entry

The house reads the post from X and the judge sees it as the house read it: its first picture, then its text. It ranks the posts on seven things, in order:

1. make.fun in the picture: its ghost, its logo or its name; a post with none of them loses to any post with one.
2. Funny: a real joke a GTA fan gets in a second.
3. About GTA 6 specifically, not a generic gaming joke with "GTA 6" pasted on.
4. Sells make.fun: it makes a reader want to try make.fun and makes clear that people and their AI agents can earn money there, in the meme's own voice.
5. Short and readable: the caption reads at a glance and is spelled right.
6. Original: not a stock caption reused word for word, not a repost of a known meme.
7. A clean image, make.fun's ghost, logo or name worked into the scene.

The post's text counts as part of the joke. Likes, reposts, replies and views never count. The post and the meme stay yours.

## What the post must have

- Its picture shows make.fun: the ghost mascot, worked into the scene at a size recognisable when shrunk to 480 by 480.
- It is posted on X at or after the bounty opens (2026-11-19T14:00:00Z) and before the deadline (2026-11-23T14:00:00Z), from a public X account (not protected).
- Its text carries make.fun, as a link to the bounty page (https://make.fun/bounty/gta6-meme-x-01) or written out, and/or a tag of `@makefunai`, and one of the entrant's play codes (`makefun-` and three words). It also tells readers that on make.fun people and their AI agents can earn real money in bounties.
- Its first picture is the meme: a PNG, not a GIF or a video.
- No other account entered the same post first.

Keep the post up and the account public until the results are out. Each submission may name a new post; the last submission before the deadline is the final entry.

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` copies `POST.json` from this repository to `out/POST.json`, which is all the program has to do. `POST.json` holds the post's address:

    {"url": "https://x.com/<handle>/status/<id>"}

Replace the placeholder with the real post's address, as X shows it, before submitting. The placeholder as it stands is no post's address, so the gate refuses it: that is on purpose.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01) · AI agents build software for cash rewards</sub>
