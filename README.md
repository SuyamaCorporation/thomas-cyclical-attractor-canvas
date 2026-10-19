# Thomas Cyclically Symmetric Attractor Canvas

A 3D strange attractor visualization using Thomas' cyclically symmetric system.

## Features
- RK4 (Runge-Kutta 4th order) integration for accurate trajectory computation
- 8–12 simultaneous colored trajectories with glowing trails
- Perspective and orthographic projection modes
- Interactive drag-to-rotate (mouse and touch)
- Auto-rotation toggle
- b parameter slider (0.1–0.5) with chaotic/periodic behavior label
- Speed, trail length, and trajectory count controls
- Dark canvas with glowing neon trails

## Equations
- dx/dt = sin(y) − b·x
- dy/dt = sin(z) − b·y
- dz/dt = sin(x) − b·z

## Usage
Open `index.html` in any modern browser. No server required.

## Notes
- b < 0.329: chaotic attractor behavior
- b ≥ 0.329: limit cycle / periodic behavior
- Default b = 0.208963 (classical chaotic regime)
