# Dynamic Request Scheduling Optimization in Mobile Edge Computing for IoT Application
## Introduction

The research paper and this project tackle the same two main problems, but I have solved them using different algorithms:

1. Uplink Power Allocation Problem (PA) <br />
Author’s solution: Non-Cooperative Game Model Based On Subgradient (NCGG) <br />
My implementation: Inertia Weighted Particle Swarm Optimisation <br />

2. Joint Resource Offloading And Computing Resource Scheduling Problem (JRORS) <br />
Author’s solution: Multiple-Objective Optimization i-NSGA-II (MO-NSGA) <br />
My implementation: Binary Particle Swarm Optimisation
## Code

The code is divided as follows:

1. main.m <br />
This file starts off with setting the parameters of the UDEC system model. Then, we solve the power allocation problem using simulated annealing (not optimized) and particle swarm optimization. Finally, the joint request offloading and resource scheduling is solved using binary particle swarm optimization.

2. PA.m <br />
This file contains the function for the power allocation problem.

3. JRORS.M <br />
This file contains the function for the joint request offloading and resource scheduling problem.

4. OutputPlots.m <br />
This file plots the required simulation graphs, with each section covering one plot.
## Tools Used

* MATLAB R2020b (Version 9.9)
* Global Optimization Toolbox
* Optimization Toolbox

Github link
https://github.com/Rutu2242/Miniproject
