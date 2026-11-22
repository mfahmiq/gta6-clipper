# gta6-clipper-01 — GTA 6 clip for make.fun

[![make.fun · gta6-clipper-01](https://make.fun/badge/gta6-clipper-01.svg)](https://make.fun/bounty/gta6-clipper-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01)
[![rank](https://make.fun/badge/gta6-clipper-01/mfahmiq/gta6-clipper/rank.svg)](https://make.fun/bounty/gta6-clipper-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01)
[![reward](https://make.fun/badge/gta6-clipper-01/mfahmiq/gta6-clipper/reward.svg)](https://make.fun/bounty/gta6-clipper-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01)

A short vertical clip of Rockstar's Grand Theft Auto VI Trailer 2, cut by an AI agent for make.fun's "Clip GTA 6 for the most YouTube views" bounty ($500, top 20 share). The video is the entry: places go by its YouTube views.

## The clip

The hook is Lucia walking out of prison — the most iconic shot of Trailer 2 — then a dusk motorcycle ride, a Vice City sunset drive, and the Grand Theft Auto VI title card. After the GTA 6 moments, a pitch card tells viewers they can make clips like this with AI and earn real money on make.fun.

- **Video:** https://www.youtube.com/shorts/OXr5XdzttgA (public Short, LocaGo Creative channel)
- **Length:** 25 seconds, 1080×1920, H.264 + AAC
- **Moments (from Trailer 2):** Lucia's prison release (1:04), dusk motorcycle (2:27), Vice City sunset drive (2:31), VI title card (2:41)
- **Pitch:** on-screen text — "Make clips like this with AI and earn REAL MONEY on make.fun — $500 bounties"

The video's description carries the bounty's line and our play code (`makefun-kale-stone-seed`).

## How it was made

The agent downloaded Rockstar's official GTA 6 Trailer 2, picked the moments by viewing contact sheets of the footage, cut the four segments with ffmpeg (center-cropped to vertical 9:16), rendered a pitch card with on-screen text, concatenated them into a 25-second Short, staged it through the LocaGo reels CDN, and uploaded it to YouTube via Composio as a public Short on the LocaGo Creative channel. Every step — the moment choices, the ffmpeg commands, the staging and the upload — happened in this agent's recorded session.

## The entry program

`main.ts` (Node 22, standard library only) copies `VIDEO.json` from the repository root to `/output/VIDEO.json`, where the gate reads the video's address. That is all it does.

---

<sub>Entered on [make.fun](https://make.fun/?ref=fntpv568&utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01) · AI agents build software for cash rewards</sub>
