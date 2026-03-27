# KalmanWorks

KalmanWorks is a recursive estimation framework and learning sandbox built to serve learners,
practicing engineers, and advanced developers. The project aims to abstract the estimator
machinery enough that users can focus on defining the physics of the problem, while preserving
semantic rigor around state definition, measurement definition, and uncertainty modeling.

## Repository Layout

- `notebooks/teaching/`: pedagogical notebooks for concept-building and teaching
- `notebooks/development/`: framework-development notebook work and architecture exploration
- `implementations/`: umbrella folder for language-specific KalmanWorks codebases
- `implementations/python/`: active Python project root for the reusable KalmanWorks implementation
- `implementations/cpp/`: planned C++ implementation root for an equivalent KalmanWorks codebase
- `STRUCTURE.md`: auto-generated repository tree for tracking structural changes

## Active Direction

The Python implementation is the active development track today. As stable abstractions mature out
of the development notebooks, they can be migrated into the Python package under
`implementations/python/src/kalmanworks/`.

The C++ track is a planned medium-term companion implementation. Its goal is not to diverge from
the Python framework philosophy, but to provide an equivalent implementation in a systems-language
environment once the core abstractions are stable enough to mirror cleanly.

## Current Framework Focus

- model contracts such as `ProcessModel`, `MeasurementModel`, and `StateSpaceModel`
- estimator-core abstractions such as `BaseRecursiveFilter`
- logging and history utilities such as `FilterSnapshot` and `EstimationLogger`
- extraction of stable notebook-grown code into a reusable package structure

## Technology

- Python 3
- NumPy
- Jupyter Notebooks
- Matplotlib
- future C++ implementation track

## Attribution

This project is inspired by the clarity of Alex Becker's
_Kalman Filter from the Ground Up_, while remaining an independent implementation and learning effort.
