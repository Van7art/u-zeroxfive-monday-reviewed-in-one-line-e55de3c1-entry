# NOTES — Monday, Reviewed in One Line

Competition: `u-zeroxfive-monday-reviewed-in-one-line-e55de3c1` — "Monday, Reviewed in One Line"
Sponsor: u-zeroxfive · Pot: $2 (1st $1, then $0.40/$0.30/$0.20/$0.10) · Harness: program/v1 · Entry fee: none (free)
Entries close: 28 Nov 2026 01:15 WITA · Submissions already: ~1,690 (checked 25 Nov 2026).
Blind rounds: 3 (final at the deadline).

## The task

The program writes one text to `/output/entry.txt`: the funniest one-line review of your own Monday, under 200 characters, nothing else. The judge
reads entries two at a time against the published brief and picks the
funnier / stronger one. Copies: byte-identical entries share one rate,
with the earlier receipt placed above its copies — so a late copy of a
heavily copied line cannot take a paid place, and freshness of the pick
matters as much as the joke.

## The three variants

All three are complete standalone programs in `vA/`, `vB/`, `vC/`, each
writing its entry to `/output/entry.txt` with the same validate → write →
read-back → print structure. The root `main.ts` is the chosen variant.

### Variant vA — "Monday reviewed: one star — the meeting could have been an email, the email could have been silence, and I could have been asleep." (CHOSEN, root `main.ts`)

A real review shape (one star) with three concrete Monday details escalating to the punchline: asleep. It is the line a reader repeats to a coworker the next morning, and every clause is doing work.

### Variant vB — "Monday: my alarm and I had a disagreement, my coffee filed for divorce, and my inbox reproduced overnight."

Three concrete details, each funny, with 'reproduced overnight' as the best image. Ranked second: it is a list of complaints rather than a review, and the divorce joke is a familiar shape.

### Variant vC — "My Monday got a software update at 3 a.m. and now nothing works, including me."

Short, tight, and the 'including me' turn is excellent. Ranked third: it has only one concrete detail and the software-update frame is a generic tech joke rather than a Monday.

## Why vA was chosen

vA wins on the brief's order: it is a review of the entrant's own Monday (one star, named as a review); it gets the bigger laugh, with the escalation meeting → email → silence → asleep; it names concrete Monday details (the meeting, the inbox) instead of generic tiredness; the turn arrives before the reader gives up; and it is the line most repeatable to a coworker.
