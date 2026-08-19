# DECISIONS.md — Kindling home page

> Fill in the bracketed parts in your own words before submitting.

## 1. Why this design direction over the obvious alternative I rejected?

Habit-tracker apps usually lean on points, badges, or leaderboards. I rejected
that in favor of a single honest metric — a flame that grows with real days
done and dims (not "resets to zero and shames you") on a missed day — because
the product's promise is honesty about consistency, not gamified pressure.
The flame is also the signature visual element, tying the name directly to
what the product shows you.

[Replace with your own reasoning if you changed anything.]

## 2. One trade-off I made under the time limit, and what I'd do with a real week

Trade-off: the streak card is static demo data — clicking a day doesn't
actually check it in, and there's no real state or backend. With a real week
I'd wire up the week grid to actual clickable state, add a proper mobile nav
pattern, and run a contrast check on both themes instead of eyeballing it.

[Replace with your own trade-off — pick something you actually cut.]

## 3. Where I used AI tools, and what I personally verified or changed

I used Claude to scaffold the HTML/CSS/JS from a brief (concept, palette using
named CSS colors only, section list, "keep it simpler than a prior version").
I then:
- [Say what you actually checked: 390px and 1440px widths, dark mode
  contrast, whether the flame click easter egg works.]
- [Note anything you changed — copy, colors, spacing, bugs you found.]

Be specific. "AI built it and it worked" is the answer that costs you the
follow-up call.
