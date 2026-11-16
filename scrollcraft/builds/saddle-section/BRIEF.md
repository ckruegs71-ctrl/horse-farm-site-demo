# BRIEF: Saddle & Section (sample horse farm real estate site)

**Self-authored under explicit creative delegation.** On 2026-11-16 Chad chose "You decide" for creative direction. He answered three of the forks himself (quoted below). The rest are authored decisions, labeled as such. Nothing here is a made-up quote from Chad.

## Evidence (what Chad actually said)

- Purpose: "a new website for their real estate company that promotes listing horse farms with them around the twin cities."
- Audience: "It's for Sellers listing horse farms with them. Also, they are hoping buyers will come to their site to look for people selling horse farms."
- Vibe: "this is Midwest properties in Minnesota so make sure you are getting the right vibe."
- On the first draft: "That looks great, but I don't like the font on the front page... That looks like AI slop font to me."
- Structure fork: picked **Distinct scenes**.
- Imagery: "Free stock for now, realtors might get me their own photos for the real site."
- Style range: picked **Heritage farm-bill**.

## The eight topics

1. **Vibe (authored):** Minnesota horse country at dawn, printed like a farm sale bill. References: a 1950s county farm auction bill set in Clarendon; a Minnesota county plat book; the wood-and-board fences along County Road 6 in Independence in early fall.
2. **Scroll journey (authored, from Chad's priorities):** First, a calm dawn pasture and who they are. Then the farms for sale, laid out like lots on a bill. Then where the farms actually are. Then how they sell a farm (sellers are the main audience). Then the Minnesota-specific winter facts. Then guides and agents (short). Last, the seller fills in their own farm.
3. **Energy (authored):** Calm open, brisk farms rail, the biggest and slowest moment at the map, calm and plain through selling and winter, ending steady and practical.
4. **Feeling, stage by stage (authored):** see the feeling curve below. The one moment: the map drawing itself and the farms dropping into place.
5. **What no other site does (authored):** the seller types their farm into a blank lot, and it is drawn onto the same plat map as the farms for sale.
6. **Range (Chad):** Heritage farm-bill.
7. **Structure (Chad):** Distinct scenes.
8. **Assets (Chad):** none yet. Free Unsplash stock now; the Realtors may supply real photos later. No image generation (no KIE key, and none was asked for).

## Grammar: Sale bill (new grammar, defined here)

The page is a printed farm sale bill. It reads top to bottom like one: masthead (who and where), lots (the farms, every one under the same fact schema), the plat (where they are), terms (how selling works), and a tear-off (the seller's own blank lot).

- **Nav:** a paper masthead strip with a lot index that jumps (Farms, Map, Selling, Winter, Valuation), and it marks where you are. It is never transparent over a photo.
- **Hero:** masthead type on the paper ground with a framed photo plate below it. Depth comes from planes inside and across the plate frame, not from copy laid over a photo.
- **Sequence:** paper and night grounds change on hard edges. No color drift.
- **Close:** the tear-off. The valuation form is set as a blank lot in the exact listing schema, it fills in live, and it lands on the plat.
- **Bans:** copy over photos with a scrim (copy sits on paper or night ground), `drift`, `magnet`, `spotlight`, `scrub` video, word or character kinetic splits, rounded shadowed cards (lots are ruled, not carded), pills and tags laid over photos, centered body copy.

Why the eight standard grammars lost:
- **Filmic one-shot** forbids jump navigation and tool chrome, but a listings site needs both.
- **Chaptered editorial** wants long-form reading. These visitors scan facts.
- **Live surface** applies to software.
- **Continuous world** was ruled out by Chad's "distinct scenes."
- **Typographic poster** bans photography, but farms sell on photos.
- **Gallery/catalog** is closest: same-schema labels, an index nav, an inquiry plate. It loses on its hero rule (object one, no title), because the seller-first pitch needs a masthead that says who they are.
- **Split stage** has no two-sided argument here.
- **Rhythmic cutlist** is the wrong energy for land and horses.

## Journey (beats)

1. Recognition: this is Minnesota horse country, and these people sell it.
2. Appetite: here are real-looking farms, with the facts horse buyers check.
3. Orientation: this is where they are, and how far from the Cities.
4. Trust: this is how they would sell my farm.
5. Respect: they know what January does to a horse property.
6. Reassurance: plain guides, real agents (placeholders for now).
7. Commitment: my farm, filled in, on the map. Get a farm valuation.

## Feeling curve (written before the score)

| Act | Feeling | What causes it |
|---|---|---|
| 1 Masthead | Stillness | Dawn pasture in a framed plate; the mist drifts slower than the board fence passing in front of it |
| 2 Lots | Appetite | Farms travel sideways, each under the same honest label: acres, stalls, arena, miles, price |
| 3 Plat (PEAK) | Orientation, then wonder | An empty survey grid on a night ground; the township lines draw in, then rivers, mile rings, towns, and finally each farm drops onto its spot |
| 4 Terms | Confidence | Plain numbered steps beside a red gambrel barn; nothing moves but the reading |
| 5 Winter | Respect | A green board fence wipes into the same kind of fence under snow; the winter checklist sits beside it |
| 6 Guides | Reassurance | Short, plain answers and an honest agent placeholder; compressed |
| 7 Tear-off | Ownership, resolve | A blank lot the seller fills in; their farm takes shape and pins onto the plat; the page holds there |

**The peak (act 3):** "a blank survey grid drew itself across the screen, the rivers came in, and then every farm dropped onto the map where it really is."

**Tell-someone sentence:** "It's the site where you type in your own farm and it lands on the same map as the farms for sale."

**Authored silence:** the opening of act 3 is a nearly empty night ground with one line of copy before the grid draws. That is deliberate quiet before the peak, not dead scroll.

## Signature move

**The tear-off lot.** The valuation form is typeset as a blank lot in the exact schema of the listings. As the seller types, a live lot composes beside it: name, town and county, straight-line miles to the nearer downtown, acres, stalls, arena. Picking a town drops a barn-red pin onto a small copy of the plat, at its real coordinates and mile ring. Bespoke page JS; the engine is untouched.

## Score

| Act | Device | Span | Why this one |
|---|---|---|---|
| 1 Masthead | parallax (bespoke planes: photo, mist, fence) | flow | Depth from planes moving at different rates is the stillness; nothing should be pinned on landing |
| 2 Lots | `pan` | 3.2 | Sideways reads as "options," and every lot shares one label |
| 3 Plat | `pin` + bespoke draw from `--sc-p` | 4.2 (largest) | The held frame is the slow breath; scroll literally draws the map |
| 4 Terms | `flow` + `in` | flow | An administrative beat; it is read, not watched |
| 5 Winter | `reveal` (wipe) | flow act | A wipe is a change of state, and here it is summer to winter |
| 6 Guides | `flow` + `in` (short) | flow | Compress the administrative part |
| 7 Tear-off | bespoke signature on a flow section | flow, holds | The page stops moving and starts responding |

Checks: 5 device families (parallax, pan, pin, flow/in, reveal). No family twice in a row (4 flow, 5 reveal, 6 flow). Zero scrub. The peak has the largest span. No two adjacent acts share a feeling.

## Revision 1 (2026-11-16, from Chad's review)

Chad's words: the moving fence in the opening "looks like an ai generated fence. either get rid of it or make it permanant. I would like to see what a nice big white fence looks like." The farms "roll in from the right side of the screen, that should not happen." On the map, "you have to scroll for the entire map ... to be built ... Just have it show up when you scroll through to that page."

Changes:
- **Hero:** the layered plate (photo, mist, generated SVG fence, pointer parallax) is gone. One still photo of three horses at a white three-board fence (Pexels 9042971). Square crop on phones so the full fence shows.
- **Farms:** the `pan` act is now a `flow` section with a fixed three-column grid (two on tablets, one on phones). Filters sit beside the heading; the sign-up is a strip under the grid. Filtering still reorders and dims.
- **Map:** the `pin` act and the scroll-drawn plat are gone. The map renders whole on arrival, with one heading, one paragraph, and the area buttons. On phones the map sits between the paragraph and the buttons.
- **Score now:** flow, flow, flow, flow, reveal (winter wipe), flow, flow plus the tear-off signature. The variety rule is relaxed by the client's direction; the page leans on content and the tear-off, not scroll effects. Page length dropped from 13.3 to 9.1 screens on desktop.
