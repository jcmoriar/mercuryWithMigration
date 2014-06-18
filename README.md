## Mercury Integrator with Star and Disk Tidal Interaction

This code is a modified version of John Chambers' mercury N-body integrator that incorporates tidal forces from the star and disk. These changes are implemented in the user defined force subroutine, mfo\_user (with helper subroutine, x2ae) in mercury6\_2.for following the method of [Papaloizou and Larwood](http://adsabs.harvard.edu/abs/2000MNRAS.315..823P). The tidal forces are calculated according to the following equations: 
 $$ a_mig = -\frac{v}{t_m}  $$
