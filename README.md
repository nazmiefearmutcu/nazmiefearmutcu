# Nazmi Efe Armutcu

Mathematics undergraduate in Türkiye. I build research prototypes and working systems — continual-learning
research, market-data infrastructure, real-time renderers.

## How I work

I direct AI coding agents to write the systems, and then hold what comes back to research standards rather
than demo standards. Concretely:

- **Thresholds are pre-registered, and git proves it.** In
  [Prizma-Chronos](https://github.com/nazmiefearmutcu/Prizma-Chronos) the pass/fail charter
  (`committee/charters/bar.md`) is its own commit, landed before the commit that adds the results it judges.
  The order is in the log, so the bar cannot have been moved after the numbers came in.
- **My own benchmarks get an adversarial pass.** A referee review goes after each run looking for baseline
  tuning, bit-budget leakage and floating-point artefacts, and it certifies *integrity* — that the comparison
  was fair — explicitly not that my method won.
- **Negative results ship.** Prizma-Chronos pre-registered six predictions; two of them failed. Both failures
  are in the README, with the reasons, and one of them falsified the project's original headline claim.

Agents make it cheap to produce code. They do not make it cheap to produce code that is *true*, so that is
where the effort goes.

## Research

**[Prizma-Chronos](https://github.com/nazmiefearmutcu/Prizma-Chronos)** — memory as reverse-time
reconstruction. A reversible recurrent core holds the whole past in one compressed state, and recall means
running it backward. The finding is that a *perfectly* reversible memory cannot read anything out of itself:
some forgetting is required before the recent past becomes decodable, and an optimal forgetting rate falls
out. Two of six pre-registered predictions (L3, L5) are reported **FAILED**, not quietly dropped.

**[Fuze](https://github.com/nazmiefearmutcu/Fuze)** — surprise-gated metaplastic consolidation for continual
learning: a per-synapse plasticity gate with no replay buffer, no task-boundary signal and no Fisher pass.
The README includes the streams where it loses — on mostly-compatible skill sequences the experience-replay
baseline wins outright, and the README says to use replay there instead.

## Systems

**[flowmap](https://github.com/nazmiefearmutcu/flowmap)** — dual-market order-flow visualizer. A WebGL2
renderer puts history in a texture so pan/zoom cost is independent of history depth, fed by a Python asyncio
gateway over a hand-packed binary wire protocol. The protocol is pinned by golden byte-vector fixtures on
both sides — the Python encoder and the TypeScript decoder assert against the same committed bytes — so a
wire change cannot silently desync the two. 492 client and 228 server tests green on a clean clone.

**[awareness](https://github.com/nazmiefearmutcu/awareness)** — a local index of the public web. Backfills
Common Crawl and live-tails RSS/GDELT into Apache Iceberg on your own disk, queried through DuckDB, in one
Python process, with nothing leaving the machine. Benchmarked head-to-head against `datasketch` 1.10 and
SQLite FTS5 — including where it loses: SQLite's dedicated inverted index answers keyword queries orders of
magnitude faster than DuckDB BM25, and MinHashLSH beats my SimHash pipeline on recall. Both losses are in
the README next to the wins.

## Volume

1,841 commits on the default branches of 18 public repositories since 12 May 2026.

## Contact

Open to work. **nazmiefearmutcu@gmail.com**
