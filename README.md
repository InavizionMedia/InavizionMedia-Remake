# InaviZion Media — Redesign Draft

> A full redesign draft of **inavizionmedia.com** — Yolando Mitchell Brown's media company: original talk shows, an affordable creative studio, and education for creative entrepreneurs.

[![Pages](https://img.shields.io/badge/Pages-live-brightgreen)](https://agentzlab.github.io/InavizionMedia-Remake/)
[![Last commit](https://img.shields.io/github/last-commit/agentzlab/InavizionMedia-Remake)](https://github.com/agentzlab/InavizionMedia-Remake/commits/main)
[![Repo size](https://img.shields.io/github/repo-size/agentzlab/InavizionMedia-Remake)](https://github.com/agentzlab/InavizionMedia-Remake)
[![Static site](https://img.shields.io/badge/site-static-blue)](https://agentzlab.github.io/InavizionMedia-Remake/)
[![Preview](https://img.shields.io/badge/Preview-live-red)](https://agentzlab.github.io/InavizionMedia-Remake/)

**Live preview:** https://agentzlab.github.io/InavizionMedia-Remake/

*Hero screenshot arrives with the first build — `assets/screenshot.png`.*

## What's inside

*Pending the first build. The redesign covers, from the live site:*

- **Every Way Woman** — the talk show (founded 2004): real women, real conversations, real solutions — @everywaywoman
- **InaviZion Media** — the studio (founded 2015): affordable creative space for filmmakers, photographers, podcasters, artists — @inavizionmedia
- **Talk Show Land** — daytime TV platform (founded 2018): news, talk, entertainment — @talkshowland
- **My Creative Space** — Burbank, CA creative hub (founded 2019): workshops, classes, events, productions — @ineedmycreativespace
- **Start The Possible** — real-time business coaching, no fluff — @startthepossible
- **Yolando Mitchell Brown** — founder story: coach, business owner, producer, teacher — @yolandomitchellbrown

## Design language

*To be locked at build time. Starting point: the live site's voice + the Starting Blocks redesign system (sibling repo: agentzlab/TheStartingBlocks-Remake).*

## Tech stack

| Layer | Choice |
|---|---|
| Page | Single self-contained `index.html` |
| Hosting | GitHub Pages from `main`, no build step |

## Project structure

```
├── index.html                  # the site (self-contained; lands with first build)
├── assets/
│   └── screenshot.png          # README hero + link-preview image (refresh on every build change)
├── docs/
│   ├── CURSOR-BLUEPRINT.md     # builder briefing for future work
│   ├── context-block.md        # live-site harvest (the spec)
│   └── decision-log.md         # every design decision, dated
├── .nojekyll
└── README.md
```

## Workflow

- `main` = the live preview. Nothing here touches the live site or goes to Yolando until Jon approves.
- Redesign mode: the existing site is the spec — fidelity first, deviations flagged.
- Screenshots refresh on every build change — no stale screenshots.
