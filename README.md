# C-ChiSquared

This code will implement a parallelized goodness of fit chi-squared for a number of built in functions.

Chi-squared goodness of fits are very useful for data sets with small sample sizes and where you know the
equation to apply to that data.  It allows one to easily take into account asymmetric error bars and is
both simple enough in its implementation that one should intuitively know the expected computations
behind the scenes.  

This started as a convenience idea of having a canned chi-squared for future use that is implemented in C giving it speed even if my data set starts to get big.  The addition of a parallelized
chi-squared is to add further speed to the program as well as an excuse for me to keep up on coding with
message passing interface (MPI).

The only dependancies on "making" the code should be a relatively updated gcc compiler as well as
an install of MPICH. MPICH is a heavily used, and free, implementation of MPI.  MPICH can be found here:
<url>https://www.mpich.org/ </url>.
