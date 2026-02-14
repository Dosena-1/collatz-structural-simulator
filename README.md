[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18643393.svg)](https://doi.org/10.5281/zenodo.18643393)

# Collatz Structural Simulator

This repository provides a PHP implementation of the structural reformulation of the Collatz conjecture developed in:

**Miguel Cerdá Bennassar (2026)**  
*Reducción estructural de la conjetura de Collatz a la dinámica de una función inducida*

## Overview

The simulator implements:

- Segmentation of Collatz orbits into maximal consecutive odd tranches.
- Parametrization of tranche starts as:
  - binary reserve (`k`)
  - odd residual parameter (`t`)
- The induced function `D` describing transitions between tranche starts.
- Exact computation of structural variation per tranche.
- Accumulated structural balance.
- Empirical distribution analysis of the next binary reserve.
- Detection of persistent positive bias in the cumulative structural balance.

## Purpose

The simulator serves as a computational companion to the theoretical framework presented in the paper.  
It allows empirical exploration of:

- Structural descent behavior.
- Portal dynamics (`k = 1` cases).
- Distributional properties of the next binary reserve.
- Cumulative structural balance across tranches.

## Requirements

- PHP with the **BCMath** extension enabled.

## License

MIT License.

