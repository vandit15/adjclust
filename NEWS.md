# Package: adjclust

## Version 0.2.3 [2017-02-02]

* Updated LD vignette
* In adjClustBand, renamed flavor "Koskas" to "PseudoMatrix"

## Version 0.2.2 [2016-12-01]

* Added dummy R/adjclust.R so that document() adds 'importFrom Rcpp evalCpp' to NAMESPACE
* "Fixed" warning at check due to .hpp file in src (this warning should not exist IMHO)

## Version 0.2.1 [2016-11-09]

* Added minimal documentation
* Replaced "std::cout" by "Rcpp::Rcout", and so on for "exit()" and "cerr".

## Version 0.2.0 [2016-06-24]

* Incorporated Michel's implementation (R function 'HeapHop')
* 'adjClustBand' is now a wrapper to call either Alia's or Michel's
  implementation

## Version 0.1.0 [2016-06-24]

* Created from BALD
* Added a test to check that we are reproducing the results of BALD::cWard
