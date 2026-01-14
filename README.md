# PSO Initialization Techniques

This repository presents a comparative study of **Particle Swarm Optimization (PSO)**
using different **population initialization techniques** to enhance diversity
and avoid premature convergence.

## Initialization Methods
- Standard Random Initialization (BPSO)
- Halton Sequence (HPSO)
- Torus Sequence (TPSO)
- Linear Congruential Generator (LCG-PSO)
- Multiplicative Congruential Generator (MCG-PSO)

## Benchmark Functions
- Sphere
- Ackley
- Salomon
- Noisy Function
- Schwefel 1.2
- Rotated Hyper-Ellipsoid
- Axis-Parallel Hyper-Ellipsoid
- Schumer–Stieglitz
- Sum of Different Powers

## Experimental Setup
- Population size: 40
- Dimensions: 10, 20, 30
- Iterations: 1000
- Runs: 10
- Inertia weight: linearly decreasing (0.9 → 0.4)
- Acceleration coefficients: c1 = c2 = 2.0

## Results
The results demonstrate that **low-discrepancy sequence–based initialization**
methods significantly improve convergence speed and solution quality compared
to standard random initialization.

## How to Run
1. Open `PSO_Initialization_Techniques.ipynb` in **Google Colab**
2. Run all cells
3. Results and convergence plots will be generated automatically

## Author
**Iqra Saleem**  
Lecturer, Computer Science  
Research Area: Evolutionary Computing & Global Optimization
# PSO-Initialization-Techniques
Particle Swarm Optimization with Advanced Population Initialization Methods
