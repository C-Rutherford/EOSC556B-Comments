# EOSC556B
EOSC556B: Applied Geophysics, UBC,  2024 Winter session

This is the git hub repository for the EOSC556B final project.
This code runs an inversion for Induced Polarization parameters from TDEM.
Forward modelling uses an empymod.

Simulation models are based on deep Sea Massive Sulfide exploration.
Models are inspired by the JOGMEC-WISTEM survey.

Induced polarization parameters are available with either the cole-cole model or the pelton model.
Steepest descend and the Gauss-Newton method are available for optimization.
Jacobian is approximated by finite difference.
Plotting functions about objective value grids are also prepared.

Reference  
empymod  
Open-source full 3D electromagnetic modeller for 1D VTI media 
https://empymod.emsig.xyz/en/stable/gallery/tdomain/cole_cole_ip.html#sphx-glr-gallery-tdomain-cole-cole-ip-py   
K. Nakayama,(2019), Application of Time-Domain Electromagnetic Survey for Seafloor Polymetallic Sulphides in the Okinawa Trough  
https://www.earthdoc.org/content/papers/10.3997/2214-4609.201902383

