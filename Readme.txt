# ScalableGP_Testing

These files contain the code necessary to run the simulations and experiments contained in the paper. Each folder has it's own instructions and readme. Each folder consists of four primary components: data generator/processor .Rmd files to simulate the data, a HS-SVD-xxx.ipynb file to perform the HS-SVD simulation/experiment, a NNGP-xxx.Rmd file to perform the NNGP simulation/experiment, and a Simulations-xxx.ipynb file to perform all of the GPyTorch simulations/experiments. The Environment.yml file contains the conda environment. The correspondence is as follows:

Table_1: 1D Simulation
Table_2: 2D Simulation
Derivative_Process: Derivative Simulation and Experiment
Genomic: Spatial Transcriptomics Experiment