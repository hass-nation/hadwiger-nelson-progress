# Hadwiger–Nelson computational progress

This repository is a concise public record of computational work on finite unit-distance graphs related to the Hadwiger–Nelson problem. It contains results, current progress, and planned work only. It is not a full reproducibility archive.

## Current headline

**VERIFIED BY CODE:** A 509-vertex, 2,241-edge unit-distance graph has passed the project’s exact-geometry, DRAT, and proper five-colouring checks.

The construction starts from the 2,242-edge graph used by the current search, removes five edges, and adds one exact point with four incident unit edges. The resulting graph has 2,241 edges.

## What this does and does not establish

- **PROVEN by checked certificates:** the published candidate is not 4-colourable and has a proper 5-colouring.
- **VERIFIED BY CODE:** all its listed edges are exact unit distances and its 509 points are distinct.
- This is not a claim of global edge-minimality.
- This is not a minimum-order claim.
- This does not improve the known bounds for the chromatic number of the plane.
- Prior-art comparison is still in progress; no novelty or record claim is made here.

See [RESULTS.md](RESULTS.md), [PROGRESS.md](PROGRESS.md), and [PLANS.md](PLANS.md).

Last updated: 24 November 2026.
