# Data Lab

A practical learning lab for numerical methods, artificial intelligence, and the code that connects both.

The repository starts with two university modules — **Numerical Algorithms** and **Fundamentals of Artificial Intelligence** — and turns the parts worth implementing into working code, tests, and small experiments.

The theory, lecture notes, and exercise write-ups live elsewhere. This repo is where ideas have to survive contact with Python.

## What lives here

```text
.
├── numerical-algorithms/       # Numerical methods and computational experiments
├── artificial-intelligence/    # Search, heuristics, classical AI, data structures
├── experiments/                # Cross-topic experiments and comparisons
├── src/
│   └── data_lab/               # Reusable implementations
└── tests/                      # Tests for implementations that claim to work
```

## Current focus

### Numerical Algorithms

Implementing and experimenting with numerical methods such as:

- root finding
- linear systems
- approximation and interpolation
- numerical optimization
- error and convergence analysis

The goal is not only to get a number out, but to understand why it is probably the right number.

### Artificial Intelligence

Practical implementations around:

- graph and state-space search
- BFS, DFS, and A*
- heuristics
- classical AI algorithms
- useful data structures behind them

This also doubles as deliberate practice for algorithms and data structures.

## Where this is going

As the foundations become solid, the repository will gradually expand into machine learning, neural networks, embeddings, transformers, vector retrieval, and RAG.

That growth is intentional: new areas are added when the underlying ideas have actually been learned and implemented, not because an empty folder called `llm/` looks impressive.

Cloud and Microsoft Fabric / DP-700 related work is planned for a later stage, once the local foundations are mature enough to be worth moving somewhere more expensive.

## Working principle

A typical topic moves through roughly this loop:

```text
understand → implement → test → break → compare → understand better
```

Sometimes the order varies around `break`.

## Tech

The repository is Python-first. Libraries will be introduced where they help investigate the actual method instead of hiding it completely.

Initial tooling:

- Python 3.11+
- NumPy
- SciPy
- Matplotlib
- pytest

More will be added when the experiments need it.
