# TrajectoryCalc

A browser-based calculator that estimates the maximum height, flight time, and range of a projectile launched at an angle, optionally from an elevated height.

## Live Demo
[Open TrajectoryCalc](https://YOUR-USERNAME.github.io/trajectorycalc/)

## Features

- Calculates time of flight, max height, and range
- Accounts for optional non-zero launch height
- Runs entirely client-side, no dependencies
- Basic input validation

## Formulas

- vx = v0 · cos(θ)
- vy = v0 · sin(θ)
- Time of flight: t = (vy + sqrt(vy² + 2gh)) / g
- Range: R = vx · t
- Max height: h + vy² / (2g)

## Example

Initial velocity: 25 m/s, angle: 45°, height: 0 m
→ Time of flight ≈ 3.60 s, Max height ≈ 15.9 m, Range ≈ 63.7 m

## Limitations

Ignores air resistance, wind, and spin. Assumes constant gravitational acceleration (9.81 m/s²). Educational use only.

## Technologies

HTML, CSS, JavaScript

## Author

Your Name — Mechanical and Aerospace Engineering Student
