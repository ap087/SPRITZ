# SPRITZ – Stiffness Prediction via Resistance Inversion in Through-thickness Z-axis

[![Python Version](https://img.shields.io/badge/python-3.9%2B-blue.svg)]()

> [!NOTE]
> **Code Availability:** The codebase, simulation pipelines, and trained surrogates are currently under review and will be fully released upon publication of the accompanying manuscript in *Computational Materials Science*.

---

## Overview

**SPRITZ** (**S**tiffness **P**rediction via **R**esistance **I**nversion in **T**hrough-thickness **Z**-axis) is a numerical-analytical simulation framework for modeling the correlation between electrical resistance changes and stiffness loss in conductive composite laminates subjected to progressive damage.

Once released, the repository will provide:

- **Core modules**: Physical models, coupled FDM solver, configuration, IO, and logging.
- **Pipeline modules**: Modular execution steps for simulation, surrogate fitting, inverse damage and stiffness estimation, plotting, and conditioning analysis.
- **Simulation cases**: Parameter configurations (geometries, material properties, solver tolerances) and outputs.
- **CLI**: Command-line entry point to run individual steps or full pipelines.

---

## License

See [LICENSE](LICENSE).
