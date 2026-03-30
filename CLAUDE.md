# CLAUDE.md — Maintenance Guide for industry-datasets

This file tells Claude (and human contributors) how to keep this repository up to date.

## What this repo is

A curated list of 200+ open datasets useful for machine learning, econometrics, marketing science, and transportation research. The README is the entire product — one markdown file, one table per category.

## Adding a dataset

Each entry is one table row:

```
| **Dataset Name** | 1-2 sentence description with concrete metrics (size, fields, time span). Note access requirements if non-trivial. | [Source](url) |
```

Rules:
- **Bold** the dataset name
- Include at least one concrete metric: number of records, users, time span, or key fields
- Use the exact URL from the dataset's official page or most reliable mirror
- Do not add entries for datasets behind paywalls with no academic access path

## Which section to use

| Domain | Section |
|--------|---------|
| Order/purchase/transaction logs | General e-Commerce |
| Session-based click trails (view→cart→buy) | E-Commerce Sessions |
| Platform clickstream, user behavior logs | Browsing and Search |
| Search engine logs, SERP, query-relevance, CTR | Search and Ranking |
| Short video / music / rec system data | Video Search and Recommendation |
| Viewer attention, emotional response to video | Video Engagement |
| News click logs, article impressions | News and Media |
| Product metadata, reviews, ratings | Product and Reviews |
| Taxi / rideshare GPS trajectories, trip records | Taxi and Ride-Hailing GPS |
| Naturalistic driving, highway sensors, AV data | Driving Behavior and Traffic Sensors |
| Pedestrian / general human movement | Human Trajectories |
| Dynamic discrete choice, structural estimation | Discrete Economic Choices |
| Hotel/flight/transport booking and search | Travel |
| Grocery, drug stores, supermarkets | Supermarkets and Grocery |
| Programmatic advertising, bidding logs | Display Advertising and Sponsored Search Auctions |

If unsure, pick the section whose existing entries most resemble the new dataset.

## When to split a section

Split when a section exceeds ~15 rows **and** has a natural thematic sub-grouping (not just alphabetical). Do not split purely for length if the datasets are thematically homogeneous.

## After adding datasets

1. Count the total datasets:
   ```bash
   grep -c '| \*\*' README.md
   ```
2. Update the counter line near the top:
   ```
   > **NNN datasets** across MM categories — last updated Month YYYY
   ```
3. Update the What's New block (see format below)
4. If you added a new section, add it to the Table of Contents with the correct anchor slug

## What's New format

```html
<details>
<summary><strong>What's New (Mon YYYY)</strong></summary>
<br>

- **Section Name** — Dataset1, Dataset2, Dataset3

</details>
```

- Place new `<details>` blocks above older ones (most recent first)
- Keep the last 2–3 updates; delete older ones
- Update an existing block if adding to the same month

## Anchor slugs

GitHub auto-generates anchors from section headers by lowercasing, replacing spaces with `-`, and removing special characters. Examples:
- `## E-Commerce Sessions` → `#e-commerce-sessions`
- `## Taxi and Ride-Hailing GPS` → `#taxi-and-ride-hailing-gps`
- `## Display Advertising and Sponsered Search Auctions` → `#display-advertising-and-sponsered-search-auctions`

## Commit style

```
Add <N> datasets: <brief list>
```

Example: `Add 3 datasets: KuaiRand, KuaiRec, Tenrec`

For structural changes: `Restructure: split <Section> into <A> and <B>`
