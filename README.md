# ScoringRules.jl

Proper scoring rules for probabilistic forecast evaluation in Julia.

Provides CRPS, energy score, weighted interval score, Brier score, and other
metrics for evaluating probabilistic predictions. Inspired by the Python
[scoringrules](https://github.com/frazane/scoringrules) library and the R
[scoringRules](https://cran.r-project.org/web/packages/scoringRules/index.html)
package.

## Installation

```julia
using Pkg
Pkg.add("ScoringRules")
```

## Development

```bash
julia --project=. -e 'using Pkg; Pkg.instantiate()'
just test
```

## License

MIT
