## Revision history for the R/negenes package

### Version 1.2, 2025-05-11

- Changelog -> NEWS.md

- In CITATION file, citEntry() -> bibentry() and personList() -> c()


### Version 1.0-12, 2019-08-05

- Fix technical problem in documentation for Mtb that causes a warning in
  the development version of R.


### Version 1.0-11, 2019-06-28

- Convert documentation to Roxygen2 (with markdown).


### Version 1.0-8, 2018-04-02

- Small changes to avoid Note about "R_registerRoutines".

- Speed up examples for negenes().


### Version 1.0-5, 2016-05-21

- Changed author() calls in inst/CITATION.


### Version 1.0-3, 2015-09-11

- Import sd from stats library in NAMESPACE.


### Version 1.0-1, 2012-03-09

- Fixed bug in negenes that could lead to a memory overrun.


### Version 0.99-2, 2011-11-07

- Added NAMESPACE.


### Version 0.98-9, 2011-03-20

- Replaced datafile for Mtb80 with a compressed version.


### Version 0.98-8, 2009-06-30

- Added a CITATION file.


### Version 0.98-7, 2007-10-09

- Minuscule changes to the help files, to conform to a change in R.


### Version 0.98-5, 2004-06-30

- Slight revision to the negenes() function: added PACKAGE="negenes"
  in the .C() call.


### Version 0.98-4, 2004-02-02

- Fixed a tiny error in the documentation.


### Version 0.98-3, 2002-08-10

- Revised the negenes function to return Rao-Blackwellized estimates
  of the probability that each gene is essential, and of the posterior
  mean of the total number of essential genes.


### Version 0.97, 2002-07-31

- Included a data object, Mtb80, containing the number of TA sites in
  M. tuberculosis CDC1551 genome, by the "80% rule."


### Version 0.96, 2002-07-16

- Changed the argument "start" in negenes() to "startp", the initial
  proportion of genes not known to be essential that will be assumed
  essential to start the Gibbs sampler.


### Version 0.95, 2002-07-14

- Revised the package to take care of the case of insertion sites in
  regions of gene overlap.  It is assumed that the genes 1, 2, ..., N
  are in order around the genome.


### Version 0.90, 2002-07-13

- A newly created package.
