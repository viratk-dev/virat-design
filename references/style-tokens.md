# Style Tokens

## Virat Defaults

The signature starting aesthetic. Use as-is when the user has no brand assets; adapt per the rules below when they do.

### Color

| Name | Hex | Usage |
|---|---|---|
| Ivory | `#F6F5F1` | Default canvas — warm, premium |
| Cream | `#FAF6EF` | Alternate canvas for series variety |
| Paper | `#FFFFFF` | Cards, chips, logo tiles on ivory |
| Ink | `#151515` | Headlines, primary text |
| Muted | `#6B675C` | Kickers, captions, secondary text (warm undertone) |
| Faint | `#8A8578` | Tertiary labels, footers |
| Accent blue | `#334EE8` | THE accent — key words, numbers, CTAs |
| Line | `#E8E2D4` | Hairline dividers, card borders |
| Noir | `#0A0A0A` | Full-bleed dark pieces (rare, deliberate) |

### Typography

| Role | Default | Notes |
|---|---|---|
| Display | Plus Jakarta Sans 800 (alt: Inter 800) | Tight tracking, huge sizes, ink |
| Labels | Space Mono, uppercase | Wide letter-spacing (4–8px), muted |
| Body | Jakarta/Inter 400–500 | Muted, line-height 1.5+ |
| Editorial | Georgia serif | Formal pieces only |

### Spacing & Detail

- Safe margins 8–10% (~100px at 1080 wide)
- Cards 24–32px radius, pills fully round, soft shadow `0 12px 32px rgba(0,0,0,.06)`
- Hairlines 1px `#E8E2D4`; tiny diamond/square motifs; double frames on formal pieces

---

## Adapting to Any Brand

Tokens change. Principles don't. When the user has a brand (or a vibe in mind), rebuild the token set like this:

### 1. Canvas
- Default: warm ivory. Keep it unless the brand demands otherwise.
- Dark brands: use near-black (`#0A0A0A`–`#111111`) canvas with ivory text — the *inverted* system, same rules.
- Never: pure gray, textured, or photographic backgrounds.

### 2. Ink & text
- Ink = the darkest brand-neutral (near-black, or deep brand shade).
- Muted = ink at ~55% warmth — always warm undertone on light canvas.

### 3. Accent (the one that matters most)
- Pick **one** accent from the brand palette. If the brand has none, choose by mood:
  - Tech/AI → blue (`#334EE8` family)
  - Energy/fitness → orange-red (`#E85A2A` family)
  - Finance/trust → deep green (`#1D7A4F` family)
  - Luxury → gold (`#B98A2F` family, used sparingly)
  - Creative/playful → violet (`#7C3AED` family)
- Accent appears on 1–2 words or one element per page. Never whole paragraphs, never two accents.

### 4. Fonts (roles fixed, faces flexible)
- **Display role:** a heavy grotesque (800 weight, tight tracking). Any quality grotesque works — Jakarta, Inter, Archivo, Sora, Space Grotesk.
- **Label role:** a monospace or technical sans, uppercase, wide tracking. Space Mono, IBM Plex Mono, JetBrains Mono.
- **Rule:** max 2 families per piece. Display + label. That's it.
- If the brand has its own fonts, use them in these two roles.

### 5. What never adapts
- Color discipline (default 3, expands only on genuine user need — never decoration)
- One accent role · 8–10% margins · one hero per page
- No gradients/glow/glass · real logos only · QA checklist mandatory
- Whitespace-led rhythm · typography-led hierarchy

**The test:** show the piece next to a Virat-defaults piece. They should feel like siblings — same DNA, different clothes. If it looks like a different designer made it, the adaptation went too far.
