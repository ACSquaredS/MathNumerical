# MathNumerical

Numerical methods for [MathCraft](https://github.com/ACSquaredS/MathCraft), an open-source, MATLAB-inspired numerical computing environment.

> **Status:** Early stage. The repository is set up; implementation has not started.

## Role in MathCraft

MathNumerical provides the numerical algorithms that other modules call. It works on the arrays and types defined in [MathCore](https://github.com/ACSquaredS/MathCore).

## Depends on

- [MathCore](https://github.com/ACSquaredS/MathCore)

## Planned scope

- Linear algebra: LU, QR, Cholesky, SVD and eigen decomposition
- Linear system solvers
- Interpolation and curve fitting
- Root finding and optimization
- Numerical integration (quadrature)
- ODE solvers (Runge-Kutta and multistep methods)

## Boundaries

ODE solvers live here. [MathSimulation](https://github.com/ACSquaredS/MathSimulation) calls them and does not reimplement them.

## Getting started

Not available yet. This section will be filled in with the first release.

## Contributing

Contribution guidelines will be published in the [MathCraft](https://github.com/ACSquaredS/MathCraft) umbrella repository. Until then, open an issue to discuss a change before sending a pull request.

## License

Released under the [MIT License](LICENSE).
