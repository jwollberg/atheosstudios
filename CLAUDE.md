# Atheos Studios — Site Guide

Read the master workspace guide first: [`..\CLAUDE.md`](../CLAUDE.md). It covers the
shared build recipe (Astro + GitHub Pages), the publish steps, and the domain-freeing
plan. This file only covers what's specific to Atheos Studios.

- **Domain:** atheosstudios.com — *currently on Google Sites; must be freed first
  (see master guide).*
- **What it is:** Josh's independent video game studio.
- **Must-have:** a prominent link out to the studio's first game, **Grave Error**
  (graveerrorgame.com — see the `Website-Grave Error` folder).

## Positioning & voice

Bold, confident indie studio. The name "Atheos" reads cosmic / defiant / mythic —
lean into a striking, cinematic, slightly dark modern look. Voice: assured, a little
mysterious, human — **not** corporate.

## Likely pages / sections

- **Hero** — studio name/logo, one-line mission, primary button → Grave Error.
- **Games** — a featured card for *Grave Error* (key art, tagline, "Learn more" →
  graveerrorgame.com), with room for future titles.
- **About the studio** — short story / mission, who's behind it.
- **Follow / contact** — social links + email; business & press inquiries.
- *(Later)* News / devlog.

## Selected design & locked decisions

- **Design: Option B — "Monolith"** (bold editorial / brutalist: huge type, strong grid,
  full-bleed rules). Permanent Atheos design; built as the real Astro + Tailwind site.
  The mockup's red accent was dropped when the brand kit arrived — the site is now
  **monochrome**: slate/ink blocks on paper. Mockups remain in `design-options/`.
- **Brand kit (applied):** lives in `brand-kit/` at the repo root; served files
  (favicon + logo) are copied into `public/brand-kit/`. Palette: **accent slate
  `#2A2E34`**, paper `#FBFAF7` (backgrounds), ink `#262B33` (text/borders). Fonts:
  **Marcellus** for headings/display (single weight — never bold it) + **Jost** for body
  and the tracked-caps labels. Full laurel lockup (`logo.png`) sits top-left in the header.
- **Copy is grounded in the real game.** Grave Error facts come from
  https://www.atheosstudios.com/grave-error plus Josh's corrections — **3D** zombie
  survival (Josh: "now a 3D project, same feature set/systems" — the old site page
  says top-down 2D; don't reintroduce "top-down"), HACK-nanobot premise (player is a
  "Null"), **single-player AND multiplayer**, **PC only** (no console), philosophy
  "realism first." **No dates on the site** — Josh replaced "Coming soon / Summer
  2026" with **"Coming eventually"** (used in the ticker, key-art chip, and status
  cell). Don't reinvent lore; re-derive from that page (or Josh) when updating.
- **Josh removed from the mockup:** the "Play Grave Error" button (game isn't out —
  CTAs say "Grave Error →"/"Learn more"), the ticker phrases "NO GODS, NO SAVES" and
  "SURVIVE THE NIGHT" (and the matching footer line), the placeholder game slots
  ("Project II" / "Reserved Slot"), the social-links grid, the pull quote "We build
  the dark…", and the **entire Contact section** — the site intentionally shows no
  email/contact at all. Sections are just: hero, Games, Studio.
- **Voice guardrail:** same as the other sites — neutral brand "we"; **never imply a
  team** ("small team", "crew") **and never say solo**. The old "Small Team. Long
  Nights." headline was replaced for this reason.

**Status:** built; repo + GitHub Pages live. Domain still on Google Sites — must be
freed and repointed before this site serves at atheosstudios.com (see master guide).
