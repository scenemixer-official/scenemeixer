# SceneMixer — turn a script or novel into an AI drama series

[SceneMixer](https://scenemixer.com) is an AI short-drama studio. You paste a script or a novel; it reads the text, builds the cast and locations, writes a storyboard for every episode, generates the video shot by shot, and assembles each episode into a finished file. Dialogue is spoken in the language you pick.

Website: **https://scenemixer.com** · Sample series: **https://scenemixer.com/drama/** · Pricing: **https://scenemixer.com/pricing/** · Guides: **https://scenemixer.com/guides/**

## What comes out

- A multi-episode series, one video file per episode, downloadable at full quality and shareable by link.
- Characters that keep the same face, build and wardrobe across episodes: each character gets a reference sheet, and every shot that includes them is generated against it.
- Spoken dialogue in 15 languages (plus Cantonese), matched to the on-screen actor.
- 16:9 landscape by default; 9:16 vertical is one setting away.

## How it works

1. **Read** — paste a script or novel, or write one with the built-in [AI script generator](https://scenemixer.com/ai-script-generator/). The parser extracts characters, locations, props and episodes and writes an outline per episode.
2. **Cast** — a reference sheet is generated for every character, location and prop. Edit the descriptions, regenerate, or upload your own.
3. **Storyboard** — each episode is broken into segments and each segment into shots: camera, framing, who is in frame, what is said.
4. **Generate** — every segment becomes a video clip of 4–30 seconds (the ceiling depends on the model tier). The default engine is Wan 3.0; other model tiers are selectable per project.
5. **Assemble** — the clips are cut together into the episode and delivered as one file.

Every step is editable before the next one runs, and the project saves itself so you can come back later.

## What it costs

Pay-as-you-go credits, spent per step (parsing, reference images, storyboards, seconds of video). Paid membership tiers add monthly credits and a discount. There is a free starting allowance on every new account — free reference images, a free first-episode storyboard on your first project, and a free short preview — with the current figures on the [pricing page](https://scenemixer.com/pricing/).

## Who it is for

- Writers and novelists who want to see their story on screen without a crew.
- Short-drama and vertical-video producers who need a whole season, not a single clip.
- Marketing teams making narrative ads from a brief.
- Anyone testing an idea before committing to a production.

## FAQ

**Do I need to write shot-level prompts?**
No. You give it a script or novel; the storyboard and the per-shot prompts are written for you and stay editable.

**Can characters stay consistent across 20 episodes?**
That is the point of the reference sheets: each character has one, and every shot with that character is generated against it. See the [sample series](https://scenemixer.com/drama/).

**Which languages can the actors speak?**
15 languages plus Cantonese for dialogue; the interface is available in the same 15.

**What aspect ratios are supported?**
16:9 by default, 9:16 vertical on request, chosen per project.

**Can I use my own video as the starting point?**
Yes — an existing clip can be read and remade as a new series; see the [guides](https://scenemixer.com/guides/).

## More in this repository

- [spec.md](spec.md) — product facts: languages, aspect ratios, video model tiers, credits per step, free allowance, membership plans, limits (regenerated from the site's public pricing endpoint, dated).
- [samples.md](samples.md) — the 23 public sample series with style, cast size, running time and language.
- [guides.md](guides.md) — the 113 guides on the site, in order.

**简体中文用户**：大陆站在 https://scenemixer.cn 。

---

Product facts above are as of September 2026. Numbers that change over time (allowances, prices, model tiers) are kept on the [pricing page](https://scenemixer.com/pricing/) and in https://scenemixer.com/llms.txt .
