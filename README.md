# Diadema vision model

This repository contains the code used in [Li et al, 2022](https://www.biorxiv.org/content/10.1101/2022.05.03.490537v1).

### Folder "diadema model"

Contains all the source code of simulation and figures in the paper.

**UrchinNet_simulation.m** shows how to build the model and run simulation for one trial.

**behavior_simulation.m** simulates the behavior experiment and generates Fig. 2C and 4B given one type of stimulus.

**trajectory_simulation.m** simulates the trajectories (Fig. 5) given one type of stimulus.

**Fig2AB.m** generates panel A and B in Fig. 2.

**Fig3B.m** generates panel B in Fig. 3.

**FigS2.m** generates Fig. S2.

All the details and instructions are in the scripts. For all the simulations, you can change the stimulus pattern and width for your stimulus of interest.

### Folder "diadema_animations"

Contains the animations in the paper.

### Folder "stat_test_diadema_simulation"

Contains the statistical test for analyzing the significance of the circular mean vector in the simulation of behavior experiment (mentioned in Fig. 4).
