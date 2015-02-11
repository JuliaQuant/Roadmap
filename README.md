# Roadmap
High-level overview of group's goals and objectives

## NOW

* Naive backtesting with `FinancialBlotter.jl`: **order placement logic** with user-defined signals (trading rules). Tests: Faber strategy (stock), luxor (forex): numerical verification from papers or quantstrat demos.
* Uniform documentation scheme (`Docile.jl`, `Lexicon.jl`); continuous integration Lexicon -> `gh-pages`

## SOON (higher priority)

* Strategy parameter optimization on user-defined grids
* Rolling parameter optimization (walk-forward analysis)

## LATER

* Real-world order fill simulation
* Process custom order sizing functions
* Parameter optimization with local search methods and global search heuristics

## ONGOING (as needed)

* Technical indicator wishlist here
* Analytics metrics wishlist here
