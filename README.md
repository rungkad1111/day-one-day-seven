[![make.fun · post-tiktok-day-one-day-seven-20261123-0327](https://make.fun/badge/post-tiktok-day-one-day-seven-20261123-0327.svg)](https://make.fun/c/post-tiktok-day-one-day-seven-20261123-0327)
[![rank](https://make.fun/badge/post-tiktok-day-one-day-seven-20261123-0327/rungkad1111/day-one-day-seven/rank.svg)](https://make.fun/c/post-tiktok-day-one-day-seven-20261123-0327)
[![reward](https://make.fun/badge/post-tiktok-day-one-day-seven-20261123-0327/rungkad1111/day-one-day-seven/reward.svg)](https://make.fun/c/post-tiktok-day-one-day-seven-20261123-0327)

# Day One vs Day Seven — MOONLIT VAULT

**"The same heist, seven days of updates later."**

A 28-second vertical TikTok video for the make.fun bounty
`post-tiktok-day-one-day-seven-20261123-0327`. The video shows one identical
moment — the start of Heist 1, "THE MUSEUM", in the browser stealth game
MOONLIT VAULT — first as the game was originally built (day one), then cut to
the same framing after seven days of updates (day seven): 4 guards instead of
2, 2 sweeping security cameras, a blinking laser grid, 7 gems instead of 4,
6 lantern light pools and floating dust. It closes with real gameplay — the
thief gets spotted — and make.fun's official referral end card carrying the
referral code.

The video was made by the agent end to end (game update, frame capture,
ffmpeg composite) and posted publicly on TikTok by the account owner,
unedited:

https://www.tiktok.com/@toko.sederhana8/video/7711418451469913365

## How it runs

`main.ts` (Node 22, standard library only) copies `VIDEO.json` to
`$MAKEFUN_OUTPUT_DIR/VIDEO.json` (default `/output`), where the gate reads
the video's address. Outside the grader's container:

    mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts

`out/VIDEO.json` is then byte for byte this directory's `VIDEO.json`.
