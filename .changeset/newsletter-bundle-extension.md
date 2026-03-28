---
"adcontextprotocol": minor
---

Add bundle support to the newsletter extension. Introduces `ext.newsletter.bundle` with `total_unique_reach`, `audience_overlap_methodology`, and a `components` array (new `newsletter_bundle_component` schema) that provides per-newsletter subscriber counts, open/click rates, send cadence, and upcoming sendouts. Enables network/aggregator agents to model multi-publisher bundle products with transparent per-newsletter breakdown alongside deduplicated reach.
