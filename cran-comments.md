* Reduces tests which run on CRAN (complies with email from CRAN/Ligges (18/06/2018))
Tests take now only about 120s to 150s on win_builder/R-devel.
* Complies with email from CRAN/Hornik (17/05/2018): removed superfluous/undeclared package dependency in unit tests (lattice)
* Adds compatibility with upcoming ggplot2 v2.3.0

### R CMD checks
### Test environments
* Ubuntu 18.04 64bit (release)
* Travis-CI Ubuntu 14.04 (devel)
* winbuilder (devel, release, oldrel)

### R CMD check results
There were no ERRORs, WARNINGs or NOTEs. 

### Downstream dependencies
moveVis OK


