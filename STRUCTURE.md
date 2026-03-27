# Repository Structure

This file is auto-generated on every push to `main` and reflects the repository layout.

## Notebook Roles

- `notebooks/teaching/Part 1 - Introduction to Kalman Filter.ipynb`: Pedagogical notebook for introductory teaching and intuition-building.
- `notebooks/teaching/Part 2 - Multivariate Kalman Filter.ipynb`: Pedagogical notebook for multivariate-state teaching material and progressively richer examples.
- `notebooks/development/Kalman_Filter_class_development.ipynb`: Framework-development notebook used to evolve the reusable KalmanWorks architecture.

## Implementation Roots

- `implementations/`: Umbrella folder for language-specific KalmanWorks codebases.
- `implementations/python/`: Active Python project root for the current KalmanWorks implementation.
- `implementations/cpp/`: Planned C++ project root for a future equivalent implementation.

## File Tree

```text
.
|-- .gitignore
|-- implementations
|   |-- cpp
|   |   `-- README.md
|   |-- python
|   |   |-- pyproject.toml
|   |   |-- README.md
|   |   `-- src
|   |       `-- kalmanworks
|   |           `-- __init__.py
|   `-- README.md
|-- notebooks
|   |-- development
|   |   `-- Kalman_Filter_class_development.ipynb
|   `-- teaching
|       |-- Part 1 - Introduction to Kalman Filter.ipynb
|       `-- Part 2 - Multivariate Kalman Filter.ipynb
|-- README.md
`-- STRUCTURE.md
```
