# Zingo — Build Brief

A self-contained brief for implementing the Zingo marketing site (homepage and packs pages). All copy below is final unless flagged. Visual design is intentionally not specified — see "What is yours to decide."

---

## Context

Zingo is a brand for beginning band education (wind and brass students). The mobile app is still in development, so this site's job right now is to establish the brand and put free, ready-to-use resources in front of band directors. The site is **director-first**: the primary visitor is a school band director, not a parent or student.

## Goal

Make a director trust Zingo and walk away with something useful (a free download) or on a waitlist. Two outcomes: free downloads grabbed, and school-program waitlist signups.

## Voice (copy only, not a visual instruction)

Direct, clear, and interest-generating. Confident but not cocky. Anti-traditional: Zingo is the energetic alternative to dry, dated method books. The brand has a proud, affectionate "band nerd" identity. Keep copy in sentence case and plain-spoken.

---

## Scope

1. Homepage
2. Packs page (index) and the pages beneath it (series pages and pack pages)

---

## Homepage

Sections, top to bottom. Copy in quotes is final.

1. **Hero**
   - Headline: "Up to 55% of beginning band students quit in their first year, but we're on a mission to change that."
   - Primary action: "Browse free downloads" (links to the Packs page). No audience fork; the page is director-first.

2. **Value**
   - "We tossed out the tired old method books and made learning an instrument exciting again."
   - Payoff line: "Creating a whole new generation of band nerds."

3. **Credibility**
   - "Real educators. Expert musicians."
   - "Built by Juilliard-trained musicians and educators."

4. **Whole-band resource**
   - "A trusted resource for your entire band."
   - "Every section. Every level."

5. **Free downloads (teaser for the Packs page)**
   - Heading: "Free downloads for your students."
   - Optional sub: "Ready-to-run practice you can hand them this week."
   - Body: the two series shown side by side — Practice Club and Folk Songs — plus a "Browse all packs" link to the Packs page. This is a curated preview, not the full list.

6. **App**
   - A small "coming soon" placeholder. Minimal; the app is not yet available.

7. **School waitlist**
   - A short section signaling a larger offering for whole programs is coming, with an email waitlist signup. No product details, no pricing.

8. **Footer**

---

## Packs

### Packs page (its own page, reachable from the nav)

A shelf of series. Two exist today: **Practice Club** and **Folk Songs**. The page is built to grow by **adding more series over time** (each new series is a new entry). Keep it a short, scannable shelf. No filters or search. A newest or featured series may be highlighted.

### Navigation logic (drill-down)

`Packs page → (series page, only if that series has more than one pack) → pack page`

- A series with multiple packs gets a middle "series page" that lists its packs.
- A series with a single pack skips the middle page and goes straight to that pack.
- This rule self-adjusts: if a single-pack series later gains a second pack, the entry simply starts leading to a list instead of straight to the pack. From the visitor's side every series entry looks the same; some just have one more step behind them.

Applied today:
- **Practice Club** has multiple pieces and grows over time, so it has a series page listing the pieces. Order newest first, with a featured "this month" slot.
- **Folk Songs** is a single compilation, so its entry goes straight to the pack page (no series page).

### Pack pages

Two pack types. Both share the same top and bottom (a hero with the pack name and a one-line description, and a download block); their middles differ.

**Practice Club pack** (a full practice session built around one central piece):
- Hero: the piece name and a one-line promise.
- What the piece teaches: the specific technique areas it develops.
- The structured practice: a four-part session arc built from the piece — warmup, technique, the piece, cooldown.
- What's inside: the graded arrangement, a warmup sheet, a practice plan, a play-along track.
- Download block (see below).

**Folk Songs pack** (a compilation / songbook of many tunes):
- Hero: the compilation name and a one-line promise.
- The tune list: the songs included with their levels, presented like a tracklist. This list is the main body.
- Download block (see below).

### Download behavior (all pack pages)

- Primary action: **Download all** (the full pack in one download).
- Secondary: **individual per-instrument** downloads.
- Make the download reachable near the top and repeat it at the end of the page.

---

## Functionality

- Email waitlist signup (homepage school section).
- File downloads: a combined "download all" plus individual per-instrument files.
- Drill-down navigation across Packs → series page → pack page.
- Structure that scales as new series and packs are added without redesign.

---

## Content accuracy notes (important)

- **The 55% figure** is commonly cited but loosely sourced. Back it with a verifiable citation before launch, or soften to "more than half."
- **Institutional names** (Juilliard, New York Philharmonic, Carnegie Hall) must appear strictly as the founders' personal background. Never imply endorsement, sponsorship, or partnership by these institutions.
- **"Entire band / every section"** is the aspiration. Current instrument coverage is limited (trombone and trumpet today, more in development), so pack and coverage content should stay honest about what is actually available, with more on the way.

---

## What is yours to decide

All visual design: color, typography, layout, spacing, imagery, illustration, motion, and overall look and feel. No palette, font, or stylistic direction is being prescribed. Interpret the brand voice and content above and make the visual choices.
