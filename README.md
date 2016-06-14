INSTALLATION INSTRUCTIONS:

1.	Alter the length of the variable *mydir* in both castelli*.f routines; the length specified, currently given as *23*, should
	actually reflect the string length of the directory employed (i.e., count the number of characters in the designated 
	installation directory name and change "char*23" to that number, "char*XX")

2.	To compile, enter the following at the commandline:  gfortran -ff2c -fno-automatic -fno-range-check castelli.f -o castelli.e
	Note the above set of options are a conservative approach.  They can be altered.  Also, the name of the execuatble can be
	modified.

# castelli_kurucz_stellar_models
