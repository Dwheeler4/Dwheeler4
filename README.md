## Daniel Wheeler

Computer Science @ UCL.

### Featured work

- **[chess-engine](https://github.com/Dwheeler4/chess-engine)** — a UCI chess engine in C++20: bitboards and magic
  bitboards, alpha-beta search with null-move pruning and late move reductions, a Zobrist-hashed transposition table,
  quiescence search, tapered evaluation. Move generation is verified against perft reference counts, with CI across
  four build configurations.

- **[semsearch](https://github.com/Dwheeler4/semsearch)** — a semantic search CLI over local code and notes, built on
  a from-scratch HNSW approximate-nearest-neighbour index (Malkov & Yashunin). Diagnosed poor recall — 41% recall@10
  on a 128k-chunk index — to a missing neighbour-selection heuristic, implemented the paper's Algorithm 4, and lifted
  recall@10 to 95%+ on realistic queries while staying ~2.5x faster than a vectorised BLAS brute-force scan.

- **[tetris-autoplayer](https://github.com/Dwheeler4/tetris-autoplayer)** — the move-selection AI for a Tetris engine
  provided as coursework: enumerates every placement, scores each board with a hand-designed evaluation (Tetris-well
  shaping, per-clear-count line scoring), and searches two plies with a beam. Weights tuned by hill-climbing self-play;
  ~32k median score, surviving the 400-piece limit in 6 of 8 self-play games.

### Now

Second year, looking for Summer 2027 software engineering internships.

[LinkedIn](https://linkedin.com/in/daniel-d-wheeler) · danielwheeler457@gmail.com
