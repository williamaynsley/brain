# Lost-to-rank impression share is usually a bid story, not a copy story
date: 2026-09-01

Ad Rank = your bid x ad/LP quality x context (+ extensions). Quality Score has three parts: expected CTR, ad relevance, landing page experience. Ad COPY only touches two of those three, inside one of the three-plus Ad Rank factors — so copy is the smallest lever on rank-lost IS, not the main one.

The bigger lever is almost always the BID, and on an automated bid strategy the bid is set by your target. A campaign on target ROAS 20 that is achieving 19.5 is not losing rank because the ads are weak — the algorithm is refusing to bid higher because the next impression would break the target. Rank-lost IS is the visible shadow of a tROAS/tCPA ceiling.

Diagnostic order when you see high rank-lost IS: (1) is there a tROAS/tCPA target, and is achieved ~= target? then it is self-imposed; (2) Quality Score components — which of the three is low; (3) only then look at ad strength/copy.

CORRECTION (same day, after reading live keyword data): I first guessed that a low Quality Score on your OWN brand terms points at landing page experience rather than copy. Wrong — go look at the three components before guessing, because Google reports them separately per keyword and they disagree.

L'ange Brand Search US, live 30d Aug 2026: landing_page_exp = ABOVE_AVERAGE on every brand keyword, expected_ctr = ABOVE_AVERAGE, but ad_relevance = BELOW_AVERAGE on most head terms. Landing page was fine. Ad relevance was the weak one — and ad relevance IS the copy-to-keyword match.

But the fix still isn't "write punchier headlines". Every one of those keywords is BROAD match sitting in a single ad group literally named "Broad", with $64.6k/30d on the one keyword "lange". One ad group covering every brand variant means no ad can be specific to any of them, so ad relevance grades down. That is a STRUCTURE problem wearing a copy problem's clothes: the fix is tighter ad groups, then ads written per group.

Lesson that generalises: "ad relevance is below average" does not mean the copywriting is bad. It means the ad does not match the query closely enough — and match-type and ad-group structure decide that before any writing does.

Also: a below-average COMPONENT is not a low Quality Score. Those L'ange head terms score QS 8-10 overall. Audit tools conflate the two; check the number before repeating it.
