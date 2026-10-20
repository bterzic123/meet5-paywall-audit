# Paywall Audit: Meet5

**Live:** https://bterzic123.github.io/meet5-paywall-audit/

Four ranked ideas for the Meet5 paywall, each backed by a finding from Adapty's
[State of Paywalls 2026](https://adapty.io/state-of-paywalls/?utm_source=paywall-audit&utm_medium=github-pages&utm_campaign=sop_2026&utm_content=meet5).
The page also has a clickable rebuild of the paywall and the close moment in Meet5's own design, with a Today / Proposed switch.

| # | Idea | Report finding | Potential outcome |
| :-- | :-- | :-- | :-- |
| 1 | Lead with 12 months, like your website does | Changing plan duration raised LTV in 59% of A/B tests (visual or copy changes: 35%) | Report finding, no range |
| 2 | Offer 6 months when someone says no | Only 4% of apps show a second-chance paywall; it beats the main one in 45% of apps | ARPU +10–15%, based on Adapty data |
| 3 | Put your 4.7 stars and your members' words on the paywall | Only 27% of top paywalls show social proof | CR +10–30%, observed in winning A/B tests |
| 4 | Greet them by name and city | Only 2% of top paywall headlines use what the app knows about the user | CR +8–17%, observed in winning A/B tests |

**Benchmark slice:** Lifestyle (App Store category) · Europe (home market). App Store data, Oct 2025 to Sep 2026.

**Grounding:** prices, ratings, benefits and the review come from Meet5's own in-app screens (iOS, 20 October 2026),
App Store listing and Premium page. Impact ranges are observed lifts from winning A/B tests in State of Paywalls 2026
and Adapty's own data, not measured results for Meet5.

**Personal link:** `?for=<first name>` changes the name in the hero and the prototype headline (default: Lars), and `&city=<city>` changes the city (default: Frankfurt).

Run locally:

```bash
python3 -m http.server 8000
```
