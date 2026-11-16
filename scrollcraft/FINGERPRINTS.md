# Fingerprints

Every site you build with **scroll-craft** gets one row here, appended after it
ships. The registry exists so your next build can prove it is a different page
rather than a re-skin of one you already made.

This file is **yours**. It starts empty on purpose: the gate is about not
repeating *yourself*, so it has nothing to say until you have built something.

The rules and the gate live in the skill's
`references/uniqueness.md`. Short version:

**A new build must differ from EVERY row below on at least 4 of the 6
dimensions.** Four against each row individually, not four on average across the
table. If a planned build fails, change the plan. Never edit a row to make room
for it.

The six dimensions are: **grammar**, **nav treatment**, **hero device**,
**act-sequence shape**, **close pattern**, **signature move**.

Dimension 6 is free, because a signature move is unique by definition. So the
gate really asks for three more out of the remaining five, and a build that
changes only grammar and world will fail it.

---

## The registry

| Build | Grammar | Nav treatment | Hero device | Act-sequence shape | Close pattern | Signature move | World | Port |
|---|---|---|---|---|---|---|---|---|
| saddle-section (2026-11-16) | Sale bill (new: printed farm sale bill; lots, plat, terms, tear-off) | Paper masthead strip with a jumping lot index that marks the current section, plus one CTA | Masthead type on paper over a framed photo plate with three planes (photo, mist, vector board fence) at different rates | flow > pan > pin > flow > reveal-in-flow > flow > flow; 7 acts, 13.3vh desktop, 15.4vh phone; peak is the 4.2 pin | Tear-off: valuation form set as a blank lot in the listing schema, holds on paper with the footer inside | Tear-off lot composes live and drops a pin on the plat at the seller's town | Minnesota horse country, stock photos, Clarendon (Besley) + Archivo | local 4500 |


---

## What is taken

Add a bullet here whenever a build claims something a later build should avoid
reusing: a grammar, a nav treatment, a close pattern, a signature move, an
act-count-and-length band. The shared columns are what the next build inherits
as a constraint, so writing them down is the whole point.

- Grammar: Sale bill (saddle-section).
- Signature: a form that composes a live listing card and pins it on a scroll-drawn map (saddle-section).
- Peak: a pinned SVG map that draws grid, rivers, rings, then drops pins from `--sc-p` (saddle-section).
- Hero: framed photo plate with a vector foreground fence and a mist plane (saddle-section).

---

## Appending a row

After shipping, add one line to the table and one bullet to **What is taken** if
the build claimed something new. Fill every column. Say what the build shares
with existing rows.

Rows are append-only. A build that has been superseded stays in the table,
because the space it occupies is still occupied.

---

## Worked example

The skill's author kept a registry of twelve builds across eight page grammars.
If you want to see what a filled-in table looks like, and which shapes tend to
collide, read `EXAMPLES.md` in the scroll-craft repository. Treat it as
illustration only: those rows are somebody else's builds and they do **not**
constrain yours.
