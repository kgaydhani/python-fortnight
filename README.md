# Python Fortnight

Twelve days, full time, September 2026. One goal: stop writing Python in the accent of
another language.

I could produce working Python — production data pipelines for NHS Scotland, a year of it
— but the honest read on my own code was that the reasoning was mine and the idiom
wasn't. Loops where comprehensions belonged, index arithmetic where slices belonged, and
the more advanced work leaning on AI I hadn't earned. This repo is the log of fixing that.

**Ground rule for the whole fortnight: no AI writes a line of the code here.** Claude
teaches, quizzes and pulls my designs apart; every line committed is typed by me. The
commit history is the evidence.

## What's here

| | |
|---|---|
| `fluent/` | Notebooks working through *Fluent Python* (Ramalho, 2e), chapter by chapter |
| `drills/` | Daily cold-coding drills — timer on, no autocomplete, no lookups |
| `scratch.ipynb` | The daily scratchpad |

The two real builds live in their own repos:

- **`wordle`** — a rewrite of a 100-line single-cell notebook as a properly designed,
  typed, tested package. The before-and-after is the point.
- **`minidf`** — a lazy query engine over CSV files. Iterator protocols, generators,
  operator overloading, context managers, all load-bearing rather than demonstrated.

## Reading log

Fluent Python, Parts I–IV cover to cover, Part V read once. Notes per chapter live
alongside the notebooks.

## A note on what's missing

`kubrick/` is gitignored. It holds my employer's training course and mock assessments,
which are their material and not mine to publish. The scores are mine and I'll quote
them; the questions stay off the internet.

## Scoreboard

| Benchmark | Date | Result |
|---|---|---|
| Python Core Mock 1 — original, during training | Sep 2025 | 40/40 |
| Python Core Mock 1 — cold re-sit, one year on, no AI | 3 Sep 2026 | 36/40 |
| Python Core Mock 1 + 2 — after the fortnight | 18 Sep 2026 | — |
