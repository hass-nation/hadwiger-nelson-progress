# Results

All claims use the project labels **PROVEN**, **VERIFIED BY CODE**, or **HEURISTIC**.

| Graph | Vertices | Edges | Established property | Geometry SHA-256 |
|---|---:|---:|---|---|
| Exact Parts-509 rebuild | 509 | 2,442 | **PROVEN:** a checked DRAT certificate establishes non-4-colourability of a 2,441-edge spanning subgraph; exact unit-distance reconstruction verified | `a886678119f57281af8afe8429db1ab51221c63a758c377ef5b3fed383f0a273` |
| Reduced Parts-509 graph | 509 | 2,294 | **PROVEN:** 5-chromatic and vertex-critical | `ba81e7dd3a9e1ecec6a1c49b7b723dddb2117f1b4afc65f5717759ba1f734bea` |
| Replacement graph | 509 | 2,259 | **PROVEN:** 5-chromatic and edge-critical; every single-edge deletion has a checked 4-colouring | `1f8510787243a8c4a7a26b1d6d010272c951cd444f6ac981a63fefecbf7496c2` |
| Current candidate | 509 | 2,241 | **PROVEN:** non-4-colourable by checked DRAT and has a checked proper 5-colouring; **VERIFIED BY CODE:** exact geometry | `7ce3d1022cd32b1e8246795494285479e41dc6096f2d5fef1d665aeb5ae406d4` |

## 2,241-edge verification record

- Removed edges: `(149,347)`, `(171,347)`, `(172,347)`, `(255,340)`, `(255,347)`.
- Added point neighbours: `3`, `14`, `70`, `172`.
- Edge arithmetic: `2242 - 5 + 4 = 2241`.
- Exact coordinate recovery used the field `Q(sqrt(3), sqrt(5), sqrt(11))`.
- Exact geometry checking found zero non-unit edges and zero coincident points.
- The proof report recorded `drat_trim_verified: true` and `five_colouring_proper: true`.
- An independent DRAT recheck returned `s VERIFIED`.
- An independent reload checked the five-colouring on all 2,241 edges.

Certificate hashes:

- Graph: `7ce3d1022cd32b1e8246795494285479e41dc6096f2d5fef1d665aeb5ae406d4`
- CNF: `f6c3e1651ffc196d21ae6c066ccd9e8a9a41ada359fc4977e2e0c894964bc43d`
- DRAT: `a28f3dd80d386783a0ac702136085a9984fd12e1eaf1ea59d7c0f13d1e799d2a`

## Scope

The 2,259-edge graph is edge-critical within its fixed edge set. No artifact currently establishes that the 2,241-edge graph is edge-critical, globally edge-minimal, or minimum-order. No novelty claim is made pending a careful prior-art comparison.
