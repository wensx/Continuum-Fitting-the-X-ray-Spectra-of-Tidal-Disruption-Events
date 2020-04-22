# Continuum-Fitting-the-X-ray-Spectra-of-Tidal-Disruption-Events
slimdisksolution.zip

The disk solutions for case (M=10^7Ms,a=0.998) and (M=4x10^6Ms, a=0.7) are included in slimdisksolution.zip. 
They are all "txt" format files. The name of each file shows the imformation of BH mass, BH spin and accretion rate, 
e.g. for name ''10799060000.txt'' 107 means 1.0x10^7Ms, 99 means a=.99 (here 99 indeed means a=0.998),60000 meams mdot=600.00;
for name ''4067001000.txt'', 406 means 4.0x10^6Ms,70 means a=.70, 01000 means mdot=10.00. The accretion rate mdot is in unit 
of Edd (1.37e21 x M_6 kg/s),and the radiation efficiency eta=0.1. Viscous parameter alpha=0.1.
There are 12 colunms in each file, correspondening to:
radius r [M], radius velocity V_r [c], mid-plane temperature T_c [K], angular velosity Omega, beta=P_g/P, H/r,total flux F_r [erg/cm^2/s], surface density Sigma [g/cm^3], effect temperature T_e [K], u_r, u_t and u_\phi.
Note that T_e should multiply by 2^0.25 due to a factor of 2 have been ignored in the output file.
