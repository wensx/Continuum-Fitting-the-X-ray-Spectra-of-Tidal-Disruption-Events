# Continuum-Fitting-the-X-ray-Spectra-of-Tidal-Disruption-Events
slimdisksolution.zi

The disk solutions for case of (M=10^7Ms,a=0.998) and (M=4x10^6Ms, a=0.7) are contained in slimdisksolution.zip file. 
They are "txt" format files.The name of each file review the imformation of BH mass, BH spin and accretion rate, 
e.g. for name ''10799060000.txt'' 107 means 1.0x10^7Ms, 99 means a=0.99 (here 99 indeed means a=0.998),600000 meams mdot=600.00;
for name ''4067001000.txt'', 406 means 4x10^6Ms,70 means a=0.7, 01000 means mdot=10.00. The accretion rate mdotis in unit 
of Edd,and the radiation efficiency eta=0.1. Vicious parameter alpha=0.1.
There are 12 colunms in each file, correspondening to:
r [M], V_r [c], T_c [K], Omega, beta=P_g/P, H/r, F_r [erg/cm^2/s], Sigma [g/cm^3],T_e [K], u_r, u_t and u_\phi. Note that T_e should multiply by 2^0.25 due to a factor of 2 have been ignore in the output file.
