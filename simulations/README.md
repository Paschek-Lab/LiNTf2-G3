# Studied Systems
This folder contains input files for performing simulations of various mixtures of $\mathrm{[Li][NTf_2]}$ and triglyme (G3). The simulations were performed with the GROMACS 2019.6 software package. All parameters different from default can be found in `SIMXX.mdp` while `sim1out.mdp` include all used parameters. For naming convention, please refer to the Gromacs-2019.6-manual. The start configurations are stored in `START.gro`, the corresponding force field parameters can be found in `topol.top`. 

The studied systems are named by their respective salt mole fractions. For example, the folder [X_0.2000](X_0.2000/) contains the input files for the binary mixture with $x$($\mathrm{[Li][NTf_2]}$) = 0.2.
  - The subfolder [sim_483K/](X_0.2000/sim_483K/) contains the input files for the eqilibrated cubic simulation boxes at 483\,K.
  - The subfolder [orthoboxy_483K/](X_0.2000/orthoboxy_483K/) contains the input files for MD simulations using an orthorhombic unit cell with $L_z/L_x=L_z/L_y\approx 2.7933596497$ according to the ``OrthoBoXY'' method
