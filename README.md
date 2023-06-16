# FFC-Paper-ESI-data
ESI for https://doi.org/10.1021/acs.jpcb.2c01372

Supporting files include:

abinitio_charges:
	- gaussian log files
	- summary of atomic charges (excel)
	- .chg files (like .xyz, with additional column containing atomic charges)
abinitio_scans:
	- energy scans at the full MP2/cc-pVTZ//B3LYP-GD3BJ/6-311+G(d,p) level of theory
	  (given as coordinate value in the first column and energy in the second)
data_files:
	- Key LAMMPS data files:
	- one directory for all non-polarisable data files together
	- one directory per polarisable simulation, containing data file plus pair coefficients
force_field:
	- Contains force field (.ff) files for use with fftool https://github.com/paduagroup/fftool
	- xyz files with input topology
input_files:
	- LAMMPS input files
MDresults: (time unit - where applicable - is femtoseconds)
	- alpha2 non-gaussian parameter values
	- charge arm histograms, distance unit is angström
	- charge lever moment histograms ("chargearm_normalised")
	- mean squared displacements, starting with "concat"
	  (the projections are given in an extra file - e.g. #1 is in x direction for the cations)
	- radial distribution functions
	- rotational autocorrelation functions, first and second Legendre polynomial, chargearm and P-CH3 vector.
	
	
