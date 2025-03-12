
# Structural Transformations within the Solvate Ionic Liquid $\mathrm{[Li(Triglyme)][NTf_2]}$

This repository contains a collection of input files described in the paper "Structural Transformations within the Solvate Ionic Liquid $\mathrm{[Li(Triglyme)][NTf_2]}$: Implications for Self-Diffusion, Viscosity, and Ionic Conductivity".

The repository is structured as follows:
- [simulations/](simulations/) contains the required input files for the molecular dynamics simulations of various systems. The simulations were performed with the GROMACS 2019.6 software package. All parameters different from default can be found in `SIMXX.mdp` while `sim1out.mdp` include all used parameters. For naming convention, please refer to the Gromacs-2019.6-manual. The start configurations are stored in `START.gro`, the corresponding force field parameters can be found in `topol.top`. An overview of the performed simulations is given in the [README](simulations/README.md) in the corresponding folder. 
