# AI Visibility Lifecycle Specification (v0.7)

**⚠️ This document is NOT the canonical source.**

The authoritative reference is the Zenodo deposit:
https://doi.org/10.5281/zenodo.18500380

This specification mirrors the canonical source for developer
accessibility. In case of discrepancy, Zenodo governs.

---

## Overview

The 11-Stage AI Visibility Lifecycle is a stage-based observational framework describing how digital content achieves visibility within AI discovery, comprehension, trust, and human exposure systems.

## The Three Phases

**Stages 1–5: AI Comprehension** — AI systems discover, interpret, classify, harmonize, and validate the domain's knowledge structure against global sources.

**Stages 6–8: Trust Establishment** — AI systems build longitudinal trust, formally accept the domain as reliable, and determine competitive readiness for human surfacing.

**Stages 9–11: Human Visibility** — AI systems cautiously test the domain with real users, establish baseline ranking, and scale visibility based on sustained positive performance.

---

## Stage Definitions

### Stage 1 — AI Crawling

AI systems discover the domain through URL submissions, sitemaps, beacons, inter-domain signals, or autonomous exploration. Pages are fetched, rendered, and prepared for semantic analysis. This is pure discovery and reconnaissance—no interpretation or trust exists yet.

→ Detailed paper: [STAGE_1_AI_CRAWLING.md](STAGE_1_AI_CRAWLING.md) | DOI: [10.5281/zenodo.18512820](https://doi.org/10.5281/zenodo.18512820)

### Stage 2 — AI Ingestion

Raw content is decomposed into tokens, parsed for structure, and transformed into semantic embeddings. AI extracts ontologies, generates vector representations, and creates a provisional knowledge graph. The domain's content becomes machine-readable semantic material.

→ Detailed paper: [STAGE_2_AI_INGESTION.md](STAGE_2_AI_INGESTION.md) | DOI: [10.5281/zenodo.18512968](https://doi.org/10.5281/zenodo.18512968)

### Stage 3 — AI Classification (Purpose & Identity Assignment)

AI determines what kind of website it is dealing with: educational, commercial, institutional, advisory, or hybrid. This classification governs every downstream process—including safety thresholds, risk levels, ranking potential, and the strictness of evaluation. Purpose clarity is essential; ambiguity slows progression.

→ Detailed paper: [STAGE_3_AI_CLASSIFICATION.md](STAGE_3_AI_CLASSIFICATION.md) | DOI: [10.5281/zenodo.18513007](https://doi.org/10.5281/zenodo.18513007)

### Stage 4 — AI Harmony Checks (Internal Consistency Evaluation)

AI checks whether the website is internally coherent: consistent structure, tone, definitions, intent, and schema across all pages. Pages must "agree with each other" conceptually and structurally. This phase eliminates chaotic, contradictory, or low-coherence domains early.

→ Detailed paper: [STAGE_4_AI_HARMONY_CHECKS.md](STAGE_4_AI_HARMONY_CHECKS.md) | DOI: [10.5281/zenodo.18513032](https://doi.org/10.5281/zenodo.18513032)

### Stage 5 — AI Cross-Correlation (External Alignment Verification)

AI checks whether the site's content aligns with external, globally verified knowledge sources: government databases, foundational references, high-authority educational bodies, scientific repositories, occupational frameworks. AI is assessing: "Does this site fit into the global consensus?" High alignment → trust potential.

→ Detailed paper: [STAGE_5_AI_CROSS_CORRELATION.md](STAGE_5_AI_CROSS_CORRELATION.md) | DOI: [10.5281/zenodo.18513259](https://doi.org/10.5281/zenodo.18513259)

### Stage 6 — AI Trust Building (Accumulating Evidence Over Time)

AI gathers evidence of reliability across multiple layers: long-term stability, accuracy, consistency, neutrality, structural integrity, and purpose transparency. Trust is iterative, not binary—AI must see repeated proof over many crawls. Only sites with durable integrity progress.

→ Detailed paper: [STAGE_6_AI_TRUST_BUILDING.md](STAGE_6_AI_TRUST_BUILDING.md) | DOI: [10.5281/zenodo.18513553](https://doi.org/10.5281/zenodo.18513553)

### Stage 7 — AI Trust Acceptance (Formal Eligibility for Use in Answers)

Once trust signals cross a threshold, AI formally marks the domain as a reliable reference node. It becomes eligible for use in answer synthesis, citations, and multi-source reasoning. The domain now exists in the AI's "trusted knowledge set," but is not yet visible to humans.

→ Detailed paper: [STAGE_7_AI_TRUST_ACCEPTANCE.md](STAGE_7_AI_TRUST_ACCEPTANCE.md) | DOI: [10.5281/zenodo.18513688](https://doi.org/10.5281/zenodo.18513688)

### Stage 8 — Candidate Surfacing (Competitive Readiness Assessment)

AI evaluates whether a trusted domain should enter the human-facing competitive layer. It maps query relevance, benchmarks against visible competitors, scores user-value potential, and tests visibility risk. This determines when and where the domain becomes eligible for human exposure.

→ Detailed paper: [STAGE_8_CANDIDATE_SURFACING.md](STAGE_8_CANDIDATE_SURFACING.md) | DOI: [10.5281/zenodo.18513751](https://doi.org/10.5281/zenodo.18513751)

### Stage 9 — Early Human Visibility Testing (Controlled User Experiments)

AI exposes the domain to a tiny fraction of real search queries (<0.1% traffic) and measures user behavior: satisfaction, dwell time, task completion, return rates. This validates whether real humans find the content useful. Poor performance pauses progression; strong performance advances to Stage 10.

→ Detailed paper: [STAGE_9_EARLY_HUMAN_VISIBILITY_TESTING.md](STAGE_9_EARLY_HUMAN_VISIBILITY_TESTING.md) | DOI: [10.5281/zenodo.18514086](https://doi.org/10.5281/zenodo.18514086)

### Stage 10 — Baseline Human Ranking (First Stable Search Placement)

The site is now included in real SERPs in a controlled, low-risk fashion—typically for long-tail and mid-tail queries. AI measures behavior at scale, compares outcomes against competitors, and checks regional stability. This stage establishes the first reliable human traffic baseline.

→ Detailed paper: [STAGE_10_BASELINE_HUMAN_RANKING.md](STAGE_10_BASELINE_HUMAN_RANKING.md) | DOI: [10.5281/zenodo.18514176](https://doi.org/10.5281/zenodo.18514176)

### Stage 11 — Growth Visibility & Human Traffic Acceleration

If baseline performance is strong, AI expands visibility across regions, query families, device types, and tail depths. Human traffic increases meaningfully and predictably. The domain enters the global search ecosystem as a scalable, reliable knowledge asset.

→ Detailed paper: [STAGE_11_GROWTH_VISIBILITY.md](STAGE_11_GROWTH_VISIBILITY.md) | DOI: [10.5281/zenodo.18514275](https://doi.org/10.5281/zenodo.18514275)

---

## Key Principles

1. Stages 1–2 are sequential gates; Stages 3–11 operate as parallel evaluation dimensions.

2. Architectural quality determines timeline; commercial classification determines trust threshold height.

3. Crawlability (Stage 1) ≠ Visibility (Stages 9–11).

4. Baseline success rate: 1–6% for all websites. Projected rate: 50–70% for optimised sites (analytical estimates).

---

## Related Papers

| Paper | DOI |
|-------|-----|
| [AI Visibility Lifecycle](AI_Visibility_Lifecycle.md) | [10.5281/zenodo.18500380](https://doi.org/10.5281/zenodo.18500380) |
| [Website Visibility & Activity Reporting](WEBSITE_VISIBILITY_AND_ACTIVITY_REPORTING.md) | [10.5281/zenodo.18512385](https://doi.org/10.5281/zenodo.18512385) |
| [Canonical Anchoring](CANONICAL_ANCHORING.md) | [10.5281/zenodo.18512549](https://doi.org/10.5281/zenodo.18512549) |
| [Ambiguity Elimination](AMBIGUITY_ELIMINATION_AS_AN_AI-NATIVE_VISIBILITY_STRATEGY.md) | [10.5281/zenodo.18500402](https://doi.org/10.5281/zenodo.18500402) |
| [29 SEO Tasks Transformed for AI Visibility](29_SEO_TASKS_TRANSFORMED_FOR_AI_VISIBILITY.md) | [10.5281/zenodo.18512464](https://doi.org/10.5281/zenodo.18512464) |

---

## Canonical Source

Zenodo: https://doi.org/10.5281/zenodo.18500380

Related: [aivisibilityarchitects.com](https://aivisibilityarchitects.com) | [cv4students.com](https://cv4students.com)

## Author

Bernard Lynch
AI Visibility Architecture Group Limited, Auckland, New Zealand

## License

CC BY-NC-ND 4.0

You are free to share this work with attribution, but you may not use it for commercial purposes or distribute modified versions.
