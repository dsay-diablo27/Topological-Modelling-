Open Quantum System Steady-State Simulation

This repository contains a numerical study of an open quantum system using a 1D tight-binding model. The project leverages the Lindblad Master Equation to calculate and visualize the steady-state density matrix of a system subject to specific dissipation and gain parameters.
📖 Overview

The simulation investigates the behavior of a quantum particle on a 1D lattice. It specifically focuses on:

    Hamiltonian Construction: Generating a tight-binding Hamiltonian (H) for a lattice of N sites.

    Dissipation Dynamics: Implementing jump operators (Lindblad operators) to model environmental interactions, such as site-specific gain and loss.

    Steady-State Analysis: Solving the Liouvillian superoperator (L) to find the density matrix ρss​ where dtdρ​=0.

    Basis Transformation: Analyzing the density matrix in both the site basis and the Hamiltonian eigenbasis to identify "commensurate" vs. "incommensurate" cases.

🛠 Features

    Customizable Parameters: Easily modify the number of sites (n), hopping strength (t), and jump operator coefficients (α,β,ν).

    Automated Visualization:

   1] Plots the diagonal elements (populations) of the steady-state density matrix across the lattice.

   2]  Generates heatmaps of the density matrix in the energy eigenbasis (ρpq​) using the inferno colormap.

   3] QuTiP Integration: Utilizes the QuTiP library for efficient quantum dynamics calculations.
