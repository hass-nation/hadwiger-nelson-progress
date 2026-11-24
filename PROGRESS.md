# Progress

Status on 24 November 2026.

## Completed campaign

**VERIFIED BY CODE:** The forward search screened all scheduled work:

- Single points: 697 scheduled; all covered. The append-only output contains 700 records because some work was repeated during resumable execution.
- Adjacent pairs: 3,744 / 3,744 screened.
- Candidates below 2,242 edges: one.
- Best verified candidate: point 577, producing 2,241 edges.

The best single-point result removed five old edges and added four new ones. The best pair result reached 2,242 edges and did not improve the headline candidate.

## Engineering progress

- A shared SQLite work queue replaced fixed worker partitions.
- Previously completed JSONL records are pre-marked done when rebuilding the queue.
- Learned 4-colourings are shared across workers as CPU-checked SAT witnesses.
- A larger Kempe-derived starting pool and shared memory mapping reduced repeated work.
- Validation reproduced the earlier R0 and net values on 10 single points and three pairs.

## GPU experiments

**VERIFIED BY CODE:** GPU candidate generation produced four exact supergraphs after CPU/SymPy confirmation of every edge, but none demonstrated an improvement below 2,242 edges.

The experimental GPU colouring search failed sanity checks on deliberately easy 4-colourable graphs. Its earlier zero-success benchmark is therefore not trusted as evidence about GPU local search in general, and no GPU colouring code was adopted.
