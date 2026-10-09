# Atheos Studios — Site Guide

Read the master workspace guide first: [`..\CLAUDE.md`](../CLAUDE.md). It covers the
shared build recipe (Astro + GitHub Pages), the publish steps, and the domain-freeing
plan. This file only covers what's specific to Atheos Studios.

- **Domain:** atheosstudios.com — served by GitHub Pages (through Cloudflare).
- **What it is:** Josh's independent video game studio.
- **Must-have:** a prominent link out to the studio's first game, **Grave Error**
  (graveerrorgame.com — see the `Website-Grave Error` folder).

## Positioning & voice

Bold, confident indie studio. The name "Atheos" reads cosmic / defiant / mythic —
lean into a striking, cinematic, slightly dark modern look. Voice: assured, a little
mysterious, human — **not** corporate.

## Selected design & locked decisions

- **Design: "Nyx"** (picked 2026-10-09 from four options in `design-options/redesign/`; replaced the
  2025 "Monolith" build). Dark: paper type on ink, plus a deeper ink `#1E2228`. A slowly turning
  Antikythera-style star dial behind the hero, a star field, and each game drawn as a constellation
  (its emblem plus stars). Greek touches: Γ Ε Η and Α Β Γ, Roman numerals. Sections: hero, In the
  Works (games), Studio, footer.
- **Brand kit** (unchanged): `brand-kit/`; slate `#2A2E34`, paper `#FBFAF7`, ink `#262B33`;
  **Marcellus** (single weight, never bold it) + **Jost**. The laurel lockup and the three game emblems
  are SVG symbols in `src/components/Sprite.astro`, recolored with `currentColor`.
- **Three games.** Copy lives in the `games` array at the top of `src/pages/index.astro`. Ground every
  claim in the game's own docs; don't invent lore.
  - **Grave Error** (`C:\Projects\Grave Error\LORE.md`, `docs\vision.md`): 3D first-person zombie
    survival, solo or co-op, PC, "Coming eventually". The risen are "Hacks"; the player is a "Null";
    HACK program, Core Update 3.0. Never say top-down/2D, Unity, Early Access, Steam/wishlist, or a
    date. Links to graveerrorgame.com. The tagline "You don't beat this world. You outlast it." is Josh's.
  - **Elderdeep** (`C:\Projects\Elderdeep\README.md`, `LORE.md`, esp. its Register section: plain, dry,
    nothing grand; no gods/temples, quests, chosen ones, ancient evils, kings). 2D dig-and-build
    platformer, "In development". Don't link its private tracker.
  - **Holdout** (`C:\Projects\Tower Defense Game\docs\vision.md`): Josh calls it "Holdout (working
    title)"; its docs call Holdout the code name. Top-down survival tower defense, rural America, its
    own world (not Grave Error's). "Early prototype": community, towers and co-op are planned, not built.
- **Voice:** plain, specific, a little wry ("Games made the long way.", "Coming eventually"). Avoid
  AI-sounding copy: stacked long dashes, rule-of-three lists, slogan filler. Neutral brand "we";
  **never imply a team and never say solo**. **No dates anywhere.** No contact/email/social section
  (Josh removed it).

**Status:** Nyx is live at atheosstudios.com (GitHub Pages behind Cloudflare; shipped 2026-10-09). Push to
`main` = deploy.
