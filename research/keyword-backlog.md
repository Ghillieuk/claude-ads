# Keyword Backlog

Ranked gap candidates. Read each run before researching from scratch: promote the strongest unused item instead of starting cold if it still holds up. Add new finds every run; mark items used with a strikethrough-style note and a link to research/covered-log.md once written.

Scoring: **Fit** = intent match with Ghillie's actual catalogue · **Demand** = plausible UK search volume · **Winnability** = realistic for a small independent brand to rank/compete on.

## Candidates (2026-08-04 audit)

1. **Gilet vs body warmer: what's the difference.** Fit: High (Torr Wool Gilet is a flagship product) · Demand: High (GO Outdoors, Millets, Trespass, Philip Morris & Son, Cherry Tree Country Clothing, TCA, Coes all run this exact article) · Winnability: High (none of the five pinned competitors have a dedicated explainer under this framing; Schöffel's "Ultimate Gilets Guide" is adjacent but broader/product-catalogue-led, not a plain-English terms explainer). **USED 2026-08-04.** See field-notes/2026-08-04-gilet-vs-body-warmer-whats-the-difference/post.md.

2. **Shacket vs overshirt: what's the difference.** Fit: High (Ghillie sells overshirts within its outerwear range) · Demand: Medium-High (The Modest Man, Moss Bros, Gentleman's Gazette, TOG24, Faherty all cover it; strong UK menswear search term) · Winnability: High (confirmed 2026-08-05: none of the five pinned competitors, nor Barbour/Musto/Joules/Seeland/Ridgeline/The Field, run a dedicated explainer; the content is owned entirely by generic fashion blogs, not country-lifestyle brands). **USED 2026-08-05.** See field-notes/2026-08-05-shacket-vs-overshirt-whats-the-difference/post.md.

3. **What to wear to a country show / game fair (men's outfit guide).** Fit: Medium (Ghillie's lifestyle pieces suit this, but catalogue lacks tweed/breeks so can't cover the "smart" end authentically) · Demand: High but seasonal. Game Fair is a July fixture, so this should be drafted and published ahead of next year's event (aim for a run in ~May/June), not now. Heavily contested (Philip Morris & Son, Outdoor and Country, Dubarry, Wadswick, Serious Country Sports, Rydale, Gunner and Hound all rank). Hold until seasonally relevant.

4. **Trucker cap: how to wear one (and why camo isn't tactical).** Fit: High (Original + Camo Trucker Caps are live SKUs; useful chance to reinforce the "countryside lifestyle, not military" framing the brand guardrails require) · Demand: Low-Medium (niche, but low competition) · Winnability: High (little dedicated content from pinned competitors on trucker caps specifically; Schöffel/Orvis skew flat caps/beanies). Good low-effort future pick.

5. **Midlayer vs base layer vs outer layer, explained simply.** Fit: High (maps directly to /collections/midlayers) · Demand: Medium · Winnability: Medium. Risk of overlapping heavily with the existing "Complete Guide to Outdoor Layering for Men" post; would need a genuinely distinct angle (e.g. a quick-reference/glossary format) to avoid cannibalisation. Lower priority until a distinct angle is found.

6. **How to care for a wool gilet (dry-clean guide, between-wears care).** Fit: High · Demand: Medium (Asket, Asphalte, ONAIE, Joseph Turner all run wool-specific care guides) · Winnability: Medium. Ghillie already has some general garment-care content referenced on the blog index; needs confirming exactly what that post covers before committing, to avoid duplicating it. Re-check on next run once the live blog is directly fetchable.

7. **Gift guide for outdoorsy/countryside men (Christmas).** Fit: High · Demand: High but sharply seasonal. Hold for a November run.

8. **Flannel vs check shirt: what's the actual difference.** Fit: High but Ghillie already has "How to Choose a Flannel Shirt: The Men's Buying Guide" live, which likely covers this ground. Low priority / possible duplicate; skip unless a genuinely new angle appears.

9. **What to wear for the start of game season (grouse/partridge/pheasant opening days).** Fit: Low-Medium (Ghillie's catalogue is countryside lifestyle wear, not technical shooting kit; breeks, tweed plus-fours etc. aren't in range) · Demand: Medium, timely (grouse season opens 12 Aug) · Winnability: Low for this brand specifically; better suited to brands with shooting-specific ranges. Deprioritised.

10. **Fleece vs wool midlayer: which is warmer, which to choose.** Fit: High (maps directly to /collections/midlayers, sits alongside the existing gilet post) · Demand: Medium · Winnability: Medium-High (no pinned competitor found running this exact comparison framing; would need a genuinely distinct angle from the existing layering guide to avoid overlap). Good next-pick candidate.

11. **How to wash a flannel shirt without ruining it (care guide).** Fit: High (Brae/Munro Flannel Shirts are flagship SKUs) · Demand: Medium (general menswear/workwear sites run flannel-specific wash guides) · Winnability: Medium (distinct from the existing "How to Choose a Flannel Shirt" buying guide, since that's purchase-intent and this is post-purchase care, but check it doesn't overlap the unconfirmed general garment-care post referenced in covered-log once the blog is directly fetchable).

12. **What to wear to a country pub (smart-casual countryside occasion dressing).** Fit: Medium-High (overshirts, flannels and the gilet all suit this) · Demand: Medium · Winnability: Medium (Philip Morris & Son and Outdoor and Country touch on "pub-ready" styling within broader guides, but no pinned competitor has a dedicated piece). Worth a future run.

## Notes for next run

- Live blog (https://ghillieuk.com/blogs/news) and sitemap.xml again returned HTTP 403 via WebFetch and via curl through the session's egress proxy on 2026-08-05, and the proxy status endpoint again confirmed `connect_rejected` / organisation policy denial for `ghillieuk.com:443`. This is now confirmed persistent across two runs, not transient. Continue using WebSearch as the fallback until this changes; re-attempt a direct fetch each run regardless, since an unblock would let us correct/complete the covered-log inventory (in particular, pin down the exact title/slug of the existing garment-care post referenced above, and confirm exact overshirt product names/slugs for direct product links).
- **Trap for future runs:** WebSearch snippets about ghillieuk.com repeatedly surface two facts that directly contradict the brand guardrails: "donates 5% of profits to the Atlantic Salmon Trust" (forbidden, no Atlantic salmon/river-conservation angle) and "free UK delivery over £90" (the guardrails specify £150, never £90). These appear to be stale/incorrect cached copy indexed from an older version of the site. Do not use either claim, regardless of how many search results repeat them; only use the verified claims list in the task prompt (free UK delivery over £150, 14-day returns, tracked 24-hour delivery, Designed in Britain).
- research/competitors.md exists but is still empty; no owner-pinned extra competitors on file yet. Check it each future run.
