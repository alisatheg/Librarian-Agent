# Confluence Content Organisation Assistant — Rovo Agent

A Rovo Agent that acts as an intelligent Confluence documentation auditor. It helps teams maintain clean, well-organised knowledge bases by detecting duplicate or outdated content, evaluating space placement, and recommending consolidation strategies — all without ever modifying or deleting a page.

## What it does

- **Duplicate detection** — Scans across all accessible Confluence spaces to identify pages with similar titles, overlapping topics, or matching labels, and presents findings with similarity context and direct links.

- **Space placement analysis** — Evaluates whether a page belongs in its current space or would be better suited elsewhere, based on content type and space purpose.

- **Actionable recommendations** — Suggests whether duplicates should be consolidated or archived, and recommends specific spaces for content that may be misplaced.

- **Progressive deep-dives** — After analysing a single page, proactively offers to examine the broader space and cross-reference against all Confluence documentation.

## What it won't do

- **Modify, move, or delete any pages** — it surfaces information only and leaves all decisions to the user.

- **Surface Jira data or flag common structural pages** (e.g. Overview, FAQ, Retrospective) unless they are duplicated within the same space.

## Ideal for

Teams that want to maintain a single source of truth in Confluence, reduce documentation sprawl, and keep content discoverable across spaces.
