# 3D_tundish_deflated_LT3

- laminar flow in a simplified tundish
- a 3D box with a rectangular inlet at the top and a same-sized outlet at the bottom
- solving 3D Navier-Stokes equations
- segregated pressure-velocity coupling (Patankar's SIMPLE scheme)
- advection term discretization - reconstruction of Lagrangian trajectory
Dongbin Xiu and George Em Karniadakis, A Semi-Lagrangian High-Order Method for Navier–Stokes Equations, Journal of Computational Physics 172, 658–684 (2001)
(explicit midpoint rule)

- linear solver - PCG (two-level preconditioning: 1) Truncated Neumann series (TNS1) and 2) deflation
