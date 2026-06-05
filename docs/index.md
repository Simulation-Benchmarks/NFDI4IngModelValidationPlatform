# Welcome the NFDI4Ing Model Validation/Verification Platform

This is the main repository of the NFDI4Ing Model Validation Platform. It contains shared infrastructure, documentation, examples, and a registry of all available benchmarks.

## Available Benchmarks

| Benchmark | Repository | Description |
|-----------|------------|-------------|
| Linear Elastic Plate with Hole | [linear-elastic-plate-with-hole](https://github.com/Simulation-Benchmarks/linear-elastic-plate-with-hole) | Convergence study for linear elasticity with analytical solution |
| Rotating Cylinders | [rotating-cylinders](https://github.com/Simulation-Benchmarks/rotating-cylinders) | Navier-Stokes flow between rotating cylinders (Taylor-Couette) |
| Hele-Shaw Cells | [hele-shaw-cells-example](https://github.com/Simulation-Benchmarks/hele-shaw-cells-example) | Radial viscous fingering in a 2D circular Hele-Shaw cell (VOF, gap-averaged, OpenFOAM heleShawFoam) |

## Repository Structure

```
.
├── docs/                   # General documentation
│   └── getting_started/    # Tutorials and guides
├── examples/               # Example implementations showing how to build a benchmark
├── notebooks/              # Jupyter notebooks for exploring results
├── src/meshhelper/         # Shared mesh utility
└── .github/workflows/      # CI for examples
```

## Getting Started

- [Workflow Overview](getting_started/workflow.md)
- [Running a Benchmark](getting_started/run_benchmark.md)
- [Adding a New Benchmark](getting_started/benchmark_addition_guide.md)
- [Provenance and RO-Crates](getting_started/provenance.md)
- [ROHub Integration](rohub.md)

## Acknowledgments

This platform is developed as part of the NFDI4Ing initiative.
