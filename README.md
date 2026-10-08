# virat-design

![MIT License](https://img.shields.io/badge/license-MIT-green)
![Version](https://img.shields.io/badge/version-3.0.0-blue)
![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)

An AI-agent skill for **world-class graphic design** — a full end-to-end methodology for premium minimal visuals.

Give this skill to your AI agent, and it designs like a professional design studio: social posts, carousels, **presentations (PPT/slide decks)**, posters, thumbnails, banners, ad creatives, infographics, covers.

**Fixed principles, flexible tokens.** The skill teaches the design system — restraint, whitespace, typography-led hierarchy, human-made quality — and adapts every color and font to *your* brand.

## What it creates

One methodology, every format — social posts, carousels, full slide decks, posters, thumbnails, banners, ad creatives, infographics. Open any file in `preview/` in a browser to see it in action:

- `preview/sample-post.html` — Instagram post, default aesthetic (warm ivory, ink, royal blue)
- `preview/sample-adapted.html` — same system on a different brand (dark, orange accent)
- `preview/sample-slides.html` — three 1920×1080 slide designs (title, content, stat)

## Install

**One command — direct connect:**
```bash
git clone https://github.com/viratk-dev/virat-design ~/.claude/skills/virat-design
```
Works with any AI agent that supports skills — just point it to your agent's skills folder (common locations: `~/.claude/skills/`, `~/workspace/skills/`). Restart your agent and the skill is live.

**No terminal? Just say it:**
> "Install this skill: https://github.com/viratk-dev/virat-design"

**Or download ZIP:**
1. Open [github.com/viratk-dev/virat-design](https://github.com/viratk-dev/virat-design)
2. Green `<> Code` button → `Download ZIP` → unzip → point your agent to the folder

No API keys. No config. Then just describe what you want designed:

- *"Make an Instagram carousel about 5 AI tools for students"*
- *"Design a 10-slide pitch deck for my startup, dark theme, green accent"*
- *"Review this poster and tell me what breaks the design rules"*

## How it works

The skill runs an 8-stage process on every piece — **Brief → Research → Direction → Tokens → Compose → Build → QA → Deliver** — the way a world-class designer works.

**Non-negotiables:** color discipline · typography-led hierarchy · one hero per page · 8–10% safe margins · zero gradients/glow/glass · real logos only · nothing ships without QA.

**Flexible:** every color and font adapts to your brand. Defaults (warm ivory `#F6F5F1`, ink `#151515`, royal blue `#334EE8`, Jakarta 800 + Space Mono) apply only when you bring no brand assets.

## What's inside

```
virat-design/
├── SKILL.md                  # philosophy, scope, workflow, principles
├── references/
│   ├── style-tokens.md       # default tokens + brand-adaptation guide
│   ├── process.md            # the 8-stage end-to-end process
│   ├── patterns.md           # 6 layout patterns + formal variant
│   ├── instagram.md          # post / carousel / story specs
│   ├── presentations.md      # slide decks: structure, slide types, rules
│   ├── formats.md            # posters, thumbnails, banners, ads, infographics
│   └── qa-checklist.md       # mandatory pre-delivery quality gates
├── preview/                  # sample outputs (open the .html files in a browser)
├── README.md
└── LICENSE
```

## License

MIT — use it anywhere, for anything.
