# Running Vortex test case with NEMO

Sequence of command lines executed to run NEMO VORTEX test case on ciclad

Contents : 
- 

## Required packages

svn co http://forge.ipsl.jussieu.fr/ioserver/svn/XIOS/branchs/xios-2.5  xios-2.5

svn co http://forge.ipsl.jussieu.fr/nemo/svn/NEMO/releases/release-4.0/r4.0-HEAD NEMOr4.0-HEAD

## NEMO/tests/MYVORTEX

I created my own version of NEMO/tests/VORTEX without any reference to AGRIF routines in code.

# References

McWilliams, J. C. and G. R. Flierl, 1979 : On the evoluation of isolated, non linear vortices, JPO (9), 1155-1182.

Debreu L., P. marchesiello, P. Penven, G. Cambon, 2012 : Two-way nesting in split-explicit ocean models: Algorithms, implementation and validation, Ocean Modelling (49-50), 1-21. 

Spall M. A. and W. R. Holland, 1991 : A nested primitive equation model for oceanic applications, JPO (21), 205-220.
