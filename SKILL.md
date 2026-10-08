---
name: virat-design
description: "World-class graphic design skill: full end-to-end methodology for premium minimal design — social posts, carousels, presentations (PPT/slide decks), posters, thumbnails, banners, ad creatives, infographics, covers. Fixed design principles with fully adaptable tokens — colors and fonts adjust to the user's brand. Use when creating, art-directing, or reviewing any visual design."
version: "3.1.0"
license: "MIT"
---

# virat-design

A complete design methodology for premium minimal visuals — the way a world-class designer works, end to end. **Principles are fixed. Tokens are flexible.** Ships with a default aesthetic ("Virat defaults"); every color and font adapts to the user's brand without breaking the style's DNA.

## The Non-Negotiables

These never change, no matter whose brand it's for:

1. **Restraint is the luxury.** Default to few colors — the exact count follows the user's need, never decoration for its own sake. If in doubt, remove.
2. **Typography leads.** Max 2 font families. Headlines do the heavy lifting — no decorative clutter.
3. **One hero per page.** A single headline, number, or visual owns the composition.
4. **Whitespace is structure.** Minimum 8–10% safe margins; generous vertical rhythm.
5. **One accent role.** A single accent color, used sparingly — on key words or one element, not whole paragraphs.
6. **Human-made, always.** No gradients, no glow, no glassmorphism, no neon, no generic AI-template look.
7. **Real assets only.** Official logos, never faked or recolored. No AI faces as heroes.
8. **Nothing ships without QA.** Run the checklist at the end of this file. Fix everything.

## Scope

| Format | Key specs |
|---|---|
| Social posts / carousels / stories | 1080×1350 post, 1080×1080 square, 1080×1920 story; 100px safe margins |
| Presentations / slide decks | 1920×1080; title → sections → closer; one idea per slide; ~30 words max per slide |
| Posters / flyers | Hero-led, 10%+ margins, info order: what → when/where → action |
| YouTube thumbnails | 1280×720; ≤3 words, huge type, one focal point, readable at 120px wide |
| Banners | LinkedIn 1584×396, X 1500×500, YouTube 2560×1440 (safe 1546×423); keep content in safe zone |
| Ad creatives | 1080×1080 / 1080×1920; hook ≤5 words readable in 1 second; single CTA pill |
| Infographics | One numbered flow, consistent icon style, max 5–7 data points, sources in small mono |
| Covers / certificates / invitations | Double frame, serif headlines, diamond motifs, structured info boxes, proper signing space |

## End-to-End Workflow

**1. Brief.** Extract only what changes the design: the one message (one sentence), audience + placement, format/size, brand assets (logo, colors, fonts — if none, use defaults and say so). Ask max 2–3 questions; assume the rest. Never stall waiting for answers you can decide.

**2. Research.** Study 3–5 best-in-class references in the category. Note what to borrow and what clichés to avoid. Verify every fact, name, and logo — never guess. Define what this piece does *differently*; if it looks like everything else, the direction is wrong.

**3. Direction.** Write the art direction as one sentence before touching layout: *"[Mood] [format] where [the hero] carries the message, with [accent role]."* For major pieces, explore 2–3 directions and let the user pick. For routine work, pick the strongest and go.

**4. Tokens.** Build the project's token set (below): canvas, ink, accent, muted, line + display font + label font. Write them at the top of your working file.

**5. Compose.** Copy first — headline ≤ 6 words, subline ≤ 2 lines. Pick a layout pattern (below). One idea per page; two ideas = two pages. Give the hero 40%+ of the canvas.

**6. Build.** Reference method: HTML/CSS at exact pixel dimensions, screenshotted to PNG. Type stays as real type — never baked into generated imagery. Official logos in white rounded tiles with soft shadow; no logo → mono text tile, never a fake mark.

**7. QA.** Run the checklist at the end of this file. Read every word twice. Fix everything — "minor" issues don't ship.

**8. Deliver & iterate.** Deliver the file + one line on the design decision behind it. Take feedback without ego: "something different" means genuinely different, never a remix of the rejected direction. Approved work is locked; new explorations become new files.

## Style Tokens

### Virat defaults (starting aesthetic — adapt per below)

