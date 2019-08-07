Description of the enclosed files.
------------------------------
Folder ./dist/ contains data files dist_X.XX.dat. 
Each file represents sampled distances from an individual Umbrella Sampling (US) simulation.
Each US simulation was performed with an applied harmonic restrain E(x)_i = k/2 * (x-x_i)^2,
k = 100 kcal/mol, x_i is defined as X.XX in the filename (dist_X.XX.dat).

The statistical analysis was performed using The R Project for Statistical Computing, https://www.r-project.org
within a Jupyter notebook (NR-SVD-CDyn-octanedithiol.ipynb).
See https://docs.anaconda.com/anaconda/navigator/tutorials/r-lang/ for the installation instructions.

