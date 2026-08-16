# Artificial Intelligence — Coursework

Course work from **Artificial Intelligence**, 6th semester, FAST-NUCES Lahore (instructor: Mubashir Baig).

## Contents

| File | Topic |
|---|---|
| [`minimumPathUsing-Astar.ipynb`](minimumPathUsing-Astar.ipynb) | **A\* search** — shortest path on a weighted graph with an admissible heuristic |
| [`Hill_Climbing_AI.ipynb`](Hill_Climbing_AI.ipynb) | **Hill climbing** — local search, and the local-optimum problem it runs into |
| [`TicTacToe-AlphBetaPruning.py`](TicTacToe-AlphBetaPruning.py) | **Minimax with alpha-beta pruning** — an unbeatable Tic-Tac-Toe opponent |
| `Final Assignment.pdf`, `ReviewFinal.pdf` | Written assignments and exam review notes |

## Topics covered by the course

- **Foundations** — definitions of AI, history, real-world applications
- **Search** — uninformed (BFS, DFS, uniform cost) and informed (A\*, greedy best-first); heuristics and optimisation
- **Adversarial search** — minimax, alpha-beta pruning
- **Machine learning** — supervised (linear regression, decision trees, SVMs), unsupervised (clustering, dimensionality reduction), and the basics of neural networks

## Running the code

```bash
python TicTacToe-AlphBetaPruning.py     # play against the agent
jupyter notebook                        # for the .ipynb files
```

## Related

A larger application of the search material is in [snake-puzzle-search-agents](https://github.com/maliawan0/snake-puzzle-search-agents), which compares A\* and Greedy Best-First on maze maps.
