# Paywall Audit — Juno

**Live:** https://plykhvar-glitch.github.io/juno-paywall-rebuild/

Juno runs Meta ads with six different promises, and today every install lands on the same “Unlock Premium with a free trial”. This rebuild gives the three biggest groups their own paywall, in Juno’s design and at Juno’s prices. Prepared by Adapty, November 2026.

| # | Idea | Potential outcome |
| :-- | :-- | :-- |
| 1 | The paywall opens on the ad they tapped: “understands chronic illness”, “Why do I feel worse today?”, “Living with MS” | CR +15–20% |
| 2 | Condition ads (hEDS, MS, endometriosis) get a paywall that names the condition | CR +10–15% |
| 3 | 4.8 from 11K ratings and the review that matches each ad, next to the price | CR +10–15% |
| 4 | The Premium row the ad promised leads the feature list | CR +5–10% |
| 5 | One month at $14.99, no trial, when they tap the X, worded per ad | ARPU +10–15% |

The Paywall view (`?view=pw`) shows the three ads side by side, each phone with its own live paywall. One row of steps moves all three: 1 · The ad (as it runs in Reels), 2 · Today, 3 · Paywall, 4 · Offer on close. Under the third phone, switch between the MS, hEDS and endometriosis ads.

**Grounding.** Prices and plan lines from Juno’s in-app paywall: 7 days free then $99.99 / year ($8.33 / month), or $14.99 / month with no trial; the trial timeline, the Free vs Premium rows and the Oxford · UCL · Forbes · msn row as they ship. 4.8 from 11K ratings and the quoted reviews from Juno’s App Store listing and junocompanion.com, which also publishes HSA/FSA eligibility. Ad frames, ad copy, dates and version counts from Meta’s public Ad Library (search “Juno” chronic illness, sorted by impressions, read 4 November 2026).

*Impact ranges are Adapty’s expected effect from teardowns and A/B tests across subscription apps — not measured lift for Juno.*

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/?view=pw.
