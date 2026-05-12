# NFDI4Ing Model Validation Platform

This is the main repository of the NFDI4Ing Model Validation Platform. It contains shared infrastructure, documentation, example implementations, and a registry of all available benchmarks.

## Available Benchmarks

| Benchmark | Repository | Description |
|-----------|------------|-------------|
| Linear Elastic Plate with Hole | [Simulation-Benchmarks/linear-elastic-plate-with-hole](https://github.com/Simulation-Benchmarks/linear-elastic-plate-with-hole) | Convergence study for linear elasticity with analytical solution |
| Rotating Cylinders | [Simulation-Benchmarks/rotating-cylinders](https://github.com/Simulation-Benchmarks/rotating-cylinders) | Navier-Stokes flow between rotating cylinders (Taylor-Couette) |

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

## Quick Start

```bash
# Create the documentation environment
mamba env create -n model-validation-platform-docs -f environment.yml
conda activate model-validation-platform-docs

# Serve docs locally
mkdocs serve
```

## Documentation

The full documentation is hosted at [ReadTheDocs](https://nfdi4ingmodelvalidationplatform.readthedocs.io).

## Acknowledgments

This platform is developed as part of the NFDI4Ing initiative.
