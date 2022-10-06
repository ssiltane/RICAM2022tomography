# RICAM2022tomography

Matlab codes used in my minicourse "Invitation to sparse-data X-ray Tomography" given at the RICAM Special Semester "Tomography Across the Scales"
Training School "Inverse Problems on Medical Imaging and Small Scales" in Linz, Austria, October 5-6, 2022. You can find the slides of the lectures here: http://www.siltanen-research.net/talks.html

The main set of routines is the series from XR01_matrix_comp.m to XR10_B111_plot.m. You can run them in alphabetical order. Note that XR01_matrix_comp.m and XR04_SVD_comp.m can take several minutes to run.

There are also a couple of smaller things. 

(a) The routines tomo2x2_TV_comp_bruteforce.m and tomo2x2_TV_comp_quadprog.m are for the simple 2x2 pixel example.
(b) The routine Complex_wavelet_wavefront.m shows how the dual-tree complex wavelet transform can be used for estimating wavefront sets of functions. 
