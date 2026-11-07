# Two-stage vertical rocket model

This repository contains the MATLAB Live Script from a group project for an ordinary-differential-equations course. The model follows a two-stage rocket through powered flight and a short coast phase.

## Model outline

The script tracks height, velocity, and mass while accounting for:

- Stage-dependent thrust and fuel consumption.
- Gravity.
- Aerodynamic drag with changing air density.
- Separation of the first-stage dry mass.
- Numerical integration with `ode45`.

The output includes time histories for acceleration, velocity, altitude, and mass.

## My contribution

This was a group project. My main contribution was the acceleration and force analysis and reviewing how fuel consumption and stage transitions affect the acceleration curve. I am not presenting the full project as individual work.

## File

- `model/two_stage_rocket.mlx` — MATLAB Live Script containing the model and plots.

The original group report is not included because it contains other students' personal details.

## Scope

This is a one-dimensional educational model. It does not include guidance, attitude dynamics, orbital mechanics, detailed aerodynamics, or flight-safety validation.

