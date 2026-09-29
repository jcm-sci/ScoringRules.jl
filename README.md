# ScoringRules.jl

> [!IMPORTANT]
> **Inactive design scaffold.** This repository does not currently provide a
> usable Julia package or public API. Its source module and tests are
> placeholders, and the package is not registered in Julia's General registry.

## Alternatives

For working implementations of proper scoring rules, see the Python
[scoringrules](https://github.com/frazane/scoringrules) library or the R
[scoringRules](https://cran.r-project.org/web/packages/scoringRules/index.html)
package.

## Repository purpose

This repository is retained as a possible starting point for future Julia
work. There is no active development timeline. Do not depend on it for
research or production work.

## Development

```bash
julia --project=. -e 'using Pkg; Pkg.instantiate()'
just test
```

## License

MIT
