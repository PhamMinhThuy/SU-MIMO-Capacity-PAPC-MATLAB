# Guidelines for the MATLAB implementation of computing single-user MIMO capacity under per-antenna power constraint 

* DATE OF CURRENT VERSION (V1.0): Nov 2017 
* CONTENTS: MATLAB implementation of fixed point and alternating optimization algorithms for finding the capacity of a single user MIMO with per-antenna power constraint
  - SUMIMO_Capacity_PAPC: Main MATLAB file to create the scenarios and call the related algorithms.
  - Alg1_fp: Algorithm 1 which is based on fixed point method
  - Alg2_ao: Algorithm 2 which is based on alternating optimization
  - Sample: Sample channel matrix
  - Snapshot_example
* RELATED PUBLICATION: 
T. M. Pham, R. Farrell and L. N. Tran, "Low-Complexity Approaches for MIMO Capacity with Per-Antenna Power Constraint," 2017 IEEE 85th Vehicular Technology Conference (VTC Spring), Sydney, Australia, 2017, pp. 1-7.
* NOTICE:
  - The code was built and tested on MATLAB R2013, R2015 and R2016.
  - The implementation generates results for the covariance matrix, capacity, duality gap/ relative objective error, and number of iterations. 
* BUG REPORTS: If you find any bug, please send your feedback to m.phamminhthuy@gmail.com.
* LICENSE: The code is licensed under the GPLv2.


If you use our code in your research and/or software, we would appreciate citations to the following paper:

T. M. Pham, R. Farrell and L. N. Tran, "Low-Complexity Approaches for MIMO Capacity with Per-Antenna Power Constraint," 2017 IEEE 85th Vehicular Technology Conference (VTC Spring), Sydney, Australia, 2017, pp. 1-7.
