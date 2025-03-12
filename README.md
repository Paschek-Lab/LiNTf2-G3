
# Structural Transformations within the Solvate Ionic Liquid [Li(Triglyme)][NTf$_2$]: Implications for Self-Diffusion, Viscosity, and Ionic Conductivity
This folder contains input files for performing simulations of various mixtures of [Li][NTf$_2$] and triglyme (G3) characterized by their respective salt mole fractions X. The simulations were performed with the GROMACS 2019.6 software package. All parameters different from default can be found in `SIMXX.mdp` while `sim1out.mdp` include all used parameters. For naming convention, please refer to the Gromacs-2019.6-manual. The start configurations are stored in `START.gro`, the corresponding force field parameters can be found in `topol.top`. 
For each system, the equilibrated start configurations at 483 K are given. Subfolders "sim" contain configurations of MD simulations with cubic simulation boxes, whereas subfolders declared as "orthoboxy" contain orthorhomic MD simulation boxes used for employing the OrthoBoXY approach.


$\zeta$
