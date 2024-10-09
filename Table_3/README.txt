Step 1: Run the code in the DataGenerator.Rmd file. This will generate the data to be used in the simulations.


Now we may run the desired simulations. Note: For the GPyTorch methods, the RAM and VRAM measurements are only accurate for the first measurement. RAM and VRAM measurements must be collected manually after restarting the Python Kernel each measurement. More instructions are in the Simulations_1D.ipynb notebook. The following steps may be performed independently so you only need to execute the step you wish to reproduce.


Step HS-SVD: Open the HS-SVD_2D.Rmd file and follow the instructions. Make sure that your working directory leads to the Table_3 folder.

Step NNGP: Open the nngp_2D.Rmd file and follow the instructions. Make sure that your working directory leads to the Table_3 folder.

Step GPyTorch: Open the Simulations_2D.ipynb file and follow the instructions. Make sure that your working directory leads to the Table_3 folder.