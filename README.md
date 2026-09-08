# Results Scorecard

Q1 FY2026-27 (Apr-Jun 2026) results for 3,321 listed Indian companies, each graded
**Blockbuster / Good / Turnaround / Neutral / Poor / Disaster** and cross-cut by
balance-sheet quality, valuation, shareholding movement, and price reaction.

A single self-contained `index.html` - no build step, no backend.

## Method

Each quarter is scored 0-100 on five weighted pillars: revenue growth YoY (22%),
operating profit growth YoY (26%), core net profit growth YoY (22%), operating
margin change YoY (20%), and sequential momentum (10%). Pillars are banded against
absolute thresholds rather than ranked against peers.

- Growth is only computed off a positive base; sign flips are handled as events
  (**Turnaround**, **Disaster**) instead of meaningless percentages.
- The profit pillar runs on **core profit** - net profit less extraordinary items,
  compared like-for-like against the year-ago quarter.
- Companies that had not reported the June 2026 quarter are excluded by default.

Median 3-month price move runs in rating order (+18.6% for Blockbuster down to
-2.9% for Disaster), which is the closest thing to external validation available.

Figures are consolidated, in Rs crore, sourced from Screener.in.
Not investment advice.