- **Canvas:** warm ivory `#F6F5F1` (alt cream `#FAF6EF`, pure white `#FFFFFF`)
- **Ink:** `#151515` near-black · **Muted:** `#6B675C` warm gray · **Faint:** `#8A8578`
- **Accent:** royal blue `#334EE8` — key words, numbers, CTAs
- **Lines:** `#E8E2D4` hairlines · **Noir:** `#0A0A0A` for deliberate dark pieces
- **Display:** Plus Jakarta Sans 800 (alt Inter 800), tight tracking, huge sizes
- **Labels:** Space Mono, uppercase, letter-spacing 4–8px, muted
- **Body:** Jakarta/Inter 400–500, muted, line-height 1.5+ · **Editorial:** Georgia serif (formal only)
- Cards 24–32px radius, pills fully round, soft shadow `0 12px 32px rgba(0,0,0,.06)`; tiny diamond motifs; double frames on formal pieces

### Adapting to any brand

Tokens change. Principles don't.

- **Canvas:** keep warm ivory unless the brand demands otherwise. Dark brands → near-black canvas with ivory text (inverted system, same rules). Never pure gray or textured.
- **Ink & text:** ink = darkest brand-neutral; muted = ink at ~55% warmth.
- **Accent:** pick ONE from the brand palette; if none, choose by mood — tech/AI → blue, energy/fitness → orange-red, finance/trust → deep green, luxury → gold (sparingly), creative → violet. One accent per piece, on 1–2 words or one element.
- **Fonts:** roles fixed, faces flexible. Display role = heavy grotesque 800, tight tracking (Jakarta, Inter, Archivo, Sora, Space Grotesk…). Label role = mono/technical sans, uppercase, wide tracking (Space Mono, IBM Plex Mono, JetBrains Mono…). Max 2 families per piece; use the brand's own fonts in these roles when available.
- **The test:** set the piece next to a defaults piece — siblings, same DNA, different clothes. If it looks like another designer made it, the adaptation went too far.

## Layout Patterns

**Cover.** Mono kicker + year → giant headline (1–2 accent words) → quiet subline → optional logo tiles → `SWIPE →` footer.

**Feature.** Series name + `02 / 07` → logo tile + mono kicker + Jakarta 800 name → hairline → 2–3 line description → feature pills → `BEST FOR ·` mono line → big number + footer.

**Comparison.** Kicker → headline → two-column table (max 5 rows); winner column right, accent header.

**Stat.** Kicker → one enormous number (40%+ of canvas) → one quiet line.

**Quote.** One strong centered line (serif allowed) → mono attribution.

**List.** Kicker + headline → 3–5 numbered items with hairlines, generous padding.

**Formal (certificates/covers/invitations).** Double frame border, centered serif/Jakarta headline, diamond divider, structured info boxes, clear signing space.

**Carousel rule:** all slides share canvas, footer, kicker style, margins. Slide 1 = cover, middle = feature, last = CTA. Number every slide.

**Slide rule:** consistent chrome on every content slide — brand left, slide number right, mono, faint.

## Type Scale

| Context | Headline | Body | Kicker | Footer |
|---|---|---|---|---|
| 1080-wide post | 120–200px | 36–44px | 28–34px | 24–28px |
| 1920-wide slide | 130–180px | 44–56px | 30–36px | 24px |

Minimum readable body at 1080 wide: 32px. Below that, cut words instead of shrinking.

## QA Checklist

- [ ] Safe margins on all edges; one hero per page; deliberate alignment; consistent rhythm
- [ ] Color count intentional (default 3, more only on genuine need); accent on 1–2 elements only
- [ ] No gradients, glow, glassmorphism; grays warm-toned
- [ ] Max 2 font families; headline ≤ 6 words with chosen breaks; kickers uppercase + letterspaced
- [ ] Zero typos — every word read twice; facts, names, logos verified
- [ ] Real official logos only — none stretched, recolored, faked
- [ ] Copy tight; single clear CTA
- [ ] Series: shared canvas/footer/kicker style, correct numbering, `SWIPE →` except last slide
- [ ] Exact pixel dimensions; crisp type; sane file size

## What This Skill Is Not

- Not video editing — static visuals only.
- Not a logo generator — it art-directs layouts; brand marks come from official sources.
- Not a photo editor — it composes designed graphics.
- Not a fixed template — a methodology that adapts to any brand.
