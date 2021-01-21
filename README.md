# copper-student-paper-2021

Student submission to 20th Copper Mountain Conference on Multigrid Methods

*A supervised learning approach to predicting multigrid convergence*

> Classical AMG solvers often require careful parameter tuning to achieve optimal convergence, and the way these parameters affect performance can be unpredictable in practice.  Evidence is presented that supervised learning techniques are able to learn certain characteristics of two-level multigrid solvers, particularly the rate of convergence and optimal relaxation weight for a given coarse/fine mesh splitting.  Random perturbations of C/F splittings are generated and evaluated in a multigrid solver to train a convolutional neural network (CNN) in order to predict convergence and a relaxation weight for the 1D variable coefficient Poisson equation, and to predict the convergence rate for a specific 2D convection-diffusion problem.  Additionally for the 2D problem, the use of graph nets is explored for use on general finite-element meshes.
